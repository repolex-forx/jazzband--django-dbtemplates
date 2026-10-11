# Repolex Knowledge Graph of jazzband/django-dbtemplates

RDF knowledge graph data for [jazzband/django-dbtemplates](https://github.com/jazzband/django-dbtemplates), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/django-dbtemplates
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── eab2ce0a7edbbd593f37538be358e58a7b237af0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── eab2ce0a7edbbd593f37538be358e58a7b237af0
│           └── chunk-001.nq.gz
├── blob
│   ├── 000a09c6dec1e80107d7d5f9479bd34e0cd42ba0.nq.gz
│   ├── 010db5b40e02373102846c4e8962d7487cc15c4e.nq.gz
│   ├── 055b5e6d7ecf7e1a0a15ed3d36124d8fc626bc1a.nq.gz
│   ├── 062e2e5d81baaf43071f4163922d0d9cdb72c666.nq.gz
│   ├── 071970ce3d89c825cf6cb8ccac5e27b36926b667.nq.gz
│   ├── 07b1ddc921c9312eb33ce89d81a8280969518c32.nq.gz
│   ├── 087a8637212c836bb8da118600926a3d041d1b1c.nq.gz
│   ├── 0a7cb9d1f81f330d18bf29e8ef4d9735fac3f0ed.nq.gz
│   ├── 0b29bb936e9de5416aec0bdca973246cdfcb0fae.nq.gz
│   ├── 115a1f0040e90c8d9cb921b00dda99a8d4644daf.nq.gz
│   ├── 198fdde919bf45d1965ea02c3114885ee7596550.nq.gz
│   ├── 2055241759fa30ffe4407ae8a3803320a2994e0b.nq.gz
│   ├── 230d88f3a3ac1872bf5b20e30398df58597751d8.nq.gz
│   ├── 25152de514df123e93f67ab8e9c6737d5de4a45b.nq.gz
│   ├── 2a486b4992f7402254b9481dca0afec700a4f7f4.nq.gz
│   ├── 335fbb6df6230ee4733f494e1118e6859b16d804.nq.gz
│   ├── 351a27a121f39d5702480e8beb6be9b0d08ff844.nq.gz
│   ├── 37effcb33a422b11868a45fe00ccf313fa59ba68.nq.gz
│   ├── 3837e65d8bb426c3c88b51582639e5f66a0be312.nq.gz
│   ├── 3a00d9aa0a65ddaaec990dd20284b0c25b0e4b3c.nq.gz
│   ├── 3ae90e700f9b52fc6cdc8ae2fdb88094c903d14c.nq.gz
│   ├── 3c53d24002c97a933b5d8e5aef082ecb2928dee9.nq.gz
│   ├── 40a90081ddd0a4c843ba27ad7ed6d4a5df533526.nq.gz
│   ├── 4b0840abf96dc7fbd3a11102312e3afe63dc0b29.nq.gz
│   ├── 4ea23859be5c4fa2d3e14d4085323ff4999a1655.nq.gz
│   ├── 4f5bc611564911f3ee6aee1638140a8e1881d04c.nq.gz
│   ├── 50f7fd5468833daffb14b5c4dbcd3a252391e43f.nq.gz
│   ├── 5a57f27225ed4307542ee520d068332efca93ae4.nq.gz
│   ├── 5fb2df1517539f9db2cb22d0640817c75e24a6bc.nq.gz
│   ├── 61cb56145250b47784f43baee8f1770755daff31.nq.gz
│   ├── 66275b720e7bde4ae74383314583d88386b885bf.nq.gz
│   ├── 662b4f6c388f0711b200993abb0a628b8df9327b.nq.gz
│   ├── 67a91160d97d9f350de6c06997425b0b102862ce.nq.gz
│   ├── 6b95a367e2068f7d21ecc7fe14133ffef3afa917.nq.gz
│   ├── 6b9e46a298efd0ef12544097d6efd9d11137303d.nq.gz
│   ├── 6ea4a5add93678dcdca03760f2905300f8bc2a6c.nq.gz
│   ├── 6f85549f198a01bcd1b04e35241e8f3db831a235.nq.gz
│   ├── 7150ea41ebe4d3d2af7e57f7107d81c07c196a8f.nq.gz
│   ├── 7ac217fa079cbba0f940cccf91e6032f4cce5181.nq.gz
│   ├── 7bf392cf0672ac310451d5c0ccc96b1ef979abb0.nq.gz
│   ├── 7f6ad1ababa224d8436e451b4d9b77ef7e88ccc0.nq.gz
│   ├── 89039ab5ba093cca6e7754fa0bb1b1d085a451c4.nq.gz
│   ├── 8bcb816ed78698d2309bbc83d6deaa8770215aac.nq.gz
│   ├── 9006d894ff7e7241dd7158d66106cd7929aedf4e.nq.gz
│   ├── 931fbf09585b458b983c48978e53c6f43fa067a3.nq.gz
│   ├── 9a6973028ec83638230dafb481ac07606b208771.nq.gz
│   ├── 9dd4105e2eeb2a6fe5d41dab782e432ff2496760.nq.gz
│   ├── 9f752736243cb0e277e0904e619b8207738cff88.nq.gz
│   ├── a3534ee71e8475008aa1d82700defdf67d2a0ba2.nq.gz
│   ├── a6647dc703b535bd2316293c76e80e40dbf94bec.nq.gz
│   ├── a74f80fef98be568439b542a1245e96cb22a350f.nq.gz
│   ├── ac915122000cb3e1dc8d2c09885ba038dc88f4a5.nq.gz
│   ├── b062319397878bfa8dd3fedb0249be78689747f4.nq.gz
│   ├── b8aaf72596e4cbb324fa035143804bbfc9f6fc86.nq.gz
│   ├── c50cb2a0857d1cacf794d769711bed750acb481b.nq.gz
│   ├── c52b05e266a223f014f9fd0fd5b3176a266f1530.nq.gz
│   ├── c7021c243c1e83bf2db4c9b4a9ef45ceefbcaeb2.nq.gz
│   ├── ca0f12f544a8b3d87c4b0da72fa428fad2465dab.nq.gz
│   ├── cf23e9aa7a184032f31e3b96b5e75a8af10066cb.nq.gz
│   ├── cfab3772d7f19f26567905591b7454908d58f095.nq.gz
│   ├── d17752023dc8de4820dd0d99446ae33a22bbd8cf.nq.gz
│   ├── d3e4ba564fbf9ac31944e674cfb4469113120ab1.nq.gz
│   ├── da3c06a745ccb115a5e6a025199eeb10597427f9.nq.gz
│   ├── e0ad5f8e602e2d6c34792ba3353abc80feb7a9fc.nq.gz
│   ├── e0d5efab56fb94577e7804603eb6f21f36977cb2.nq.gz
│   ├── e510bcc4bbd089990be6d030c5ae89ac1b1eb0f5.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── edb99c96fbe2909cf932ab7acd52187483351518.nq.gz
│   ├── f146836ab4260538edb1797052ce9ecc4b009b2d.nq.gz
│   ├── f46a6d20f674539bc2de0aa6c1d42878003d84a7.nq.gz
│   ├── f6d65afcf5c48eac015ec2f966ca74acff7d2e8b.nq.gz
│   ├── faa0912da2dbe8d8a63e6d3042dc70f93938aba3.nq.gz
│   ├── fe02d1128e84e47e8fed30eb987b22c540c7c6ad.nq.gz
│   └── fee2f2ed0eb4b9ef989550a3dc9d38b1cfa03ce3.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── eab2ce0a7edbbd593f37538be358e58a7b237af0.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 82 files
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

[jazzband/django-dbtemplates](https://github.com/jazzband/django-dbtemplates)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
