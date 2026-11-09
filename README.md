# Repolex Knowledge Graph of chronotope/chrono-tz

RDF knowledge graph data for [chronotope/chrono-tz](https://github.com/chronotope/chrono-tz), parsed by [repolex](https://repolex.ai).

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
rlex download chronotope/chrono-tz
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 64c3e4daa9fa5a4ee4d5a6098609790142552fe5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 64c3e4daa9fa5a4ee4d5a6098609790142552fe5
│           └── chunk-001.nq.gz
├── blob
│   ├── 0809dfd859184d5dd727e099613cee3fa04afd15.nq.gz
│   ├── 0bea97e1822b277d6349f9746fc7bfabe98a4ea0.nq.gz
│   ├── 24a13fc02436ebd43a07f35c2ea61578fea8d768.nq.gz
│   ├── 2c1834fbfd1def19ebe84fb9574d981cec4b7325.nq.gz
│   ├── 2cdd048b190557a0a3f849d7c39d52bafee0f642.nq.gz
│   ├── 30a1b6eb43971f5d53760c97f60da55277a01110.nq.gz
│   ├── 35612217e42e73c00eec5361b9cd2938cd53e211.nq.gz
│   ├── 35c2078e13b89d90584431f530446bdb4d100f68.nq.gz
│   ├── 37d69e8f3d9a24dcdc88e9368f9cef19fcb65ee1.nq.gz
│   ├── 42cbb46a5a02c656d945d37774fc15aec1a2a43e.nq.gz
│   ├── 43177a060eaf9362172e24811b89fe72cbe7ba9a.nq.gz
│   ├── 4b121ad1c44ed59630fdb765ca7241842be339b9.nq.gz
│   ├── 4dad5c49adeb304ae360cd4292a9fa914d5bc95e.nq.gz
│   ├── 57f0bd3ba24447e57227456498f6f2c87a20334c.nq.gz
│   ├── 65482a583f9b4f17fbffb18b42711268003f324d.nq.gz
│   ├── 733277ae513e1aa58881b644194118db52aa8558.nq.gz
│   ├── 77a426b9ffa5199b6be31bfa9fa1354c7276f391.nq.gz
│   ├── 86802349d3914063ddad25ccfb2c0bce9b0f8e77.nq.gz
│   ├── 8b211d64661569214ae74719a11eeb3cfc4b3f3e.nq.gz
│   ├── 93788d1f178439bc9805fa78ec26fc44f897939c.nq.gz
│   ├── 93bc3505e55208a71e351703f3a8e7ce0be18440.nq.gz
│   ├── 98a4b3359130714f056e0acab3f8342870dedc38.nq.gz
│   ├── 98dd7a15a89f7342973c99f8ca25dbc9fc7c2d8e.nq.gz
│   ├── 99a91eba7c58747d6624ec04cb814127d0de2f5f.nq.gz
│   ├── 9db601098c4ffebc7851a810976960e3ec6e091d.nq.gz
│   ├── 9dddb1aaf98197554c57d5ee80c29007d28739fa.nq.gz
│   ├── 9f5e0deaa83c5a64c53ed3e8ed2fd96cc65ffc8e.nq.gz
│   ├── a576c4a5836b66124e6aa67258b45062be16b69b.nq.gz
│   ├── a636bef754a7c7cfbbd36df49f4862cb187960b2.nq.gz
│   ├── a9d37c560c6ab8d4afbf47eda643e8c42e857716.nq.gz
│   ├── afb427ac24bee17f4f309fdd390111fd2e614bfa.nq.gz
│   ├── b271f22c6dafe075bb0a51074941ce72e961e4bd.nq.gz
│   ├── bc74467b24b09c8d6a37598a314b4dd9733f7f24.nq.gz
│   ├── bd8d937ad0dc20381c9ad5fa211010ecee6fd218.nq.gz
│   ├── c0b1dc995d959f4304b1b1eb339e0f1173c4d96d.nq.gz
│   ├── c839ef5c618950d200ea69c54a2e17a6b40676be.nq.gz
│   ├── e1c27e9f91a54e06c74a00563bc7b0630801586a.nq.gz
│   ├── e64a511ae871765faaa2b5859a83d4e31e975b60.nq.gz
│   ├── e6f89a0ba4dd827d2e31f98b5e31daff031b3124.nq.gz
│   ├── e93daa1559063515ca4d74363ef544e5b133bd26.nq.gz
│   ├── ea5b60640b01f74e295037aa8a6b7d4ea278a739.nq.gz
│   ├── ef3c300f91810ff8342ace145a4df2b1143e26d3.nq.gz
│   ├── f77fba4fdf8183af81d8906a8bb29e2f7e829df2.nq.gz
│   └── fed2dbe6e55727afadd5719ecfd64543544e6252.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 64c3e4daa9fa5a4ee4d5a6098609790142552fe5.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 52 files
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

[chronotope/chrono-tz](https://github.com/chronotope/chrono-tz)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
