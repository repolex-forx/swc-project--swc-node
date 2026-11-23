# Repolex Knowledge Graph of swc-project/swc-node

RDF knowledge graph data for [swc-project/swc-node](https://github.com/swc-project/swc-node), parsed by [repolex](https://repolex.ai).

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
rlex download swc-project/swc-node
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 41dc95797d26bb0bb4b0f92770657b3010e4364e
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 41dc95797d26bb0bb4b0f92770657b3010e4364e.nq.gz
│   └── repolex
│       └── 41dc95797d26bb0bb4b0f92770657b3010e4364e
│           └── chunk-001.nq.gz
├── blob
│   ├── 062b73ed17ea02fee5ab9849f2a8da18a487740d.nq.gz
│   ├── 06a1007eec501ccd71f763489db4950c6b81aeb3.nq.gz
│   ├── 07cbd30203429e348fdf49b231b9f9d0533d9106.nq.gz
│   ├── 1068bb2899a47beea63d62bf9771ecad84fa9ce2.nq.gz
│   ├── 1118994dee4b8abfaff0ac4ba7c2eb099d39ff82.nq.gz
│   ├── 1164b6595f84ac7fc2d539baa83ece64f50db3a8.nq.gz
│   ├── 12bd2f3efbd71a58e3b00ef0ca5ee594ce106de2.nq.gz
│   ├── 14ace7b36f93579a8ee1277cd716324b9fd31578.nq.gz
│   ├── 19c90ed8cf4dc814d3bc51051abfba3496d34c7f.nq.gz
│   ├── 20421b40baa1c7038d23f5db65628d733f9563c6.nq.gz
│   ├── 210d92200c156991d3552e380605d53df4715eaa.nq.gz
│   ├── 255a8493cd452e0bc126c30f8910a3aead10937d.nq.gz
│   ├── 257cc339dd30f857f329b5bf8f440ec060ed108f.nq.gz
│   ├── 28dfaa3bb7fe725da939142e5ab753be2d595935.nq.gz
│   ├── 298a916df4c4fd6631936c2fbdb4be7e832748f0.nq.gz
│   ├── 31354ec1389994b5f6708c7d915fdcc6bb76ba6e.nq.gz
│   ├── 351551bfcd3390d717432103ed33334aa77cbe1c.nq.gz
│   ├── 3caad40f7c70d740c49c74a4a45adc1014df5728.nq.gz
│   ├── 3ec47de9a8e8f26d37c715ba8aac593a3704d854.nq.gz
│   ├── 3f4e5dd665d81d038c72e111f0ff5b2f753aa226.nq.gz
│   ├── 442fe0b405794752e30c2113a956bd4796933c50.nq.gz
│   ├── 47ef28b93b1c8db69d97666bfdde6ab1e1b11e66.nq.gz
│   ├── 4bce11e14b5b81e5ac368bb66b326856c0924605.nq.gz
│   ├── 4be1995e9ba6554cc69b5b7cb9b9e2190bf74f02.nq.gz
│   ├── 4ca957bd7a90876d879a6be3e998f2f5a7bacef8.nq.gz
│   ├── 4d5a9908a4b17d1ab984c5100bdb770cd0c5329e.nq.gz
│   ├── 4d8267a0cc256cdebbd54741e6c6ab1aa9f8dc06.nq.gz
│   ├── 4f4f78c6209f079920b3225985624853bae0430e.nq.gz
│   ├── 5998e81ffbeafe96723065c900f947728d0ad8cc.nq.gz
│   ├── 5b84bd9d2356144137acb2efbf30ea46f9135ac3.nq.gz
│   ├── 5f318c50c355bf0db53ddbabbfb3d3fedceb8c77.nq.gz
│   ├── 61029263462b00857078547526c654c5674cf670.nq.gz
│   ├── 627c32568684a02a0259ba314a426a102825f570.nq.gz
│   ├── 6404653e459a988ad82b8888800bd0babb7f7da4.nq.gz
│   ├── 64342b364ef8033ccd26e3a5c713bcfa59acccb3.nq.gz
│   ├── 6a4ecb6e250e602c8678c9c2e69239c0aa5205f6.nq.gz
│   ├── 6de1f5a8d64dcf54e52ac6aaef559f1754c45639.nq.gz
│   ├── 6e9b876cefc6b6b789341312e61c016aa534359e.nq.gz
│   ├── 71991ede015817bec8e72b61f750d05c8955138c.nq.gz
│   ├── 746eb6f189978c64da8ed4530bdc4f53d0bfb4f3.nq.gz
│   ├── 74eb250e19599b2a936aadc4f24cba1c609bcbcb.nq.gz
│   ├── 755c785a27469db8ece454eaa49079a78d01bd37.nq.gz
│   ├── 75ce94daa088dc45c5017b1aea89ffdafa50c678.nq.gz
│   ├── 7642f79b89eb8b9f6a89d498cc4dcbe43c9e93ad.nq.gz
│   ├── 7a20f9cb909c7ef17ca6c892f7c2eece5957d07f.nq.gz
│   ├── 7c487ff1574866ec4ebbc81b27d3a8e37eacb543.nq.gz
│   ├── 7e2acf6757a573f535ffda7ebacdebec83404a60.nq.gz
│   ├── 7ffd6759f2b0b5064eb8561865c50758e0fff1a3.nq.gz
│   ├── 85da7ee54368b36a314cf271ae0f32741c39a48e.nq.gz
│   ├── 865c173542baec8364d657ac3cc9d74bf38b644d.nq.gz
│   ├── 86d7146ddbd5108f0b40a62389614c11f9dda695.nq.gz
│   ├── 8cb1c4474375ef06b6e90f64dff908d54513a30e.nq.gz
│   ├── 8edbcc65dcb46dc878a2c97903e91b5afeac1088.nq.gz
│   ├── 906b26965a710040dd24072107f123664718ca90.nq.gz
│   ├── 92d39e23e2d6bed0f55134fdd8dd968d6b41314b.nq.gz
│   ├── 94016ffe456a51acc351b5dadf2e67d171261791.nq.gz
│   ├── 974e8d0799b8216d013f764c234c69434592156f.nq.gz
│   ├── 986bbfe699f608eb97e423677fcb6f79b2dea709.nq.gz
│   ├── 98b680ce1d067f03b644be488dc8d0a6b026401a.nq.gz
│   ├── 98e9867d9fa99499bf3df45db6844eef6a4397a7.nq.gz
│   ├── 9d758e8d4148a64f09653252f6cc26ce25673851.nq.gz
│   ├── a48cd089658129bf0f90f5446cab38966b274849.nq.gz
│   ├── a56eef2ab6ff97b0e3ffc6530fe617b709257114.nq.gz
│   ├── adbb762d7e3a11242e9b821a72a77c6c9bf99139.nq.gz
│   ├── b8a057dc8edbbba93fb201450302d4bda453bc22.nq.gz
│   ├── b9b99d1dc85e340a9f8676590655ddf043508ed7.nq.gz
│   ├── bb8862a00b02ace36843d91cf3059c43cf5094fd.nq.gz
│   ├── bc9ea55c0a4f6df3cd3613538c768cbc7ff8cd72.nq.gz
│   ├── bd2b9f1456a0c1b88633216297b916881a2d8d49.nq.gz
│   ├── c8e0e8efde1a90dbd8c73b2844755cde790831f1.nq.gz
│   ├── c9d7fac5574e3f2edcaf4ec9c9c38ef77a7d9453.nq.gz
│   ├── cb5c24d3fd78cf99bbe88a52ae103bda095e2d88.nq.gz
│   ├── cd85b56347067290f35259ea9540514aaa99af34.nq.gz
│   ├── cfbf20be6ced8e9ee4a9378cac5781b2ad51d6ab.nq.gz
│   ├── d66006cb55b48769c39e7dc64bba3c8e1af5905e.nq.gz
│   ├── d848cb0b49f067c055965c40ad2cda18fccaba1a.nq.gz
│   ├── d9913f520d484a84d3fc82448b061ea62dea5a65.nq.gz
│   ├── d9ab5c9a44e4e702427723d9e9c46573929a5884.nq.gz
│   ├── db2ac5f258482595459f3f372ec60fd9f37d53d4.nq.gz
│   ├── db67d57d113a5989e34815623619de1fed4ca181.nq.gz
│   ├── dc6ae932049016f9a1f3ff7c373345546d4b7c91.nq.gz
│   ├── dd47c2e4a45ff5585cf5741374cf62233fff291f.nq.gz
│   ├── de0c48d27cc39b77bdea62aac4f1a04a2934a6f8.nq.gz
│   ├── e83772cc38fbd7d41adeb26b7bd3d6e06f97bd67.nq.gz
│   ├── ef74615458eaef55f8d067e5b316095556cff33b.nq.gz
│   ├── f033f79b5f2c3fe0d9c56230c504fc432539afcb.nq.gz
│   ├── f586e15333f9937e664983a764f24279906446d7.nq.gz
│   ├── fac147974a156202c68d6cc0071578d3ed0ac29a.nq.gz
│   ├── fd33425aafc05cf69f2bc8261238f43fd0858f97.nq.gz
│   ├── fdd71a638cfe9f1bbab1f125fd5643c018b94e7f.nq.gz
│   └── fefb1f4c39dc36bbac4aace5c6bcbd4cec22c33f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 41dc95797d26bb0bb4b0f92770657b3010e4364e.nq.gz
├── filetree
│   └── 41dc95797d26bb0bb4b0f92770657b3010e4364e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 101 files
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

[swc-project/swc-node](https://github.com/swc-project/swc-node)

---
*Parsed on 2026-11-23 by [repolex](https://repolex.ai)*
