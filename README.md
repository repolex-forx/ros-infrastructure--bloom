# Repolex Knowledge Graph of ros-infrastructure/bloom

RDF knowledge graph data for [ros-infrastructure/bloom](https://github.com/ros-infrastructure/bloom), parsed by [repolex](https://repolex.ai).

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
rlex download ros-infrastructure/bloom
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0179b9193b4d192213affdd31b2ef58eebce18b2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0179b9193b4d192213affdd31b2ef58eebce18b2
│           └── chunk-001.nq.gz
├── blob
│   ├── 0010931d832c9fee65702b78c66a489d58d1f35b.nq.gz
│   ├── 013773e8c5968ec470b96815781af1defc7c5533.nq.gz
│   ├── 01c63025b101fa4e652af3a7cc8ae4b79a9f1263.nq.gz
│   ├── 02e24e58d14ef151733c33c113bda566d2c229f2.nq.gz
│   ├── 050c4f0d81235b2f84e629617dec711a5335dc76.nq.gz
│   ├── 05f0375dc6631d399bbbed6b96fca46d35dfb272.nq.gz
│   ├── 0652d97e093aa72b401f57d4a02e84aec8ec5c19.nq.gz
│   ├── 07bd1e94921c7f4378fb90df4ba2c6e95ad43d17.nq.gz
│   ├── 0967ad0cac8d2f570d187f0260250c7e37105bf0.nq.gz
│   ├── 0c8b13dfd76a86dede41e19a973566f3bbec4c5f.nq.gz
│   ├── 0e1b535549494a6a6d68687a626a34fce01c7f3f.nq.gz
│   ├── 0e7ca83a898b2c7ec2bfd7bfa88630ecd1afe7f7.nq.gz
│   ├── 111f74f45ad7d50584e8bc9e02214f79d77dc218.nq.gz
│   ├── 12593862fd760e5911dd207361bceb7f078546db.nq.gz
│   ├── 18814cbefa73f9a75aa219e4fa26444b942a417e.nq.gz
│   ├── 18a180a9bcafe68d3c3b4e03d36a5778a0d6b7f9.nq.gz
│   ├── 1aafa5738d4e4d7271b0f7377e227ad69b876569.nq.gz
│   ├── 1b0f263d15eded502441412e7d5c408b2ae1029a.nq.gz
│   ├── 1e0f6bf07d7d1a2db7eadf36219e51f5e0a41aee.nq.gz
│   ├── 24a102cca062eb3dfb94b760a67bdc2a363d9ca6.nq.gz
│   ├── 25a613198df14f0a73d0b4a779f70ff2f60d4e2c.nq.gz
│   ├── 276329db83de163e68e997211b36941c38e55fd5.nq.gz
│   ├── 284a07142d7ad0a8c9398484d9f86f93209f733f.nq.gz
│   ├── 2dcdb587f83c012f33522ea41740660dc269a533.nq.gz
│   ├── 2fae015519f357f80ba0155fadfe8e61e9496071.nq.gz
│   ├── 30f3da509d72c2c78ac3f7a7437da1bbe858f05a.nq.gz
│   ├── 322d382bfe1146e3577445799424d17aadeb319e.nq.gz
│   ├── 33c9d642b5571e0d670e56d41da60c844bbafdd4.nq.gz
│   ├── 3464a0bc11e1ebcd8a1da2ff7ab8ccf47e01105f.nq.gz
│   ├── 3585909062373de14f5843d2a766f3de64a7bba7.nq.gz
│   ├── 385f4c996d08a761944dd7e5b84fa8a3978ac8ad.nq.gz
│   ├── 39cd2b3e288df1b39359a07e1766ebbddcf9e163.nq.gz
│   ├── 3a2d79b95319e898f0096e56b8e81fc084267a04.nq.gz
│   ├── 3f7832588d427e1a787fdd34b3c8e8f0246e3b5d.nq.gz
│   ├── 40d8cc94198bb0bf80a599ed1e13fb02bdcfc98a.nq.gz
│   ├── 426830d08a284264162193dba72070380df79bfd.nq.gz
│   ├── 42b413371f6764495ccfbcdb79405f82785f1975.nq.gz
│   ├── 466fcfb043bb76832249e7a9cd48dbea1da02b66.nq.gz
│   ├── 4d02618c7040bc00fdff56415059fe596783734c.nq.gz
│   ├── 53c3716ad1fb5bfb94cfa990c48701292780dc80.nq.gz
│   ├── 5538d31952ed8002093b70b2f0722e17fe71be34.nq.gz
│   ├── 558528782571a3f27c826c99386ac95f27ebd85f.nq.gz
│   ├── 55d86c734df7c242c217b866acc3f5369ca870df.nq.gz
│   ├── 5c89c7b497635d8e502a03b799bfc87cde280e26.nq.gz
│   ├── 5d2afb373a9ecb2e3bb8084eedf8edd29139fd00.nq.gz
│   ├── 5daf54c3a7a0fd139cb70e1718a0fce520c9bc83.nq.gz
│   ├── 5ecd25cbc17fd4e3becb4384c530f1a87a307b84.nq.gz
│   ├── 605797f2395f407f978ac52af7b624475040df33.nq.gz
│   ├── 6284680a1faa4f93339c446231fac8bbf3405f93.nq.gz
│   ├── 686ebf39476c1bb56568465098c05f7a25b93ab9.nq.gz
│   ├── 68c1b0218df5192013eda325fcb1ac9028a3c235.nq.gz
│   ├── 692c849cd29ffc7e23f686647ee1cce8f7b9198e.nq.gz
│   ├── 69cf43d12c0864ae94b7f80302fb57e91865f8a6.nq.gz
│   ├── 6a4e8842a92344efd24eccf3ff570312629f97b1.nq.gz
│   ├── 6a5bf07cd129837a75c7811e7a5ec25572e3b632.nq.gz
│   ├── 6b98efaa03e925590c91c2f754111d86628bf613.nq.gz
│   ├── 6c106ead3471f5bfb1031a959ab7edb155ac0236.nq.gz
│   ├── 6d7b65c3479be9d999ab5e6e88585a04da6771b8.nq.gz
│   ├── 759822a070b3b69ae65f916d847081d910d554c6.nq.gz
│   ├── 78c0a180e5bfd4e5e7939fa00426e460aa89d0cf.nq.gz
│   ├── 7a87216d3cc89c4e9d5ea56ac9537953e60a9fb6.nq.gz
│   ├── 7aaee7f4dc3356144b2d52c54525316af8253b20.nq.gz
│   ├── 7e942b6b925915368fb3964e5c09a4de77289df1.nq.gz
│   ├── 82b0758e43cd26fef190dac764f90953c9e71c00.nq.gz
│   ├── 832b38130e474d873459834f60550e928105d743.nq.gz
│   ├── 843e363775a5cc154577cd8c01cc70a3c24fb754.nq.gz
│   ├── 8441ba7613c0614ecba31627ea9da7624db62057.nq.gz
│   ├── 853e4a6867ef2f05f4c34b24c41b4c8fe3e804ad.nq.gz
│   ├── 85fcc5e69c427272b2b37501fb00bd0d433080bd.nq.gz
│   ├── 86d7a7a02dd4ec3b70a68557885199a0ec1c1fa9.nq.gz
│   ├── 8aaa9d0927c0234eb9594e6a425ea9b2a5d5c988.nq.gz
│   ├── 8bc5e48a1e75639192550f03c6154ed1d72f4608.nq.gz
│   ├── 8bece5515a7d35f4a2148447b48c80fc5a253845.nq.gz
│   ├── 8c4c78b063abdf704107a25b536b762ef97f8cde.nq.gz
│   ├── 90b17cb0554e5d21c245749b920f4611cbfcfade.nq.gz
│   ├── 938ed84fd380f47701c4f7a92a23bacf98006481.nq.gz
│   ├── 942f6d0068f7f22f3a35249de2e1d3175627b19e.nq.gz
│   ├── 943519dd136ecce522efdcf926f8d4739cd12214.nq.gz
│   ├── 9666bf410907d00c38ea5d9ce95b62a8cf7bf4a1.nq.gz
│   ├── 9e1c3df833203dda6488324d1f1d1ec880828258.nq.gz
│   ├── 9e98801b4b281feee9d59369b5e06387d8650560.nq.gz
│   ├── a074d8eba6107f3941f21d879f23dccffed244fc.nq.gz
│   ├── a0ceb15dd668887cfb4bd24b40b581f9b736ad7b.nq.gz
│   ├── a0de06f831cd62d83a094b5f087bbbbb85075a8e.nq.gz
│   ├── a72fb6b40b8a4e5d61e1de18c8763c39362b5b2c.nq.gz
│   ├── a856369d18c32cb9bbbef3a1110c7395edcc835e.nq.gz
│   ├── ab9ea63c5b27b81e609babdaf29b19e39a278cfc.nq.gz
│   ├── ad24a164d06a7971a9dcca990e935fea39b6ce88.nq.gz
│   ├── ad97e056a93343651a06ab4b178fd26d3d5e8ef2.nq.gz
│   ├── b2a40f669fff1be8f8b48dd774ffcc0eeeb49186.nq.gz
│   ├── b2f4ff45c42591b81bde037b4283aae8cee2700e.nq.gz
│   ├── b53040a003b65b9b03f571dbf27f220d30e9a732.nq.gz
│   ├── b951952cf526d13323979612cf53fdcc8cc3d3b3.nq.gz
│   ├── bc2e91c2dd5341829f63361206b66f0de0506f45.nq.gz
│   ├── bc82fd5da0c4966b2a99058e132cc38a41c7d40a.nq.gz
│   ├── bd232d2c5aa904d9e0770e9b145ad50d80d44dd6.nq.gz
│   ├── bdacd73109b0d32d4d8b9a791af9e0152886d5b8.nq.gz
│   ├── bdca7be18d68f305ffefebb7b26163ca86f7a09c.nq.gz
│   ├── bf1e9d57ea728fadf73b01027bdf1d6695410aa6.nq.gz
│   ├── c38c828daad3296b7edd83287f60b3b0186a3782.nq.gz
│   ├── c497239b0ab65ff23dd5c636f958a263db8ce3d5.nq.gz
│   ├── c644896827ea3890a7d4cbbe2e660363186070d3.nq.gz
│   ├── ca5e6b8c021c29e3cac9d8cc44aa7efe517627f9.nq.gz
│   ├── cad745c829c50cc7ba272e70a07b2cdef7950326.nq.gz
│   ├── cbf7bd30b1f994fd27e9c93a6100e1175c5582c7.nq.gz
│   ├── d31c2f2ffe17b5057f484c464ad59a5bb1e1a66f.nq.gz
│   ├── d341e8237a0e57af675e04630e4aa2847d60d16a.nq.gz
│   ├── d5bfa6bf47811f573d9e948851607ccb3a0a5f42.nq.gz
│   ├── d6bda74ae9b43349331d2b6342dee99bc827984b.nq.gz
│   ├── d7a29059a73f373d73d07068c2a0911859142ce1.nq.gz
│   ├── da556e4610e7b9eb905aa7081b12f31394004272.nq.gz
│   ├── db87c728b2876cd3207f6c271b822f1a89e149ed.nq.gz
│   ├── db9b7a166ab315c45a4894024b3fe8bd847585d8.nq.gz
│   ├── dd9f6b257c3e9257434a07d40a4c37e00a77cb56.nq.gz
│   ├── de40951c0a30e14163be79f96c093e9852da3a21.nq.gz
│   ├── df4688863e16bc29ddd654345064fe4815abf1b4.nq.gz
│   ├── e35d8850c9688b1ce82711694692cc574a799396.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6b1f0e4745fd619b1e4854239a6cc7d7ef7fc8b.nq.gz
│   ├── e7f90c47787ecf80f2c0dd36624127f4d09a6877.nq.gz
│   ├── e89c5de403d37254cf0aeba004f367dc65e68661.nq.gz
│   ├── e8ef0afdb4967fb6b85934a6a16129038142319f.nq.gz
│   ├── ef927d3af379e920539efa3c9ad13537c616e8b5.nq.gz
│   ├── f19cc7542bac6e67b964cb3c10e3b1a781ba01e7.nq.gz
│   ├── f424316985a74e57f2f223577f04d3b3fe764fcd.nq.gz
│   ├── f55acd94b4be607113db85f7c49d4c3cdff3c100.nq.gz
│   ├── fc05e4d79e3927a8d5e0194ee62a472d16614855.nq.gz
│   ├── ff7ccab7054c06df677e8f08314cc1bcbc504264.nq.gz
│   └── ffa3421a1fac9e1a86b0507d733310f27630631f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0179b9193b4d192213affdd31b2ef58eebce18b2.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 137 files
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

[ros-infrastructure/bloom](https://github.com/ros-infrastructure/bloom)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
