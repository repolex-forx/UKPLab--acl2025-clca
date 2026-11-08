# Repolex Knowledge Graph of UKPLab/acl2025-clca

RDF knowledge graph data for [UKPLab/acl2025-clca](https://github.com/UKPLab/acl2025-clca), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/acl2025-clca
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f77a266b03229cae5692da6052137dd92b0516a9
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f77a266b03229cae5692da6052137dd92b0516a9
│           └── chunk-001.nq.gz
├── blob
│   ├── 023ca00f1cd14205a7f1bed09b8643cc837b43ca.nq.gz
│   ├── 04fc5cb874221b29dff9cf7f4747efcf0ed3a1b0.nq.gz
│   ├── 0a34fd9fe505904cb4272678764bc8bded8b7d04.nq.gz
│   ├── 0cd12a45a94d6f4c38bceed076b6fcdd018bc715.nq.gz
│   ├── 0d03bf268c448d14aeb9becbc045bcde4ae6c9b7.nq.gz
│   ├── 1e91f19ebf4d45b6413b1fb36987228ca80d0c57.nq.gz
│   ├── 22994d26c18c3c411d9b13aa54fc4d89482d268a.nq.gz
│   ├── 229edba242bb190698662cdce6bdacde9f0769fe.nq.gz
│   ├── 22c858edc7f0ec2a9274ed8c8b39c4c35b4ae1ef.nq.gz
│   ├── 273cdeb2282c34bd4689e27e64b3c743b72fd3d1.nq.gz
│   ├── 2e474efcdee525aac6b0ac078056a5bfd4052295.nq.gz
│   ├── 3dc429a6613bf85898a47643fe31d4439fe9d973.nq.gz
│   ├── 460dbac4007496960e961dad9211c485e3f68db3.nq.gz
│   ├── 527d143425f783c2cf454cd4cf6fe15892898e38.nq.gz
│   ├── 559532080adc01d6ab80fd5e58a66cf52f3be9d0.nq.gz
│   ├── 585ee96a5bf63fd97e912801fc94247ee9f5e719.nq.gz
│   ├── 6170a23d829c16610d1c3301279158a4a0193b67.nq.gz
│   ├── 68eb69b23434984ce6053d307b6b6b7f709a7e7e.nq.gz
│   ├── 698e9f972a96948e15606d89ceda254e571d2692.nq.gz
│   ├── 6a0ca2d59dfca054cfca0d72a833a77f596a6495.nq.gz
│   ├── 702d5e92c2c2bf68b6d928c49e226cb9ecd1a132.nq.gz
│   ├── 80f9dedb22582266a9daa4b5a74a2b7ef60f99a4.nq.gz
│   ├── 83105fe22bcb0b8467d31ec2c22911e40af5186f.nq.gz
│   ├── 846349bde7d6468cff0d1f8343f752b216dbb670.nq.gz
│   ├── 8b4fa0773a8f940bc054ae8dd550c65c3447cd48.nq.gz
│   ├── 94a0ec8b1b1e4226fa0f4bd9e853902fff7f6769.nq.gz
│   ├── 9b3703a912d40f58fb0fb57d20742e53d9fe7671.nq.gz
│   ├── b30139b264d7c43dca9be86565f8813cfa7891e3.nq.gz
│   ├── b69f3e4419d3728cd205ab28942c7ba98baa3535.nq.gz
│   ├── c08a79032592be8f5e7318991b0242323389469d.nq.gz
│   ├── c23b452a08e45fb61421242ff6b41fb35cf0d530.nq.gz
│   ├── c30d89d26d1dbfd56a12186707f14508ff162996.nq.gz
│   ├── c4692100a7c2e362f045fae33504c07d525b8411.nq.gz
│   ├── c6718de5c5ae59d2c22141a147f5afba41af9cbb.nq.gz
│   ├── c9775f0aaf8020226c3d482733f14c1a6d6fe403.nq.gz
│   ├── d508cfd442a0e57ce2336cf998d6bea033cdddd3.nq.gz
│   ├── d62fc66df4b9acdd5381753fde4173a5775b1ddf.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7a27dd25dc8dd910c5fad29358e791897ea6132.nq.gz
│   ├── ed3a9d377ba3c30e6eb8b2a35e08e8dc814a0725.nq.gz
│   ├── f47c06cc18baa434989aa2d46756a0b678957242.nq.gz
│   ├── faa22638ee2810355444627b30ba7a2bdd3695bb.nq.gz
│   ├── fb749b6336a24c083b4ff6698c8d26f174322035.nq.gz
│   └── fc86fbed35a79bb140a5c368b35b1d89ad4c2570.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f77a266b03229cae5692da6052137dd92b0516a9.nq.gz
├── issue
│   └── issue.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 51 files
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

[UKPLab/acl2025-clca](https://github.com/UKPLab/acl2025-clca)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
