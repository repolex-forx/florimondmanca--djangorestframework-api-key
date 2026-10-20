# Repolex Knowledge Graph of florimondmanca/djangorestframework-api-key

RDF knowledge graph data for [florimondmanca/djangorestframework-api-key](https://github.com/florimondmanca/djangorestframework-api-key), parsed by [repolex](https://repolex.ai).

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
rlex download florimondmanca/djangorestframework-api-key
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 02f68e85d2e51f8a2049cb15ee4d5466d38cf1db
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 02f68e85d2e51f8a2049cb15ee4d5466d38cf1db
│           └── chunk-001.nq.gz
├── blob
│   ├── 028d4b313b20b701f65cbfda8b2fa0c4e105c564.nq.gz
│   ├── 034ea6daefe21598b7915079d69155d53de15b64.nq.gz
│   ├── 066b2d920a28db73b4ba3a0b35e6905eeeef5772.nq.gz
│   ├── 08cad7c4082b35472d3185a1b22672fa45ef73a6.nq.gz
│   ├── 0b3af9ab6a59e01892a297a754cc5cc5c3b8d994.nq.gz
│   ├── 11f2be11768ea983b19d15fbeb002108ea80fb85.nq.gz
│   ├── 1224c47be10e033ec32e02ca34f31b7f1007df3d.nq.gz
│   ├── 125c0947ff1aea711aaf4f6f0313db3e87f9f6b7.nq.gz
│   ├── 1300f6f1bc518a80502c3bb1d94eb91f5eccc39c.nq.gz
│   ├── 14d73188c8a15e0dee87e95d98f2b55af81caa2b.nq.gz
│   ├── 19585c678ac4d45377aeb3ddcc7cd00b828decda.nq.gz
│   ├── 1a36b15a43498fa5c1a133b04cd0c053bf68df6f.nq.gz
│   ├── 2706822cd02b3ce8e619ff049408f32eaecaddab.nq.gz
│   ├── 28a25faf06f64cd2062d346acd73a2bb11830ef6.nq.gz
│   ├── 2cf3dceb00daabb96d16473f45c36d525b3633d3.nq.gz
│   ├── 317c518bfc040ebb0e83b22c1ff616880b86ed3d.nq.gz
│   ├── 32bc99e79b9f20c265ba69aac815adfd1d7d0004.nq.gz
│   ├── 3310bb5cd9c527251cca6aa1ebbc1e87c552457f.nq.gz
│   ├── 3da72132e59adb2ff6b768c2bd0e10e34094b398.nq.gz
│   ├── 4043cfdcd5e9bdc2e6f42be89f002f6eb2a6b8ab.nq.gz
│   ├── 405f33e98e0e5cfd13d7acd8a88dd467687779a5.nq.gz
│   ├── 4a994360d5ae96e11e7d1c97a3e7153c3b5528e1.nq.gz
│   ├── 4aca123d250b40abb93a36194c504ac916b371ca.nq.gz
│   ├── 4b259de09defc3cb6f160a93361f89fdc37f0508.nq.gz
│   ├── 51748c1d1cf2b42f6c9c1e7aa6c581d5c0a4b86e.nq.gz
│   ├── 51a95dbf78efbbfe2d7b5d34be1b6e99e4421d80.nq.gz
│   ├── 5580482f3fefe5620609489b3e1682dddde5cdbc.nq.gz
│   ├── 6289b098e0f5fd440c90bdec2f0e2f5ae7b32be7.nq.gz
│   ├── 6ebd53d079763b57e78ce56f063947e2e3ce7b2b.nq.gz
│   ├── 7275031f7fd6c7a4d09f3e9f2e1c92f5b659c098.nq.gz
│   ├── 73cf95d93e1ba9b8843123c0d560ae75c300ff22.nq.gz
│   ├── 756d50f744d4edcaa5a1891c878ceabd7b47b006.nq.gz
│   ├── 7ac6adfa9fc85046c701384b736ea7da25693777.nq.gz
│   ├── 7e142d50620bc065b18e1ebfd5d882210290620b.nq.gz
│   ├── 86ffe8dbf2a59c8234354153a5b884ac8dc8e392.nq.gz
│   ├── 8c95653670b011433252a33fe09fd13182c8af77.nq.gz
│   ├── 8d8d6afabc4201610a1b30275328ae9076203c47.nq.gz
│   ├── 8de175e0f42bfbfe259571402b8807126a59c58a.nq.gz
│   ├── 8fea5a8689a931ea9e107bbd34da4380b9c6fbbd.nq.gz
│   ├── 94940042d38dde5173a4dd0edbe58f92b507cabd.nq.gz
│   ├── 954fb6a892145ae8cc4e96a86f5f93ab28d4a3d3.nq.gz
│   ├── 967e1463d524069020027bd277af7affbc9c2ab9.nq.gz
│   ├── 978077dfa50d22a0085ed2e8fa0e7cadcf7c0930.nq.gz
│   ├── 9a1f529fc7d8b6fd3308150702718b3e167f7696.nq.gz
│   ├── 9cf573286e1559359554c0d37b86556e5aaa7b7a.nq.gz
│   ├── a20a5bfb36cd79ac511fc60f1f69f4caf73b1f3e.nq.gz
│   ├── a2ebb0b6bde24ea20fb0e7d5e5fdc018e35f33af.nq.gz
│   ├── a368b459c889d31e653ef1e846cda764dd250542.nq.gz
│   ├── a49951f3e0c8d70b669db9975e9ea580d2978dcd.nq.gz
│   ├── a5a6c50ab1967ac65ce91975e9e10630f5c9e27d.nq.gz
│   ├── a8baa9c881a3bb3b8d0e07de24cfbe14459aea89.nq.gz
│   ├── b713cb0d210a7245b2f7f6c976b976e41c1e351e.nq.gz
│   ├── b8b71d8cba48c86813cfa5598fdd920778b413c0.nq.gz
│   ├── c2a2534507a0efcb84e34fa8256974f1ac7f09c7.nq.gz
│   ├── ce22b446f8bc937ad8769f899c49ca11373132af.nq.gz
│   ├── d254f242b28e00250a0039004ddfbdeeddac66d9.nq.gz
│   ├── dc400385d87cdaf7b5662d22b7d886bf357606d6.nq.gz
│   ├── dc49aab4399c97a6f9721311172eaa0d4998062f.nq.gz
│   ├── e2c642ccb165c5e9794e96ba7c4ecbd4c16a0c84.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9e3cf7640bd3f9493f6c02667be9a49801cddef.nq.gz
│   ├── ed93bb72af9d118c4b341e30072e22cd5238d8ef.nq.gz
│   ├── f4327bce2930f0dd9943aa87325d12df9a8ff2b1.nq.gz
│   ├── f82b65835db3a6de95971ae87db86ea8c49945cc.nq.gz
│   └── fe0b9bb4e10548563283570ab8d412c2e0335c19.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 02f68e85d2e51f8a2049cb15ee4d5466d38cf1db.nq.gz
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

[florimondmanca/djangorestframework-api-key](https://github.com/florimondmanca/djangorestframework-api-key)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
