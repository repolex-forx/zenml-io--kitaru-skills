# Repolex Knowledge Graph of zenml-io/kitaru-skills

RDF knowledge graph data for [zenml-io/kitaru-skills](https://github.com/zenml-io/kitaru-skills), parsed by [repolex](https://repolex.ai).

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
rlex download zenml-io/kitaru-skills
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 777cd41ed792bb722f21d041b1f220e5e5714284
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 777cd41ed792bb722f21d041b1f220e5e5714284
│           └── chunk-001.nq.gz
├── blob
│   ├── 0118b3128c9488641da5a270f883b6d1be1ba98f.nq.gz
│   ├── 02e6188389c9d7c6149c7da2949c1ee6273d0a98.nq.gz
│   ├── 044869ec4f0eeb3627281ec3b2e29f0876da5efb.nq.gz
│   ├── 049e81a3dcedb93e52816af00ef6dd7bc04a3ece.nq.gz
│   ├── 15845bfac12c088f51fba39682dc6c95696d9a4b.nq.gz
│   ├── 163bb1e17b30f4f6f70118e4f9698784f291bee3.nq.gz
│   ├── 16c02fe85c9ac05be8d9e547f562320031d96980.nq.gz
│   ├── 1a2758db3fc4f9143071c295020afc741e901c01.nq.gz
│   ├── 1b699947e6986ac8b664b66c478cfc6c6bcf09ae.nq.gz
│   ├── 23ac458e1800e7b4215328a33a11abb595e46ae6.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 28fc622933113826c4bde850efde4bdb810dfa1b.nq.gz
│   ├── 2b73f8ebf5633c1874e32d66ccbc9048697c1aab.nq.gz
│   ├── 303d6a2880a657961a0eced0c2be47333829e7a3.nq.gz
│   ├── 31610f1390b227c494ba434d3f398ad9652b99e9.nq.gz
│   ├── 325aa908f563423926285d3a539fea3eb72e0990.nq.gz
│   ├── 3e981104625f38e1e9db38b72513b2ebea4c2348.nq.gz
│   ├── 40db1bfb7759df9dd73ba211753bee2a8167aaa3.nq.gz
│   ├── 41eb2fd90b72340986bc9ca85fee85117bb3af2b.nq.gz
│   ├── 4459cee8fdd67315a2800e64c564d4ac62c5bccd.nq.gz
│   ├── 45514a1a237c6d219f63201dc6343d9e0a7dae3d.nq.gz
│   ├── 4c5d35ebe591a814bec1eb9ee9a5bef02ef8790b.nq.gz
│   ├── 4fb12d108a05df596a5233e5dbcfd161e73ff654.nq.gz
│   ├── 5360de38171f2570161a55cb243544251ca68b1a.nq.gz
│   ├── 5533343e2f7b947a146f86bafb7c2b2d92e5e0af.nq.gz
│   ├── 583f4df4959a61b4a19e29eff6ef68d2f3c57134.nq.gz
│   ├── 5ec4d1f24632a0cd9d1d61a78bae45e363424cff.nq.gz
│   ├── 65fdb5dc23b22324cdcdc636e5008bf3eba7e813.nq.gz
│   ├── 67b02acbe6834d5a08a4c65f10f2f22c05a3d768.nq.gz
│   ├── 67c488b97d8330c176678a403c08c50aa1709b9e.nq.gz
│   ├── 700fff1e2b88a8d4e6428aced29e91669a6054cd.nq.gz
│   ├── 75a0f33647e9124d255346e379e5894fe308f9da.nq.gz
│   ├── 767b76ba24c3bcbe0b3fe012067d6b88fe1e538c.nq.gz
│   ├── 78b732c5dbbbd84a4537a620e896776901fbe67a.nq.gz
│   ├── 7cc67aa63339ca6e149ef1ec72da4b6573981d4c.nq.gz
│   ├── 89d2024e4d14d85dcb23b2c82b0fb37c9c1cea42.nq.gz
│   ├── 8a6d128aad0eee04137682e0e761bb8baa0fdb53.nq.gz
│   ├── 8b61a08517332ffd584e4086a3a2c2b77b347b5b.nq.gz
│   ├── 8f1e7e9c4dfef756b8df8176eec78865c40d76c4.nq.gz
│   ├── 981880baa3b1e31f53f554312a309b2fbe17954c.nq.gz
│   ├── a2604375a084668829e784e191c812724d5cdf27.nq.gz
│   ├── a95b665d3ff006119a0a4bc951b9b01c9b644d8e.nq.gz
│   ├── ab6b7fdf00b994dbf4a3e8aa13042cd8df1bda29.nq.gz
│   ├── aba81e0ed333af5bc6dbe223f65782ee9b7d95ac.nq.gz
│   ├── b413d000613423510a956361d9673ac0e4a18eda.nq.gz
│   ├── b7bb2c557ad2d5b98e14ed7a7023765ef88945b9.nq.gz
│   ├── b84c0294cf8e3f7dd73bc20e4240755faa0ef6ef.nq.gz
│   ├── bdb2d6ca856664aa5f9e5021378337859c342982.nq.gz
│   ├── d04e7fa1502170e69efe44645ce73fb3a05cc5d2.nq.gz
│   ├── d4207dc64b8b6b7cd225defc5160dcf4c2fc19d1.nq.gz
│   ├── d75d90fcc01125e65c2451462432f2d2a929c041.nq.gz
│   ├── d93c171780107eab6b36ff785c07813fb75febb7.nq.gz
│   ├── d95c22fd81b7d21acb636817bc3191f7f42f4cfc.nq.gz
│   ├── e7e8e40987dfc551461d623f675ba4b8b495e6b5.nq.gz
│   ├── e994671c7719329d47a7792f97086c10a459453a.nq.gz
│   └── ea0e4f2526b289a7657a814659cb2053f0b82b8b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 777cd41ed792bb722f21d041b1f220e5e5714284.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 64 files
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

[zenml-io/kitaru-skills](https://github.com/zenml-io/kitaru-skills)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
