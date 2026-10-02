# Repolex Knowledge Graph of block/frfr

RDF knowledge graph data for [block/frfr](https://github.com/block/frfr), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download block/frfr
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b4d7462d0ced29f65abb03abfd8442808d528493
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── b4d7462d0ced29f65abb03abfd8442808d528493.nq.gz
│   └── repolex
│       └── b4d7462d0ced29f65abb03abfd8442808d528493
│           └── chunk-001.nq.gz
├── blob
│   ├── 01c8f32b8b2e97094ecbd7bf414853497fdd1bf2.nq.gz
│   ├── 030a6a5bafc5d8b90371001782a89efa8a34abbc.nq.gz
│   ├── 03612f88553c375731b689675d69cf3f76790f69.nq.gz
│   ├── 0450e227b64a2085cb030b6ea82c7f2135dab423.nq.gz
│   ├── 078d5f0f53bdf5c7c61dc1697f3b2d75e7d7d366.nq.gz
│   ├── 08121f06178a0a6861612bb8b98c97f9423dbc3a.nq.gz
│   ├── 0acb59b94fda77ea96243ca2ef86472f03e8b940.nq.gz
│   ├── 0b4a2ed51ca28f01ada51f7e9807595980c649a1.nq.gz
│   ├── 0ba9db25329d0b336e39ca8cde8470c5b7bc45eb.nq.gz
│   ├── 0c87159fc4c4c7adc1b14dedb06d958205da1c4f.nq.gz
│   ├── 0f0b00b690cd21540209a97451e58ced9b8c1c5a.nq.gz
│   ├── 10400273c42bcbeaab3b310c3aae6c6cea5ab7ae.nq.gz
│   ├── 12a3c16993702786233dd7b996fd346dc716943f.nq.gz
│   ├── 170c75f2a08e6f5cd910c25d910ce43a8e1aca35.nq.gz
│   ├── 187e005a5c0665a175b71d4ddcca86b56e1e0405.nq.gz
│   ├── 1970467d78cbff0fa5bf6f3a3ea49defb8ff7bcf.nq.gz
│   ├── 1ac335813e2636abc508e065d8b61629c34d40f5.nq.gz
│   ├── 1b7486d5b3e9b4ff699dae5f45397bf44f873f85.nq.gz
│   ├── 1bc469e68eb776aa52185c6cbfc5cdcaee837ce3.nq.gz
│   ├── 24c5ddc67e77e4b3d5c1f89c2cd956eef5d78a8c.nq.gz
│   ├── 25f0bc5ed80683a81f46e6bfd1cf8ea0b56c6807.nq.gz
│   ├── 282a8b47decc76dbc5b558277d0b286e9363d17e.nq.gz
│   ├── 2a4bf2236aa7d484090c67935280485fee3dcb06.nq.gz
│   ├── 2b965be0a4d19c36fae3c0e5c28c7719466fdc13.nq.gz
│   ├── 2d04c918cdebcd13458765cae795d4980b9b5625.nq.gz
│   ├── 2db3353457a440f074785a7fc14a90b63835586c.nq.gz
│   ├── 32fd68c52437ef645c4103701ef59a0c8be38428.nq.gz
│   ├── 37e95fbed6e3d4396fa9d989d7c2f633fc48be92.nq.gz
│   ├── 3afb4926f90036ad21dd9fe2ea89d6e9fb53b572.nq.gz
│   ├── 3d14ac966d3b7812f02c517bbecd006d0a8ce386.nq.gz
│   ├── 3d36d869b07b50a34511cae1b71632cf320d7d40.nq.gz
│   ├── 3d803c0baa45fbe10c93fc9c4f783124cf63c659.nq.gz
│   ├── 4031a2120a0faea043d56de0e62684412d789427.nq.gz
│   ├── 43a287ec0a88e6135ec86dc7ad3133ee18695f54.nq.gz
│   ├── 455976149c94c2edb6e58b0a750c3dfcc52a6331.nq.gz
│   ├── 45ec8a7eb81c9f7930ac7a5a7a5e72e778ca07d1.nq.gz
│   ├── 46c2771fede6eff85fa83a3df2d04582ed4eb349.nq.gz
│   ├── 49d45f547801337e87753f64ea5cb4df6b03ccf9.nq.gz
│   ├── 49e00d0e1df00b5942e993d0cf011ee6dd93d7fa.nq.gz
│   ├── 50869c7c54bec280b76d7f7d9abd27100c2ed26f.nq.gz
│   ├── 5406ff075f23b2c11bf8f492861951649bfe2639.nq.gz
│   ├── 5413626ccc0c7d10abf82c2db8f616fd517f6c30.nq.gz
│   ├── 5a1190a3e1bffb229a63d91a98c77c5b20c63d8a.nq.gz
│   ├── 5b348de50029b21deb952d01e0403fcbde5f6094.nq.gz
│   ├── 5eac365d9c89f887af4fa2f5fcb0997de6cfb55d.nq.gz
│   ├── 66429a31cbff09edc146f29f4136df480153921b.nq.gz
│   ├── 691a8f79984d3d504cc7995f5415480491fca290.nq.gz
│   ├── 69628a65db94f4f7c2f8fbdb1364112562997eab.nq.gz
│   ├── 6bccf43368fd7c96d9c659562a5142b8b8cb98a1.nq.gz
│   ├── 6fe4fd5626ded9f91a748c8b5e84c268bbc71d54.nq.gz
│   ├── 70a2d870ef9bafe18de4ca0614bafff6698d1c12.nq.gz
│   ├── 71fb5e20b93b378c91941857ce2d262d80f10c06.nq.gz
│   ├── 736e971af89acb4311664dbe4977801d430f9351.nq.gz
│   ├── 753a26d902c78978c523e77c95862a07c6420bfe.nq.gz
│   ├── 77f5ca4e8d98bef5b39e2df22babca29dcfb7a0e.nq.gz
│   ├── 78fceaf330ff7ec3e682c3c3ab416d13a7b08025.nq.gz
│   ├── 7a747aca319f87175f96a1f67ba9ec82d4e5c76e.nq.gz
│   ├── 830fa32f713c2d1338dfa088b35a6cb9d95ed224.nq.gz
│   ├── 85699cf5aed5d3c6acd7eec98d521a3d30e40bae.nq.gz
│   ├── 869db134def8e1ece9db19a40e25284b6cb89530.nq.gz
│   ├── 89aa3347919914a6aa22cc97eb7d9c4350d5f96d.nq.gz
│   ├── 8e2bcb5816e8f8934e838bfab3ae9aa467857c74.nq.gz
│   ├── 90da71e20bf57bfe2dc4c9b12735d4675005ed12.nq.gz
│   ├── 93eb22fd12de780cba6ba4aa90fa0fc750172dd8.nq.gz
│   ├── 957cdacff123a37a47ab60eeea29bf41be495ff7.nq.gz
│   ├── 9582fc588754f78d9875691a3bd5e674295436b3.nq.gz
│   ├── 97ede7ee6f2d37bd2d76e60c0b6a447bee718b05.nq.gz
│   ├── 985082a4725320674186ef1ca281a55edb2f2a8b.nq.gz
│   ├── 99324a594f1a63c526e0e5e1b3e38d4e793c2573.nq.gz
│   ├── 9992c89e25e2577b479e3eeb2a982e298c4409d2.nq.gz
│   ├── 9b43d36803aceb6b0ba02f91eb1816601de05232.nq.gz
│   ├── 9d629f75a18a5e5d1125b75b63dd2d9c7a99d485.nq.gz
│   ├── a27456a35db4c30f91a67e6b7009f3bcfdc119bb.nq.gz
│   ├── a44c3a7d90ca70ae400d19ef197d92f41febb930.nq.gz
│   ├── a8ca4cc47b02d943b904912be0a54eee485e596e.nq.gz
│   ├── ac083feaa90fe8084b72f0ee2551a10049ac16f8.nq.gz
│   ├── ade7d63d79cc010e22cc68b6dd5caa1de70f130a.nq.gz
│   ├── b53b6e98c2542895cea7c1440636986c42c9668c.nq.gz
│   ├── b5e524383a3f36d875fbe85b6cb9988e238132e8.nq.gz
│   ├── bb511b67ff9805580b81475f7225baa9a504a8bb.nq.gz
│   ├── bbb4a1ca6e0734ff1858e451114f2f81eb5c563f.nq.gz
│   ├── bfe93a82c34dce3f2bc91ef01a7e099159e9842b.nq.gz
│   ├── c55270ba53c88aa07bfc2430f34e98d773bf69ca.nq.gz
│   ├── c9f3681b03130826f812d5454e3306cfa9403c6b.nq.gz
│   ├── ca491c4f2c0374d9d27a510d2c4fb1da21b4b00c.nq.gz
│   ├── cbf42d24521f525cb8424afa59842ae2ac59ddfa.nq.gz
│   ├── cc8fd09cbb1b9258d17045ca3bb7635e4f38097a.nq.gz
│   ├── cca3af225d677d2f500cc78b44625c403d06399a.nq.gz
│   ├── d192548316a9a2dd505f8b25ff3a909d89631306.nq.gz
│   ├── d3c571f7a541100ae11a5d98c6d94ece54c015de.nq.gz
│   ├── da6ed89f8f3e8b40a97697c65aae7359b15061a9.nq.gz
│   ├── e4e333f333b89422e2e4aa77d533ddbab8d8671b.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e74ccdaf004d5e05db0d958b2e916105028b0cbe.nq.gz
│   ├── e8a37e19f18c9a350e0e13592d13b8e84dd913dd.nq.gz
│   ├── ebd3b1804c7a45a02a00c537ffcb66381c11410a.nq.gz
│   ├── ecbd4669d9fdf1d640ea281be248dae28a121f09.nq.gz
│   ├── edb6ab68b73e79aea617208a4e81acf0a990b054.nq.gz
│   ├── ee09d3fb331d57cef4f21bc59cd5fd014ec20414.nq.gz
│   ├── ee26d9d7e0b856c516b1299c3367e843233b0028.nq.gz
│   ├── ee57556d000ee6d0da7f6ec75e30d75630a010de.nq.gz
│   ├── f5c167f1c043dcac96615bd68c6678e522f6db85.nq.gz
│   ├── f904386378348521b1284577c6a097ef898008d8.nq.gz
│   ├── f99a88b626569f516e10225c2be066fbd460b919.nq.gz
│   ├── fcda76a9284210dd8e8ba73cadd48d5c745ca309.nq.gz
│   ├── fe5cdd83f440dace68b9994c0ae6f28923f11174.nq.gz
│   ├── fed1e69dcc07081257a355f8b3313a7b98660963.nq.gz
│   └── ff94a47c43062dcce20f24770e2cf13b2504eb8d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b4d7462d0ced29f65abb03abfd8442808d528493.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 117 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[block/frfr](https://github.com/block/frfr)

---
*Parsed on 2026-10-02 by [repolex](https://repolex.ai)*
