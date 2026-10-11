# Repolex Knowledge Graph of aio-libs/sockjs

RDF knowledge graph data for [aio-libs/sockjs](https://github.com/aio-libs/sockjs), parsed by [repolex](https://repolex.ai).

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
rlex download aio-libs/sockjs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── eeeb73568a28230b95ef4d17dcc83e234ef6d1eb
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── eeeb73568a28230b95ef4d17dcc83e234ef6d1eb
│           └── chunk-001.nq.gz
├── blob
│   ├── 060664c4b85f341e3b5cbd8f0925b9fc53da235a.nq.gz
│   ├── 0681ddacb49a78e2216f86dcc9fa1fc028214cca.nq.gz
│   ├── 09a535c930c0229dbff8e35b1780db94bd4d8a91.nq.gz
│   ├── 10541285ed40d000d4c0fa8c62b1ef4609e99ccc.nq.gz
│   ├── 1109d984377dfa45996f5168c118af88165e9c3e.nq.gz
│   ├── 126ef44563a2b37d040c8ef91fd4ac7fe8c8d31e.nq.gz
│   ├── 164383eaf547d946c6137e06ae27944aa0e40457.nq.gz
│   ├── 1c9c75f92cae048d7f61def78e1a4e0c411efc9c.nq.gz
│   ├── 24c3d820cadf0dada28d8e8777f8d6dbb523d8d9.nq.gz
│   ├── 2518beb01003a4807a1c8bb2f16e978019392dbb.nq.gz
│   ├── 271304321d476e60ffd852eafa49e36b6f51f262.nq.gz
│   ├── 2db017a9d4f79f8b9bc5171699b8fbf0c938ceeb.nq.gz
│   ├── 423ce63b58036929ab180ba33ad5353f97429e69.nq.gz
│   ├── 4517a1fcc373931627beaf3bb677239b2a0b0a13.nq.gz
│   ├── 4906f6687fba42fd70a5e46dc12af95dcd9d8d30.nq.gz
│   ├── 61c0868f97e761a6beb6de73bba66dab5d65f1eb.nq.gz
│   ├── 62e5f0b3252fb94178c65e321e0168f86b2da110.nq.gz
│   ├── 648d08b400690f42643c7d40984e7b888a56c6e8.nq.gz
│   ├── 67626106e6ca22f86c5904fb1bd66600dcc8d09f.nq.gz
│   ├── 6d2f88c17e2574ab5c12747f64def78f93813e74.nq.gz
│   ├── 6d7cefda5f8318fe1e8c8dddbfefa8299b45812a.nq.gz
│   ├── 6d8e77dc2fd8f7e07163681e76b0ab84fc587f08.nq.gz
│   ├── 6f9defcc45cc8ca8c163fe276d68c474dba3088b.nq.gz
│   ├── 75b967c0dd54d8d59b7057226c36eb3ec955d799.nq.gz
│   ├── 75f971166aa4063943ec9c92aed81e04aac28046.nq.gz
│   ├── 8a7d23b7a177a4407d918e3547468e75889d2a25.nq.gz
│   ├── 8d2bbb1d94fdc99f9728aac330e70aa1304186c3.nq.gz
│   ├── 91867d8e71732dd81526064a5da0193a7c62c97c.nq.gz
│   ├── 9d3f272447e5c16bc802cce13395171d9646de11.nq.gz
│   ├── a596b52a65f7283c905227ae37cfc82915aea03b.nq.gz
│   ├── b37cec96dfef4e0f5581285a2e8365e415e59a8c.nq.gz
│   ├── bb2a83e054a9e5a716fe32aebff3b1f119173712.nq.gz
│   ├── bfc32128574631ae1f1198763195c782f9eb321f.nq.gz
│   ├── c0d75bbd6a0e2a266d27c8d03aa2599c08e4aec8.nq.gz
│   ├── c569e45dba2b015395f6c50e57f9e6e3c6bc2937.nq.gz
│   ├── e05f194aa51a95226f3086b0a39c1f38b2ffdf5e.nq.gz
│   ├── e1bc544243fd8242ca360a6dfdb95d1b7e1613cb.nq.gz
│   ├── e7b4cf14981ecd365bca3812cf63c7e41f637ab3.nq.gz
│   ├── e98f0cabdeb8a061dfc1171ae3b2141a2dcbe327.nq.gz
│   ├── e9ccf0f7e3d42f952a32da3052b18cf358908c15.nq.gz
│   ├── f2fcd943cf09a181bb40ea669536c71c2f51aef1.nq.gz
│   └── fcbcab7ef7e5080eb446e9adc0a2efb4aff19c44.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── eeeb73568a28230b95ef4d17dcc83e234ef6d1eb.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 50 files
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

[aio-libs/sockjs](https://github.com/aio-libs/sockjs)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
