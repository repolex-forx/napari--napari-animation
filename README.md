# Repolex Knowledge Graph of napari/napari-animation

RDF knowledge graph data for [napari/napari-animation](https://github.com/napari/napari-animation), parsed by [repolex](https://repolex.ai).

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
rlex download napari/napari-animation
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1404817ac56301697a07e3d68e948e7c74d73ff2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1404817ac56301697a07e3d68e948e7c74d73ff2
│           └── chunk-001.nq.gz
├── blob
│   ├── 00aefa479644b2d2748f679b3c4358f051538e60.nq.gz
│   ├── 013328378ef14f0fc574bd0b2b4bbf45248bddbb.nq.gz
│   ├── 0529d53f2fd42fb75b49bb33cadca2e4dee35707.nq.gz
│   ├── 0aa8a3b7ec8daf4444ccb616670ae8358d127e54.nq.gz
│   ├── 129088056382f0d4d79f3cc002bd9422308283f1.nq.gz
│   ├── 1b7059531ef827792b44f316dac264f8e12752c9.nq.gz
│   ├── 248c11fdd00f5c63cca40477bd627ed71175339f.nq.gz
│   ├── 25248afb99e22bd3d941f4e49da8b6e74c3ca2bc.nq.gz
│   ├── 2689394e81e4689a674ce09e06c5b20027122124.nq.gz
│   ├── 2778f9f624ebb98efe2807209047d55be8b307c0.nq.gz
│   ├── 2e1b9f7f8fde8de5ec32fe37ff93b870cef95873.nq.gz
│   ├── 3053193f9c9f7d1da9800b843d9f780e2006b371.nq.gz
│   ├── 31f4f5cc91483ab1a95918bf4e372304fa912655.nq.gz
│   ├── 35a31089c33789d68fab3fdbf592519463231056.nq.gz
│   ├── 3656106ac3ebc1ae28babbb167b2c127624cf63b.nq.gz
│   ├── 40d271165176516c92bc48cc58f3e5f84a155d1c.nq.gz
│   ├── 4437200f59e6e270658eb0cd45c112f5477126ed.nq.gz
│   ├── 451bedaec21ea36474276ced4ad7260227f5b227.nq.gz
│   ├── 47ee70bedbb7b32d523afb4cfe22afca3b5ab918.nq.gz
│   ├── 49b37e837e7ec9d68133bb30f973da461e53ee8a.nq.gz
│   ├── 5208e6dff0d4ed7e8e0b739933b1be37884d2b55.nq.gz
│   ├── 52c6d359ff0df8feebd0c660c40dd16356145b5c.nq.gz
│   ├── 64f7ec5958f00ae4a12a3851e5f53fc5c38dc342.nq.gz
│   ├── 65bb14cd8c246bfb15c0d975c48a2229c38126d4.nq.gz
│   ├── 67b10dc25695ba8dedac04426f8b235bbe4e71c9.nq.gz
│   ├── 6a02e4e543118a0b1e95681c284563e097ff085b.nq.gz
│   ├── 6ca02202b753f86ad407f68989074b4700282544.nq.gz
│   ├── 6fa3042f467c453236ad2f6453a7edd58811f978.nq.gz
│   ├── 7008e1d4edef11786344d8658d23a908b30dfdb0.nq.gz
│   ├── 7120e739eb1f492efe39d637176bb8ef362398ee.nq.gz
│   ├── 736ee20849af2f250d266a209ae48d3b9728e510.nq.gz
│   ├── 7b18210f064b84f7f863d4caf8ca0a73923a30b2.nq.gz
│   ├── 803c1438c77780735baa0b2719cac063f91296da.nq.gz
│   ├── 866cccedce54801313484f2ddd5f41234fcb7307.nq.gz
│   ├── 88b21dd18b189a55be207090c9013f0ee07fe0a1.nq.gz
│   ├── 8b6a98ec3fe5439430f299f0fb6ddec079a173c5.nq.gz
│   ├── 8f5180674e308a611bf2f298cca474eb6bc9772a.nq.gz
│   ├── 91f2c60f11b59692de047e1e07634fb6e710b5d2.nq.gz
│   ├── 93cf4e9dfa21a8ad5da6ac012ceeecfc14e56413.nq.gz
│   ├── 9558cd50f83431b3a13a8a70bf536ecf6452d40f.nq.gz
│   ├── 9bf1f1f5897426b53b32a6b04f7f3cf2f8a9c689.nq.gz
│   ├── 9d68e45ec0d92089e9bd619c3b05d3575733a3e4.nq.gz
│   ├── 9e3356b9173766687e9c2861c623d2a7100bbfb9.nq.gz
│   ├── b25e158603516d2cefe4b271b2bc688e4f527c6c.nq.gz
│   ├── b796659d7184fc4fc6113d8b89e02c3bc86bd4d4.nq.gz
│   ├── baf1bd9dab24e54cad67043f14ec1ca53fb1d7ee.nq.gz
│   ├── bc2e14acbe339284a223087bbd400c2adad5b64e.nq.gz
│   ├── c4c082f626ad10b699ce6d362dccfa35d0a1dad7.nq.gz
│   ├── c75dcb014b2c54b84a557e18f140c4eb6a688de8.nq.gz
│   ├── ccbe2950438c09790182acfb8b7983715f2c520e.nq.gz
│   ├── cfd3ea72253f893224d223fed500b009b037ad9f.nq.gz
│   ├── d01a02c2b066633494625fbd85d70252bce08184.nq.gz
│   ├── d0227bcebb89cafb4d820aec76c0b4a201176fb2.nq.gz
│   ├── d7c807a886d48729e6b0f2e91961c46babc78574.nq.gz
│   ├── df38c31ef554873e5f8a69e705986651df9957fb.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eb7536acd7f72d0a15737582cadd54ad99ff37b5.nq.gz
│   ├── f3155af7064c0db0b5b9b8e2aa0d4b2f02f092ce.nq.gz
│   ├── f3462615ae7e56b355f8d1b3642c7b8ad910947f.nq.gz
│   ├── f51f7a79e984efa2963577e113d42a4943d3d71e.nq.gz
│   ├── f6667139ab27fde82345a81ca98e4646b16cea5a.nq.gz
│   ├── f9fdf112a9c955f1267ae4fc60956645bb15a489.nq.gz
│   ├── fc987cf052a34539416b107825b87c79fe6831be.nq.gz
│   ├── fca364fc2b0b4c3dcb4b8959cbf074241844fcdd.nq.gz
│   └── feffcb4cc084c3fa64b58a94d91039e01ec36eed.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1404817ac56301697a07e3d68e948e7c74d73ff2.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 73 files
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

[napari/napari-animation](https://github.com/napari/napari-animation)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
