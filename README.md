# Repolex Knowledge Graph of pylint-dev/pylint-django

RDF knowledge graph data for [pylint-dev/pylint-django](https://github.com/pylint-dev/pylint-django), parsed by [repolex](https://repolex.ai).

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
rlex download pylint-dev/pylint-django
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 370556a75a2b427e326bc98cef14059514df8d61
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 370556a75a2b427e326bc98cef14059514df8d61
│           └── chunk-001.nq.gz
├── blob
│   ├── 014299636feac0fdbba1f66a625d3991410a17ba.nq.gz
│   ├── 02774b120ffbdb5735ce0d8fd95b13fbfdf10890.nq.gz
│   ├── 043126b05b619a3f8b580e8048f15a0a12facbbb.nq.gz
│   ├── 04a3458293abeb3daff57a6898603adbf3d39119.nq.gz
│   ├── 05d5b48fc14f14c0098c7784cda2c684f99d3675.nq.gz
│   ├── 0d38dfc9161cdbce5292c3539adf27ef1c6dab72.nq.gz
│   ├── 0dbde08090c6e190d14f8930eb1d82a3f2dbb101.nq.gz
│   ├── 0fe8ab803b5c89e2296a80e7168edc3c66e63699.nq.gz
│   ├── 148979b48d10caab424ee4af53a7e9f9d95e0077.nq.gz
│   ├── 169e0879aef61f462daa40759beb472d4cfe2fcd.nq.gz
│   ├── 1d92a6d5c7b0e86e41c3a08c7dc9fd163eda7c47.nq.gz
│   ├── 212eb2c2d0d2dbcaf6c1dc82a315c63324767955.nq.gz
│   ├── 21d572f83dd4d500d125e2f2214902ac43574aee.nq.gz
│   ├── 25771811b9bb0f13ed9bf5df1e5d0273c56866a4.nq.gz
│   ├── 27575371c7e418e8484e5aee1567dc66242f1e40.nq.gz
│   ├── 29467b98f3c2d8a18fe32fc36032a92cd7aff863.nq.gz
│   ├── 2cd04d274fda36c330dbf627c2889755238dab35.nq.gz
│   ├── 2d6ea6fd723304244fa3e478cf598c3f24e489d5.nq.gz
│   ├── 35b147011d2edd85a298af9026227bcca5de6d13.nq.gz
│   ├── 35f72c9ce36c43ef946cadb1684acf7328364d90.nq.gz
│   ├── 37e6909033fbe2a5e57898df079132a89533eba7.nq.gz
│   ├── 394c910ba06b62e4b2035b711a4534f41d6fff0e.nq.gz
│   ├── 4062f6e01a47eb80f93cd9a77c053e6eae73934b.nq.gz
│   ├── 40a5d3ed4e7c64fd9a0fb915ab1d80d4e84e3796.nq.gz
│   ├── 411867662e2e6253c2093aa48fdac8ee21c1dce2.nq.gz
│   ├── 432ee0dc8f7713e155bd5dcba78d489bd4aa1e3b.nq.gz
│   ├── 450d4fe9e6e3e96a3098a2a6adf05857d8592478.nq.gz
│   ├── 4b8bab3acf80de182bae72c0e0a5174700a29f97.nq.gz
│   ├── 50a84f1d5dce62fbd567457cb50ba263aeecee93.nq.gz
│   ├── 52f40ed5788e9d450e513f4ff7d5d8d623e2e32a.nq.gz
│   ├── 57d7061fcf300ba2633bfa4b61f2e88b240a4eca.nq.gz
│   ├── 5e0d89e4a3b5fd3253df71a5cc32844e83213af8.nq.gz
│   ├── 5ec670e36cf578f8d59f8675e3451dfecd8b78a5.nq.gz
│   ├── 5eca5070f3ea3bb8fe97040748efbd63d24e1d4e.nq.gz
│   ├── 5febb28ef73e790aab0d46fe0138b82c19ecdab2.nq.gz
│   ├── 6061b9dcbbd342995451216f0fedf50e43ba234b.nq.gz
│   ├── 63942adfa75c1d3bc8317dc934105e257a62f47f.nq.gz
│   ├── 65b5e1f439699b9f4dfe1be1252791dac6491034.nq.gz
│   ├── 668a35cad7723b4a0812b342c5cd6ae2e2355b82.nq.gz
│   ├── 66aa3d0133664e05215c3d546ced6855b0d01002.nq.gz
│   ├── 69448a6b411b594fa8e07736f152cb573bc0ccef.nq.gz
│   ├── 6955c0c471de39420005740eb54bdea249a95c57.nq.gz
│   ├── 6cad8fcf5766da39eee2aada767ec47b1b0b329e.nq.gz
│   ├── 6e982c86491b30afff37b8b80151421a6f4099b6.nq.gz
│   ├── 6f09158f424a97b5012a92db298a2f4b2da97746.nq.gz
│   ├── 6f1225598a99c52ba2dbea5eb9530f1c3006beca.nq.gz
│   ├── 79453a71866d3bd9684aec2a13fcb160d55db044.nq.gz
│   ├── 79d90bd349c96653c38c408dd77f1b5263cf60d2.nq.gz
│   ├── 79f0c092ec19f6d0640953c932f4596c7f19334a.nq.gz
│   ├── 7a7a55c8730167147b100202dbd14f07486803ac.nq.gz
│   ├── 7fd3111e651908e994e419348f392dd0d186260a.nq.gz
│   ├── 809bf938f95816330080840e9c649777a2ab0a8e.nq.gz
│   ├── 8118055b71bfc5fbe915079b4e98877369f0bd89.nq.gz
│   ├── 8153f3b1dfa895ae91cf4a0bdbea597f0a75243f.nq.gz
│   ├── 831f161d31369f501cac4a5cde1836519c55eb15.nq.gz
│   ├── 8bd2e18141ab76c910caf3561753412759e24121.nq.gz
│   ├── 8c20b4fc8631a12ff0fb1cbbb421efbb797e4fa5.nq.gz
│   ├── 8d6c259281525d0a922f980093ba7d4656bfa21a.nq.gz
│   ├── 9037073500b7f792ad38ff1ff93a3cc5256c684e.nq.gz
│   ├── 9460ac55d4444173decdfda33e8f2f41a97513ff.nq.gz
│   ├── 9620541e0c5bb8ab3e9e9013cc93d1bf9f9855e8.nq.gz
│   ├── 965664258705ba80fa74f3b17aab8fdf0e72195b.nq.gz
│   ├── 975a5a0f909d617a27b46ada7802850bf8a3ebea.nq.gz
│   ├── 99e3041b47b2f9748e1f38213577282e4c67c46d.nq.gz
│   ├── 9c19d076267ce3f5c1170e881daf8748936485f9.nq.gz
│   ├── 9c5938ed3aec491370e84970709f75bc43cc1827.nq.gz
│   ├── 9db69920b8eae199f870fee1a8d2de0f345c9b08.nq.gz
│   ├── a0b4e9c2b99e5fb5dcc116858ef4804157825862.nq.gz
│   ├── a17893ba8518c6c34705e68bbe5d76737c4e600f.nq.gz
│   ├── a1db11b4473e8b18a759680bb9f92fcf0f9699a6.nq.gz
│   ├── a36bbf3e9af6c872578fec41faaef53ff84fd411.nq.gz
│   ├── a3fa4a35c12121639105b3b1b2572bb856ce9108.nq.gz
│   ├── a42faecadde8f0e94985821a575e9a87fa1341bd.nq.gz
│   ├── a5c761d39fdaeb9786dc49b90ed6951789a06ae6.nq.gz
│   ├── a63d6bff88d817bee17f2ceb1dbcb91c028167d7.nq.gz
│   ├── a7708e33585ce84a90afa5fa36ee70606c11a4b3.nq.gz
│   ├── a963ee0e603b0fc5ee0b507d81d5c25e96580441.nq.gz
│   ├── ac51e2410c622b57aa31923bf8301379c7ccb585.nq.gz
│   ├── ae18839148e9a0b740d871b2737a0105de8c162a.nq.gz
│   ├── af5222bc854ba7815832c55566974bd52ea55455.nq.gz
│   ├── af9763129e9ec5b5488352ab44f5628383008cbc.nq.gz
│   ├── b0f5eddd8d5e9eb03e60c3a0f8a10716d5ae515e.nq.gz
│   ├── b2fdd994d602fc5b9f512ed72c4eb400c75f4946.nq.gz
│   ├── b404ce297dadcfd525f27fb1a0fd0a5d2644b8b9.nq.gz
│   ├── b476a33b5c66ef4c1e0bd0321cbe67602bb49c06.nq.gz
│   ├── b6fa7e1a595fba34471351b4abd695dbaf00c7ba.nq.gz
│   ├── bb0c72aa45a5c376ba71bd602eaaa3b470965644.nq.gz
│   ├── c2a303fef44febecce92b532a9c0a644fde79544.nq.gz
│   ├── c372e709c0ef5cde5ac2844cdb6c0fec600d1789.nq.gz
│   ├── c88aeda2f6b96b636a3308d5fef3c7c5dccd5fca.nq.gz
│   ├── d111218d2fb159793ce9c95f4f7dbe90ae3e10ca.nq.gz
│   ├── d174376dbbf9ee1dd69a68fe8288aa4d6d7cba5c.nq.gz
│   ├── d331c4d525dc54b7c117de02c49dc7ec6788544c.nq.gz
│   ├── d4479b5daea02e1abffad7276dd855867ceb4751.nq.gz
│   ├── dc8efd627fd3a1b87690121530d80ffd7858852e.nq.gz
│   ├── dd190a4df7490d32fa85d3c83b2b4340ebf85bf9.nq.gz
│   ├── dd4b68e2f1eee6cfc04e70b1d6f7a95dd4274db1.nq.gz
│   ├── df1f8d40b1c5481dd7e20a6f1ee1976a54949533.nq.gz
│   ├── e13d0ef9c264b8fbbefa9a395b1906dd200305bb.nq.gz
│   ├── e1482ffb8573624fabb69df3fa4bcb727f420cdc.nq.gz
│   ├── e55ba49df1e2b7bdcf4201ba70167ad5151c97f7.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e711ec5efca8e32a9031b537b7a3f037c7f79d8f.nq.gz
│   ├── e9a8ea251de61f2bcee3987f196792eacd17e648.nq.gz
│   ├── eb1ef8fcb9b16b6094a84eb1b3852df7efd8c26f.nq.gz
│   ├── ebcf236cb8c3c5055414589b8f5821ea61143168.nq.gz
│   ├── ed41385a2fe6d958ae24fb487f7b034544cb80b0.nq.gz
│   ├── f168fd5ff5a97b2dba82ce7a38444d557ba7bce6.nq.gz
│   ├── f1b36330b3c6a3cf49987a52f5847ed9494fdeae.nq.gz
│   ├── f22701f53b3c062dbed1230bbbc8e906d44246d5.nq.gz
│   ├── f2c18d5c91f93352451fb29637894d8865ffbf16.nq.gz
│   ├── f7e40b9e9cf962df2a253a696690717737f799b6.nq.gz
│   ├── f83d66f2856678943ffc70249bba5e15a2ffdae4.nq.gz
│   ├── fab465f6e87ae23aad0cbd7412916932d9f5d881.nq.gz
│   └── febcde0e9e6a0d59f2fe0e8a8b1d6572388b8010.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 370556a75a2b427e326bc98cef14059514df8d61.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 123 files
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

[pylint-dev/pylint-django](https://github.com/pylint-dev/pylint-django)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
