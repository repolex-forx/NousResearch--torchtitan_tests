# Repolex Knowledge Graph of NousResearch/torchtitan_tests

RDF knowledge graph data for [NousResearch/torchtitan_tests](https://github.com/NousResearch/torchtitan_tests), parsed by [repolex](https://repolex.ai).

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
rlex download NousResearch/torchtitan_tests
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3513c4305b1729ea7fa73f6a56aa1a74a9c42834
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3513c4305b1729ea7fa73f6a56aa1a74a9c42834
│           └── chunk-001.nq.gz
├── blob
│   ├── 0d78263fdc50f0cc1ce16d48eedec9a7e7419d0d.nq.gz
│   ├── 0fc734df627deffa0cead700261731a403ddd17a.nq.gz
│   ├── 10e85f5aeecdad07ab4fcfc5b5ffab2a306edcbf.nq.gz
│   ├── 1cc065c6161d24262a8c03b463605aca33bc07fb.nq.gz
│   ├── 1f7e798ad14551bee9091d0505605c4b7b979e1a.nq.gz
│   ├── 234d8a663236426af1f3458336993ac98a0b19f8.nq.gz
│   ├── 256e234b43c739a1245fca5539f6f15790540dd1.nq.gz
│   ├── 33f1750d9f446e1bbf7116ed9b60f329aea5a38c.nq.gz
│   ├── 3c42fee0b9efe35000b33469a97102821fbd030f.nq.gz
│   ├── 3d581aad1974ea9275d09cfea04f95ff321a3527.nq.gz
│   ├── 3e33ff2ccee75df03205830c93c3b981fbb08879.nq.gz
│   ├── 3fffe66e2275686081263e465389f081d0d2298b.nq.gz
│   ├── 46a7e6628700ebaa5e9623287ca353ca4867a8cd.nq.gz
│   ├── 4b2951aed9d57d03a4b59f1313ceb5a79d98a786.nq.gz
│   ├── 4fc9caa8dbfc62cec306b26a6aa54f86c0f04162.nq.gz
│   ├── 529b3a477a5bb4e9e8a378c04ada9f03cbd2ffb2.nq.gz
│   ├── 590bba5bcffb0088ab69318de2363037e3bbaa43.nq.gz
│   ├── 5df18e31405ce9636b29cd06a23364d0f26c2908.nq.gz
│   ├── 65e1252cbcbf319abd2872aa8bd62830d2bc36eb.nq.gz
│   ├── 68ba7d64a0d79f41a989c065bf27855d7f83db6d.nq.gz
│   ├── 68dc5a650614a22c6f99af9b895efd521123306a.nq.gz
│   ├── 743b4e899ef96ca023557e076f5131b63e829a77.nq.gz
│   ├── 78f26c838683e763fa3e1c20facb53905a0bd317.nq.gz
│   ├── 7e7668cb65aaee0cd4637b8172d999af4c45f2ed.nq.gz
│   ├── 811377f95d908e36ff632bef52cf686d1d14b9ba.nq.gz
│   ├── 826da875f8d9b65dd20dd4fddd652c68cc3b4f4c.nq.gz
│   ├── 949e1d476fc59c57c609f9d54bae0edd6631be81.nq.gz
│   ├── 97856a4c5793d9b729750e894acf566beade1eb0.nq.gz
│   ├── 9950c30c4dff8afd2d8294af4f360aedb1495d17.nq.gz
│   ├── 9a723fd6ddefa7d03be2fe9869b7572b593c7b48.nq.gz
│   ├── a3a3f060d4899c337c4fcd7ca9d1da9254e3499c.nq.gz
│   ├── a57b5df80a87731c8c6cbe32f2dd8d583267d24e.nq.gz
│   ├── ac84ccdb8f8234dc744490dd9612ba31f3831956.nq.gz
│   ├── b205a870f584f652d06a39c33dd6e0d646e727f7.nq.gz
│   ├── b97cb143c865095390742838c4d201efad441ac0.nq.gz
│   ├── ba7e72403d02e9f740a7cd75cdd0da1b4207a2b7.nq.gz
│   ├── bac0bbaae78a680b39214758df060b895e719fe9.nq.gz
│   ├── bb3c40071205d509382e3e1b8a06e4b015607c12.nq.gz
│   ├── bd63ec1b73fb366cec8e90f66df6bfc17e0befe8.nq.gz
│   ├── c159c08651cb0813cca53d5ec39c0064fd1ac78f.nq.gz
│   ├── c89d95757c13af46ba90ec7775755b177815533a.nq.gz
│   ├── cd85eb9f1d2948efbf456111f42ec4927bae8cd6.nq.gz
│   ├── d45ad69fdf1c4f577e57e3c574737ccba01ac251.nq.gz
│   ├── d8a7cff3696329520051190c4d806da7c82fd90f.nq.gz
│   ├── db1f9eba01e76147ff2615b576f38ccec909d873.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f387014a5980af473c36315889f541bacae107a6.nq.gz
│   ├── f7c9bd3c13b98f12bca8d1affaa1862cf7095b78.nq.gz
│   ├── f9b2d9a1f39413a64745c3fae2647512738722fa.nq.gz
│   └── fc2e6f5bbc0ed00cc685db6112169734481066c1.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3513c4305b1729ea7fa73f6a56aa1a74a9c42834.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 56 files
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

[NousResearch/torchtitan_tests](https://github.com/NousResearch/torchtitan_tests)

---
*Parsed on 2026-11-02 by [repolex](https://repolex.ai)*
