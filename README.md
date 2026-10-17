# Repolex Knowledge Graph of intake/intake-stac

RDF knowledge graph data for [intake/intake-stac](https://github.com/intake/intake-stac), parsed by [repolex](https://repolex.ai).

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
rlex download intake/intake-stac
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 227a74c5d3968b926ab0bda1526fa7ae3558deab
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 227a74c5d3968b926ab0bda1526fa7ae3558deab
│           └── chunk-001.nq.gz
├── blob
│   ├── 09ea1b65ed4de3fe3a39a29ca9ad07a8bb9922d5.nq.gz
│   ├── 0c8547fb860e5578e177661e17f4e90c26f861e6.nq.gz
│   ├── 1032099102752ca3abf381a4f5eed96815efc318.nq.gz
│   ├── 10a3b587b0f798c4b71c0b7ac293a2190d5bf971.nq.gz
│   ├── 139f1d12e387fe8b070fc4c6f17092b3005082cf.nq.gz
│   ├── 1467422fe1c4056cfa27e5c64b00b0774ea0f264.nq.gz
│   ├── 1faf220f4df828310fa90462de42f3a796969e2d.nq.gz
│   ├── 268b178ab72f377b60a7707b1c800b241cb9fa14.nq.gz
│   ├── 271c8436967948df6c939e16028a878615851656.nq.gz
│   ├── 28157f4e7b96b1d1bdd9ec1622efe3db6d2b775a.nq.gz
│   ├── 2cbe1c63c078d9b2ca7563c4dbba1a498a7ff05a.nq.gz
│   ├── 2df9a8cbbb680a1e83d41f835efafaefffc4888b.nq.gz
│   ├── 2e6c12824b7c8ed87da79ae0ff44991bdd59bec9.nq.gz
│   ├── 2e6f9924700b392f28038c6bfaba23b5eae7b9e9.nq.gz
│   ├── 3602107d4096f84c0f39c200f9484862bbe1afef.nq.gz
│   ├── 367022bf96d9ba7f2c9e4a7e3faab5f18010904d.nq.gz
│   ├── 42b54d311f7d6b71567e9ff5cb3326a2eb611ed8.nq.gz
│   ├── 4500ec8432132898a0854732409435189e863313.nq.gz
│   ├── 4680f104d22354bfdc9c34696bab94017f24ca0f.nq.gz
│   ├── 4aab824b65a226f53688234c21f8407440a99d16.nq.gz
│   ├── 4afe071f604f5476e332b7236b3ce982bada7196.nq.gz
│   ├── 6302d0cafd951964c5c2baba4949c53e3e7efee6.nq.gz
│   ├── 67b0a539ae6623d06c383359d078118d4a66cf78.nq.gz
│   ├── 6a494c5a14a03dbccb84411c9e94f80dc91d76ac.nq.gz
│   ├── 6b2a01a441b801a8152fc217f7bccfbee9ac52a4.nq.gz
│   ├── 6e0000184b893a2b171590c3d99b7abd5a885ab9.nq.gz
│   ├── 755406b2b47b20e15b98f1d3c0772992f292c53a.nq.gz
│   ├── 799c5934010654e5990192ad13479f822b9d083b.nq.gz
│   ├── 7aec066cb50ac55bb73112f96f6173b8bdcb9597.nq.gz
│   ├── 834d68d9c94fa2d8a7e8fdafc9993fc75201f808.nq.gz
│   ├── 95eebdbccff127a7a9eb7d5e34ee049b964334cc.nq.gz
│   ├── 96bbd39996bc83fb7a1f5da2c528443d4d7ca7ed.nq.gz
│   ├── 9b5b60428384d948bbc3d049bf7fde0944f28e88.nq.gz
│   ├── 9bdcdffd09c3bd15ec555e58d78edaca46dce058.nq.gz
│   ├── a01b9e495d21ab59f73c002c7855a8cecaac0734.nq.gz
│   ├── a2dc083ba2331bf80d38bec36037fff403477aab.nq.gz
│   ├── aca5495831336d6b4b54431b4cf1688862ac85cc.nq.gz
│   ├── ae83e05d4c5f841de94f2ed705635d838282c9d5.nq.gz
│   ├── bc2b2d85ff13f733ba3d5d7114be6425424caee2.nq.gz
│   ├── bd3b8f89ea73f1f0d0abd0be4809fb21afaa488a.nq.gz
│   ├── bebdd3f59c29ab86dea704c4b2d44b3939a45645.nq.gz
│   ├── c08cdcf1f22c13abf1a669eaaa10a379389369a4.nq.gz
│   ├── c3bb54113ca821df152b7c1cc62fe3b7f38afb7d.nq.gz
│   ├── cd9b89ff907a25b4b4ac79fd721eb9c17b3af869.nq.gz
│   ├── cee86f4e5df2ab71feaedf604547e61bc5347a95.nq.gz
│   ├── d1d1190be709d50e96cb883e915019c026ff3a5a.nq.gz
│   ├── d7759cf87282072b13978ccd40537c193fe2df96.nq.gz
│   ├── d948a7129b148e4923ae9b9737aad0f7a91eb94a.nq.gz
│   ├── df5db513b8f762c40e17d91dccb6435648445771.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e84a72417ea9ca62cdd5cbab209a82056b231559.nq.gz
│   ├── f0192c27d894e758b115feea05ee8ee9be7288e9.nq.gz
│   ├── f5cd008a6aa8a22280ceb9559454889f3c1e438b.nq.gz
│   ├── f842975fb977debb35d4a0c295a02904f30de2d9.nq.gz
│   └── fb8680c262ef9c5ac6e26d314a0c69eee523a0e0.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 227a74c5d3968b926ab0bda1526fa7ae3558deab.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 63 files
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

[intake/intake-stac](https://github.com/intake/intake-stac)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
