# Repolex Knowledge Graph of deedy5/duckduckgo_search

RDF knowledge graph data for [deedy5/duckduckgo_search](https://github.com/deedy5/duckduckgo_search), parsed by [repolex](https://repolex.ai).

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
lexq download deedy5/duckduckgo_search
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1ebe10148c8089e888a36b25b5b557b9e94d8a3f
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 1ebe10148c8089e888a36b25b5b557b9e94d8a3f.nq.gz
│   └── repolex
│       └── 1ebe10148c8089e888a36b25b5b557b9e94d8a3f
│           └── chunk-001.nq.gz
├── blob
│   ├── 00c07ac908b091794d6a176ce8c8ddcdd71b301d.nq.gz
│   ├── 01dac1effcf079f3956160f657d57061db619215.nq.gz
│   ├── 060150d52e4acfe76141d5e30c54f6c4c754e721.nq.gz
│   ├── 0aac972ea29ada2fa7666515df9626804a8e3924.nq.gz
│   ├── 0d89c684f66e80a00551bb11eb451683a1691a3f.nq.gz
│   ├── 0e863c01c8dde896d96eb090d9abb9b1a64ecfd3.nq.gz
│   ├── 1099ceab090d8702be41bd7146d0f97d81fac0df.nq.gz
│   ├── 1242d43277017748bbbf3d0a104ec4cf78245822.nq.gz
│   ├── 1a2d888491ebeddb67ed0ef9a1d3eb0e64d694ce.nq.gz
│   ├── 1c8fcd1c3388fef771e25385479dd2fc22eacd8b.nq.gz
│   ├── 22b8e41a33c2bee02fe0816b0a3e2910f81be581.nq.gz
│   ├── 23f0a317d2fdec721f63334bf761f2553c6df219.nq.gz
│   ├── 2427741acbbdeb14217a3ef845f858b481c24c0f.nq.gz
│   ├── 309bd01dde9dc184df1ee01f87e72efefc940fa2.nq.gz
│   ├── 388a470f33bb061ae16bf2347cf226aafbf8b4c6.nq.gz
│   ├── 3e59c0bfe845b0331f6d63c64ece72f4154a5079.nq.gz
│   ├── 41bad72a05ec6b42b69f43cebbc6a3d42421a36d.nq.gz
│   ├── 48bc7766854fde3e0f45338ae5606480cf7a6acb.nq.gz
│   ├── 49cb0436fc52c72304be7968bf81addaf3fb33b8.nq.gz
│   ├── 50b91c86e74dffc3b3e150adb645d9b44be49245.nq.gz
│   ├── 51df186fc9564ce1a1a6b8327e4597110e1a5f34.nq.gz
│   ├── 5934afe9e199243f2ca74131a6e4b51641ddb999.nq.gz
│   ├── 5de1d84457230f0e5fa72e6d5217c043aeb4c1ab.nq.gz
│   ├── 6396dbab0f0751c572176a8a2d93a3b226ad03b0.nq.gz
│   ├── 671875fcc38c755b1111baca35df236d4a511a83.nq.gz
│   ├── 6bee99ec57d3031f2cd3d091bae430436154485c.nq.gz
│   ├── 6fdd509c48b524b73c964b258c6d7d507e53f378.nq.gz
│   ├── 74d10b136d309140b99a59392d357f71d87603fa.nq.gz
│   ├── 77d8e9491234384c9aa71f4ba7e33856adb1b856.nq.gz
│   ├── 782c9969309a5f4cb08f806233ade974789041a6.nq.gz
│   ├── 80f1b391ee162095ba0e48c78813ad0cc74ad4ab.nq.gz
│   ├── 8113703af783ca483c1d9211b856cd3ad8144bbd.nq.gz
│   ├── 8a67030e933c379ac61cc63ca92722bf831a81db.nq.gz
│   ├── 8ca398afb3e5cb7bebe24ff16c5fbada45b2996a.nq.gz
│   ├── 916492e5f07b6d74be32c6f8be10bd54add78e71.nq.gz
│   ├── 91abb11fdf507883caeeb2d2958e1c65fb6cbdc1.nq.gz
│   ├── 9261d977bf94d573c7dbecdc020b33f1bd292678.nq.gz
│   ├── 98245770ab5530e11d989702ce699b7dff0a7769.nq.gz
│   ├── 992552b24ba2b077fcf5ace684ac0c4a741e74c1.nq.gz
│   ├── 9a1b2ea3f22f24b200abf2ba1da1c9ae82d58695.nq.gz
│   ├── 9f45d4b39f61af9cbdbcfdaa0445f1fba3635b1a.nq.gz
│   ├── a3a183836ad6ff678c0591ff955adf8215509857.nq.gz
│   ├── ace47a8ea2c6bf97f31a0563f77de72a096a5dab.nq.gz
│   ├── bbcbbe7d61558adde3cbfd0c7a63a67c27ed6d30.nq.gz
│   ├── bc1a6afc261610c817f552677ac5502bc59824b7.nq.gz
│   ├── d612189cd001e2990c1d6af950a767deab97a1d6.nq.gz
│   ├── dafbc27155b9f4e192a60b6c044b6f9556dd7839.nq.gz
│   ├── de198e9924ca61e1b691f6250613694cd662838d.nq.gz
│   ├── e4576b5f4afcce1856bb853bf91fd7aad0053b40.nq.gz
│   ├── f3dd5da30a44bb3a510ce3960afbe4c05028bea5.nq.gz
│   └── fae1d006d04ff6c599c6e865c695e4548ba2dd68.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 1ebe10148c8089e888a36b25b5b557b9e94d8a3f.nq.gz
├── filetree
│   └── 1ebe10148c8089e888a36b25b5b557b9e94d8a3f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 61 files
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

[deedy5/duckduckgo_search](https://github.com/deedy5/duckduckgo_search)

---
*Parsed on 2026-04-17 by [repolex](https://repolex.ai)*
