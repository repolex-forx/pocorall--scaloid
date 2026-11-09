# Repolex Knowledge Graph of pocorall/scaloid

RDF knowledge graph data for [pocorall/scaloid](https://github.com/pocorall/scaloid), parsed by [repolex](https://repolex.ai).

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
rlex download pocorall/scaloid
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b9d13c782f6b8364c4f63e50df74054802b31127
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b9d13c782f6b8364c4f63e50df74054802b31127
│           └── chunk-001.nq.gz
├── blob
│   ├── 00e3a4ccafcfeb27ec6173867a52874f22035bed.nq.gz
│   ├── 04267b14af698ecc351f1ccc0908218ee60b8a7a.nq.gz
│   ├── 062e75ea96b0e712ec430b5f40d97abecc444ad5.nq.gz
│   ├── 082cb267dde8d199497e212c05878b7c734bc72c.nq.gz
│   ├── 0b176a16bdd9c859c3d74f3bf67a8cb438340154.nq.gz
│   ├── 16d693bfdd1c60084dc05ea46ce87af5328b7dcf.nq.gz
│   ├── 1d7c09cb85cc7eb002e357ba0c1b233c95f8d2f3.nq.gz
│   ├── 1e2a04b122d03dee70c9b4cef53af57dcb6ba580.nq.gz
│   ├── 1e6569e8971d59bf32d221b421b847f218bc5db4.nq.gz
│   ├── 1e77179af98d33369d1e81a88184f9930075326c.nq.gz
│   ├── 1ea7e11da356e4f7aecefd67ac649f9a5ba08084.nq.gz
│   ├── 233089412961000a6da143c184ec07a3d4f7ffcb.nq.gz
│   ├── 254fcf754ce8a6f58ce165f39e25dcce41ff7609.nq.gz
│   ├── 25822a93033aef36b5b58a313bd76629b1dafd76.nq.gz
│   ├── 2a318a02a2542d374932ba4935f35af6b40124ff.nq.gz
│   ├── 2bfb15ef0a16c485a70a4e8daf43dc3dccb10113.nq.gz
│   ├── 2ec45cfdceecc94f1abf45637991b3e571cea94d.nq.gz
│   ├── 32f44e86b4ea1b6a352dce719da12d6bd01d747a.nq.gz
│   ├── 3a104e584d5e2ffee5eb767fc5bc0a241d6da89b.nq.gz
│   ├── 3cf588b1df5dc63eef8937147a97cec20ea8e192.nq.gz
│   ├── 409f7ccb75ea23da0252efb81e8b881160b576ac.nq.gz
│   ├── 410d48b91daf15a91f3feaf4d7f8c5c35b9533d0.nq.gz
│   ├── 45751903810de50190f5496924c051364c6c0d49.nq.gz
│   ├── 473c6473b35bc2790d733461ea781a0c357cc44f.nq.gz
│   ├── 4f8208fcd44b2c63ccfe7839019595118b24917c.nq.gz
│   ├── 4fa083e46070ac724a24e6107213d943788cdbcf.nq.gz
│   ├── 54f5865e5d57628f7da1f9dd452240c58529bb81.nq.gz
│   ├── 55e059a8b35096c8383f71a1cdb328dd1c8df92f.nq.gz
│   ├── 588b442c8ed315a8a8fbb9fd580a4844ab13da08.nq.gz
│   ├── 596fcf52b8da40ad50e13e546fb11b846e6f29dd.nq.gz
│   ├── 61b66259d06d75db1aae9b0a4d42153e8ef05883.nq.gz
│   ├── 651f179c27ddf491e29791f85b5b2a4d7d27b386.nq.gz
│   ├── 6a96b4a8ad96e04f4270cb9c26903b58270f285c.nq.gz
│   ├── 6e60709e695fd1afdf73d6f8bfb1eb3efa6df2d1.nq.gz
│   ├── 7289d41a0a272e0b37c7a371002715c67b57fda1.nq.gz
│   ├── 783d7095660f788ba0440fa6c3507f5381a1d417.nq.gz
│   ├── 7b1af69c8a62506f8f0e15f71328d087622e8445.nq.gz
│   ├── 8708d1c53f45616524529ad840c1e561ba7d02d4.nq.gz
│   ├── 8924ade7ce93c6eee6dd4841c38532d863ca42a7.nq.gz
│   ├── 8b3cb29177133c6195c6006ceae27af8c2552448.nq.gz
│   ├── 8d001abc72e63d7407fc3cac705a03a8302c6b79.nq.gz
│   ├── 8dfac26c9244985e730537a976d626846d2306dd.nq.gz
│   ├── 9769905aa8dc19c601ad92374bba12991b050b0f.nq.gz
│   ├── 98508c8f417a604155eb3c5a6dc84e32356ffbd3.nq.gz
│   ├── a22bcb1786fcf1ca3b0a29c9ef22cf5f695a2081.nq.gz
│   ├── a73ec26aa9ea03b7a0d89350cc73c0dc9157b14d.nq.gz
│   ├── a8bd2e5c3bebe0c09b1b198344ed03cb16663456.nq.gz
│   ├── acce6156a43e7fd56d88d085853eb467973fef04.nq.gz
│   ├── b20bd1944f05d6ff264410deb199d717baeccbe6.nq.gz
│   ├── ba4eb91a68ce90a32ba12a42fe6e9f9d78f05c5a.nq.gz
│   ├── bb392ba9a99db7411c20530caa6be52c084c205e.nq.gz
│   ├── bc2d53bd01a1ccce7ced54fc225db673c3fbd07b.nq.gz
│   ├── c66d26d06bdfc61b3ba8ba10e8a411f7b5904765.nq.gz
│   ├── c89363374f6d59f5c56ce35b0f4dfdfa21c951aa.nq.gz
│   ├── cbe89434d6f1bfce92fdda07ee4a731a71f4e690.nq.gz
│   ├── ce75acf59428b2fc436883eed72899d21d4b0110.nq.gz
│   ├── cfa7187ce4476dee286c5f870b9917e18e38d79d.nq.gz
│   ├── d7003b6c6cace052eb455d8d13277ec5db2e201d.nq.gz
│   ├── db065bbee450f2b46133cc5b2aca7d266cf5ffc2.nq.gz
│   ├── df52fdcee32cc70e8ae509e8757c3fcb6da36077.nq.gz
│   ├── ef1dcb9badeed720555971149b05f634a8c25fe8.nq.gz
│   ├── f15ab91d6ce95e3d8989c55e777903450478eb6b.nq.gz
│   ├── f4c6a015987f4179abc61351d63fc38f7e315901.nq.gz
│   └── f905e408006f322d6d2e7bd1a8d8474be678bda6.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b9d13c782f6b8364c4f63e50df74054802b31127.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 72 files
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

[pocorall/scaloid](https://github.com/pocorall/scaloid)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
