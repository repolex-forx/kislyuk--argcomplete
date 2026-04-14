# Repolex Knowledge Graph of kislyuk/argcomplete

RDF knowledge graph data for [kislyuk/argcomplete](https://github.com/kislyuk/argcomplete), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download kislyuk/argcomplete
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fae5549ac1e89ec05de7d11ff33f540c74fc3b18
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── fae5549ac1e89ec05de7d11ff33f540c74fc3b18.nq.gz
│   └── repolex
│       └── fae5549ac1e89ec05de7d11ff33f540c74fc3b18
│           └── chunk-001.nq.gz
├── blob
│   ├── 03726529fc60bf56f7c825e77c4c956bad4ef959.nq.gz
│   ├── 077b1850d2c46d58e489b0e36321ba652e0bfe2a.nq.gz
│   ├── 08fc179a71a33d11a00a15bc09996785bc4e70d5.nq.gz
│   ├── 0a69e01709726710511c560e30bd4a8f8f782041.nq.gz
│   ├── 0d0bb1b2a0bd8a0ca449152511e6a1739f0fffed.nq.gz
│   ├── 0d5a68298e2c414efef21792b5a3d3e9928e99cb.nq.gz
│   ├── 0eb744c9e96ddc7981cca107650145bccaee2101.nq.gz
│   ├── 0f13a0709aa71dd544b4e74f787467af359a96e1.nq.gz
│   ├── 1155f1ce5e8f00893b64366e5ccefb3c718e5693.nq.gz
│   ├── 1e680298258d91e34929e28b67db513b1370808a.nq.gz
│   ├── 26f8d0eca3de357c9134da8fde01f641014335e2.nq.gz
│   ├── 29e2444542cacf2fa0b19d4b3d318cc5b7c7fd08.nq.gz
│   ├── 2e913579905625fc55c3f588a0543b0c099dce23.nq.gz
│   ├── 313af3f07d3e9ab1ed506eece4270608c7b89eba.nq.gz
│   ├── 3c0c58990890d2313e26142d03114bf354b7e228.nq.gz
│   ├── 4bdd1ec8d7c3949c77fcef5688e4b2aa20b0fe65.nq.gz
│   ├── 4c01e6951893920252f7eec1c61cbcae66bda6f9.nq.gz
│   ├── 4dd824f51846673a0271c1f4b80ce35dc2cdd15b.nq.gz
│   ├── 55f094e5ad6ef8b8358dc024a86f2db21b02a5be.nq.gz
│   ├── 5d02c16ea1f788cdf936e6b3dcba5104cf424a2f.nq.gz
│   ├── 5d7670d39c9946a21864e4ca9e8b6480441667e6.nq.gz
│   ├── 614f50a7b0b020bf225d2e94cd2115a74e4e2912.nq.gz
│   ├── 6d2287575a8bc93e85c7536021404b6951f7f685.nq.gz
│   ├── 6fffb6a2db66f49252c2644e3edabeedb03c2cce.nq.gz
│   ├── 72c378b54d72f30bdb6bdf491a328d386585410a.nq.gz
│   ├── 890a38f43f96177ecb51fc84266a8e5dfce0068d.nq.gz
│   ├── 90d9e3394528b5a73c6fcfa17f0fdabdd56a7236.nq.gz
│   ├── 91ab246863f5edd73780af4838cb6a4d7b762396.nq.gz
│   ├── 98c59d3fedaf12f74b8c54e92a853ec47294d497.nq.gz
│   ├── 9bd90f1f5636964d3d89410b4f3482c28902a4f8.nq.gz
│   ├── a46d81e1e82ffbbaf53dd12901b84c1eea50cd88.nq.gz
│   ├── ab31a5b1beb9aae6f613457be2ebd7cd2d158e8d.nq.gz
│   ├── ab8bb1d90a235e971ccd9662b0332f65c3da7637.nq.gz
│   ├── ad5eee86c81e332523d7ed9827ee21c44b30cb51.nq.gz
│   ├── bce5b7978d135733db8506aa57e7ede3a2923900.nq.gz
│   ├── c1309626de48c6637340475fb08bbcf1cab66ea1.nq.gz
│   ├── c59730795121c2a204374f406d0bfad503204b45.nq.gz
│   ├── c9150bcce4811009544429a53eed6defb4ed86a6.nq.gz
│   ├── dc72640e933c05c86e52f0111511695d6bb98df6.nq.gz
│   ├── dcd26e8627f605abf82781d8eecb31bd1d5159b7.nq.gz
│   ├── df2c4f20326ef67d6380222831f5adc9324fa497.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f01c80919dcc8fb15cf29b38b28e50089b7ba830.nq.gz
│   ├── f433b1a53f5b830a205fd2df78e2b34974656c7b.nq.gz
│   └── f6ecb1f4172512a19d10c7765e49fbaac4928a78.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── fae5549ac1e89ec05de7d11ff33f540c74fc3b18.nq.gz
├── filetree
│   └── fae5549ac1e89ec05de7d11ff33f540c74fc3b18.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 55 files
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

## Source repository

[kislyuk/argcomplete](https://github.com/kislyuk/argcomplete)

---
*Parsed on 2026-04-14 by [repolex](https://repolex.ai)*
