# Repolex Knowledge Graph of dryrust/getenv.rs

RDF knowledge graph data for [dryrust/getenv.rs](https://github.com/dryrust/getenv.rs), parsed by [repolex](https://repolex.ai).

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
rlex download dryrust/getenv.rs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6fafcf5587045ec427a804d3ea3da9b63e0605dd
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 6fafcf5587045ec427a804d3ea3da9b63e0605dd.nq.gz
│   └── repolex
│       └── 6fafcf5587045ec427a804d3ea3da9b63e0605dd
│           └── chunk-001.nq.gz
├── blob
│   ├── 028bbac137a5b7a7d085038b2840f422689a7b0a.nq.gz
│   ├── 0a0d94ff6a55f55b8ab2cdf2574335bf64ff65d9.nq.gz
│   ├── 13edb27f8341a15f7ef6805243c5be8572913129.nq.gz
│   ├── 1757eda67b2a16dcff8be17771a88e45b88517d3.nq.gz
│   ├── 1e5039088e0ce7a8e388b72c0321f5da3508504e.nq.gz
│   ├── 2601b3f4151f2ad62821425751ff1867283aa420.nq.gz
│   ├── 271649cf062bfb396d429c714d1c73eff4b0e5d6.nq.gz
│   ├── 280fb8d04170d32ee9c5f1537fb204382a2602ff.nq.gz
│   ├── 317f94f9af0838a09282c3eb66ad6cf8930970f8.nq.gz
│   ├── 42471e544ab405ee70d1ff837e4ee4450d0ae279.nq.gz
│   ├── 44ec79e8097231dbc0254997f4959be5d74e9616.nq.gz
│   ├── 512e2714a5dce41d1c32578126897950d935b818.nq.gz
│   ├── 5d1ef3e61603210e943822998420e4de34c78c1a.nq.gz
│   ├── 692f46ae8baa26bc5f75f9dc6f4c00be86a43e04.nq.gz
│   ├── 748dca9b8b92137aa3d25c5c33ee3643c0fa37e7.nq.gz
│   ├── 7504cf9bf0fb83a7142ad4726ce7638c61481850.nq.gz
│   ├── 75e3b65f99b29f48ab230e3eab3de8d0b7a9229f.nq.gz
│   ├── 78af8f9f390bbb2dd137fd6caceb4c796d68c5dd.nq.gz
│   ├── 7b88d3b075b0f415d39f409c1380551f700b9e04.nq.gz
│   ├── 7ba52f7e317f1587e68750dcfeadbe2bb36749ac.nq.gz
│   ├── 93cfc10fd9e8e96499fec5139a4398e58ced4eef.nq.gz
│   ├── 9581517e4d4f6bb6981acf25edaf34bf7c13cbaf.nq.gz
│   ├── 9b997633645609e1eef6a62b4dba408f81b304c2.nq.gz
│   ├── 9d94b68943006be10c68735f74402d7158de4edc.nq.gz
│   ├── a02381332e1befde08ba6f5916db68bbf7713f16.nq.gz
│   ├── a45a6c8eb043ac4fd2e45a861b7303a3ef075f1e.nq.gz
│   ├── a60dc44c0895b2fab4c96aeb9497f5988a940921.nq.gz
│   ├── a70fbf254c9d355a7551fa38ba07e81e1f0ce5dc.nq.gz
│   ├── c7504b17b600cacd0a72d17b05bb8dae214c4791.nq.gz
│   ├── cd01ffdcc037849c4bdd2fa20aa374afa49b228c.nq.gz
│   ├── d1f49c4d251713faf680a5224223d80c057bb3b3.nq.gz
│   ├── d2d774d685a805fac62723c16262a6ba9ded7549.nq.gz
│   ├── d2f443a8856f8802d887d04feef6034583d367d1.nq.gz
│   ├── d5f14314490835d538b4861237fc67b4e5c3cdc6.nq.gz
│   ├── d917d3e26adc9854b4569871e20111c38de2606f.nq.gz
│   ├── dc159d8eea284343e27a2104d04e80a5fc6a9444.nq.gz
│   ├── df89fa499a018e108fd2f33ea6ab8e005fce89fa.nq.gz
│   ├── e062577bf70456173ea93ad2947a8f7a80d93a46.nq.gz
│   ├── e3e57a8ce4ccbf74759a6df8fa4a3980ff1c9209.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7ef8e610ac75a7875a2c50555ebced5dcfd0917.nq.gz
│   ├── e94d007030c7f349ab7a49bf213a046e494b7efe.nq.gz
│   ├── efb98088164f5786b17e83ed384971fc3c74f93c.nq.gz
│   └── f5a69c3fc86861c10a7799be36fba6a4c946533f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 6fafcf5587045ec427a804d3ea3da9b63e0605dd.nq.gz
├── filetree
│   └── 6fafcf5587045ec427a804d3ea3da9b63e0605dd.nq.gz
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

[dryrust/getenv.rs](https://github.com/dryrust/getenv.rs)

---
*Parsed on 2026-11-21 by [repolex](https://repolex.ai)*
