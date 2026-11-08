# Repolex Knowledge Graph of canonical/sdcore-pcf-operator

RDF knowledge graph data for [canonical/sdcore-pcf-operator](https://github.com/canonical/sdcore-pcf-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/sdcore-pcf-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fc84499edee777d4e9581f229600ba3f59bbcfc1
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fc84499edee777d4e9581f229600ba3f59bbcfc1
│           └── chunk-001.nq.gz
├── blob
│   ├── 000bb3c6e954b1e0e8d6fc7d30fbc8c252df7186.nq.gz
│   ├── 07e10a08514124ce2ce63de2bd3fccecb89797e1.nq.gz
│   ├── 0b680d508757e960bfc1e7190cc29509514d1562.nq.gz
│   ├── 0ff992b299b3f0224c0a4575fb68ea04de62af99.nq.gz
│   ├── 13af703428e23ce7d56cf7a1bc7061b64a8f6a18.nq.gz
│   ├── 1c4bfcce5fd92cdec1fcca155f77292d0f9e56f8.nq.gz
│   ├── 2055a28de90818ffa33b0a2ff4e1fdbd93eb1473.nq.gz
│   ├── 24b9227897e73e7052f229e79372cce8b548409c.nq.gz
│   ├── 35e2e1433ed56e7e49a18f2fbdf76db1006d2a19.nq.gz
│   ├── 3bcd8a9f726c1e7ff32172d0ed5d95ab6436a34c.nq.gz
│   ├── 46fdfb6ff31d8f845aa61ec8d9c441011982757c.nq.gz
│   ├── 4d394c33b8ea132a10ef09db97c9509d10e14fd1.nq.gz
│   ├── 530e7adad83f81bd6e6a52ac201b241d2947fdbf.nq.gz
│   ├── 5411236d6b63bc4bd54f36ff39cc6f7912a44507.nq.gz
│   ├── 6063f72f417271a6cba967b4e767ccd955d209b3.nq.gz
│   ├── 6acb4c96b4b815594daf4caf8492b5b4f8ed3158.nq.gz
│   ├── 6ba504ef999b8449256e921e3001575764698337.nq.gz
│   ├── 75e33dedcdb32c52bbdba403fef56d5c2670fb2c.nq.gz
│   ├── 7b2852eb0d7808c4b13be3652086f8e36cd6b720.nq.gz
│   ├── 7bbbdf45bed96dd74d8c9566653b60262bd9277d.nq.gz
│   ├── 7c48b265a6f18cd15b34396603aa03b05a53dc64.nq.gz
│   ├── 7fe93248f925244e9bf2159c8dd0f827a47f3539.nq.gz
│   ├── 8c7729a98c384783a54d8bfc1322099d7bc6fa1a.nq.gz
│   ├── 8d771e187ba4b2ced1b643c804548e5c014bab70.nq.gz
│   ├── 924d97150f603c5c30ffaee3c50038f5aeaff64e.nq.gz
│   ├── 95e554bb9fed2318387c74fe175a4f799c35e295.nq.gz
│   ├── 9ca56a8830a92c94a3be6a6aeb3dfe77d9cd869b.nq.gz
│   ├── 9f2d2317d4c7a266b271d7b97775a133a896f9d7.nq.gz
│   ├── a7019cb8b7101c74d54aeedb6262099f954dd211.nq.gz
│   ├── a81c4625c094f11963e67c498ab3809ecb84c1f2.nq.gz
│   ├── b304313c814ed08faa5d753227161ed0a6e5669a.nq.gz
│   ├── b9edb5c264761db66bb04f8a5ae71ed52c3c6afb.nq.gz
│   ├── bbe77cb69558e274639017d0079c3ebd6bc948a5.nq.gz
│   ├── bd418d4c38a2ac7224a9d96b73029764359b499a.nq.gz
│   ├── ce526c5e2858a8006b72e3d985d4f8a33ce80ed3.nq.gz
│   ├── d01d3ec218c3341b0efcc04120cea0290c5f3ca3.nq.gz
│   ├── d54e174965cd46628cb383227260a3687f776d53.nq.gz
│   ├── da0a7b733a04462ff782c62333b3ab8de87c2a9f.nq.gz
│   ├── e06a7b4b2efbc25bac99a8a022c1f583198a9c68.nq.gz
│   ├── e5b983f7d14e698308810e5515bffcc0c8d4e636.nq.gz
│   ├── ed67d9f62e5efc1621f0c0e8ae8ee293fdde7856.nq.gz
│   ├── f0571dc2b05049fc3780efcdffbafae38febe7a8.nq.gz
│   └── f87b5261528025f1e53689d5d79c8a1e085ad1ee.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── fc84499edee777d4e9581f229600ba3f59bbcfc1.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 51 files
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

[canonical/sdcore-pcf-operator](https://github.com/canonical/sdcore-pcf-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
