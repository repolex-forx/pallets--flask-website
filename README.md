# Repolex Knowledge Graph of pallets/flask-website

RDF knowledge graph data for [pallets/flask-website](https://github.com/pallets/flask-website), parsed by [repolex](https://repolex.ai).

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
rlex download pallets/flask-website
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8b083412f98842ee5e2b674cad40b8bf18501216
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8b083412f98842ee5e2b674cad40b8bf18501216
│           └── chunk-001.nq.gz
├── blob
│   ├── 11e95d63b811e1933b1f586d94c3ed42dca94b35.nq.gz
│   ├── 136f244193e663b52676ea518497a530e90fb571.nq.gz
│   ├── 17127cdac6c5bb80b18a9ac9cc681021d2dada39.nq.gz
│   ├── 1887100d316b86091a567aaefa61b21192f63b86.nq.gz
│   ├── 1b381e9e61d90a0b6ecb5778c3e525bcd0fdb654.nq.gz
│   ├── 27a8366877a9730b72bd5f59cc792807c0ce13b6.nq.gz
│   ├── 2ed2f92a3dbb686f1baedeb230241c331569dfd4.nq.gz
│   ├── 2fdfed0507d2a99bd4404f4f5c8e1d81a2064a7b.nq.gz
│   ├── 33f47449c11d241e36c83d7f95d819bbe56e2c8f.nq.gz
│   ├── 4040a981a3282f313f8f72842245f090e70f1c3b.nq.gz
│   ├── 41456b10e34393b024c77b536dc7d9d73593221f.nq.gz
│   ├── 49eca5d4f9db7850065ab0c10ef8936d5b03c7de.nq.gz
│   ├── 4eb3d795da28206c9e29130ca2a18cbccdad90bd.nq.gz
│   ├── 4f3c0b4d876b36c07c6a8b1bed1f04ce6334e442.nq.gz
│   ├── 56ad862b6fca910ca5b0e388b86a9d1d1f4080bc.nq.gz
│   ├── 5ae5ef6cd6decb41523f426147bc4fdce1e30d6d.nq.gz
│   ├── 5de4b47a2688739dac0ab04eca83bc1efea38a24.nq.gz
│   ├── 5deaf1b84eedf509fc1c0d853357b605880c8dfe.nq.gz
│   ├── 62c9d4c5b26db3e1205d2b2c9a3527c94f567d26.nq.gz
│   ├── 63f5d5e10f1572f1b164ce53b15302b46f230964.nq.gz
│   ├── 6436e5a059d5496e08aa20a373a6f4af6e5e86dc.nq.gz
│   ├── 653d7defcbb67d3925daf0888cfe695d113b3761.nq.gz
│   ├── 6eebe1e0a22314f4d4ac0a4a3507b3a4c8401a72.nq.gz
│   ├── 7302aed133d36734444e8051308553533da1ab4c.nq.gz
│   ├── 8431b0c6972371554334fe97c9db85645826995a.nq.gz
│   ├── 86920c131af8f2ac9c96b660f35be455a7600f8a.nq.gz
│   ├── 8b3e5c1634604545578d3b301a23f907450ba52f.nq.gz
│   ├── 8db724abc9d9a502b4d63bf63405904f502f9369.nq.gz
│   ├── 96aeb5832d01e73a325076cec2d5eb2abfb3c5cd.nq.gz
│   ├── 9d20f17cbc1fc174738611c3d96cc199427a50f7.nq.gz
│   ├── a8c5e79a26a1fb21a53e1ca236ecb1378628da18.nq.gz
│   ├── ac546db3b2cbfa14696c6e9c40535c2495a631e9.nq.gz
│   ├── b06a1de95eecfad674016e076c83e3ce0013763d.nq.gz
│   ├── b0a463fb0330f3f51073a10ae17ef1f1cf59baaf.nq.gz
│   ├── b37fa4a8cf7bda1a3e211729ee642bc2fcbf3411.nq.gz
│   ├── b57e66d21e5538a08824d51069ee95d2ed12d266.nq.gz
│   ├── b68a14974537d46415a90e2490a5674ec981fc21.nq.gz
│   ├── bd820c24728485ddc545e791da2a64d7794b6e6e.nq.gz
│   ├── bdffd361b49fd6a2eb45e60dacc83a4178369468.nq.gz
│   ├── bf92c02c0ea91c9a9bbd6e99a3771ae0fc5ef324.nq.gz
│   ├── c204b648fb3b2d25b7f251a34782a7a3636f918c.nq.gz
│   ├── d981733bb516a6cecaa2e1a06235940270f34688.nq.gz
│   ├── da5aa3bb4e85fcec93d03d2dd9b55007d8261689.nq.gz
│   ├── dc8159bd1c43d4181a12e54a5bea20a1c1bbc289.nq.gz
│   ├── de696c3f10b65fd355e6afb84eeff88b20089a8f.nq.gz
│   ├── deb5c81241f28cad115914309d6eac58ad63a0d2.nq.gz
│   ├── e0fb7112c2f1d64fb29de849336350f69e59ee70.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ed6d1f5049d890f54e6ce14be00b78ef3c5d41ee.nq.gz
│   ├── f2fdbe14b0aab5d03a366ed491910ec6f3ab0688.nq.gz
│   ├── f57b3fd31ba13665556ce1d156cc49f1dad37514.nq.gz
│   ├── f98ce466e407b10035f04aff906a34a5ffe8ef96.nq.gz
│   └── fcb93a2060e5d87475ba2d218ee23d7f83bd699a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 8b083412f98842ee5e2b674cad40b8bf18501216.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 61 files
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

[pallets/flask-website](https://github.com/pallets/flask-website)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
