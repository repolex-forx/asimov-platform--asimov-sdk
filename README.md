# Repolex Knowledge Graph of asimov-platform/asimov-sdk

RDF knowledge graph data for [asimov-platform/asimov-sdk](https://github.com/asimov-platform/asimov-sdk), parsed by [repolex](https://repolex.ai).

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
rlex download asimov-platform/asimov-sdk
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── df76fd18d73735b0a74924ceea9184e2e991bd5a
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── df76fd18d73735b0a74924ceea9184e2e991bd5a.nq.gz
│   └── repolex
│       └── df76fd18d73735b0a74924ceea9184e2e991bd5a
│           └── chunk-001.nq.gz
└── blob
    ├── 007367b89029fe420177c5b70b8ab4502a7266e4.nq.gz
    ├── 00b869260711524a6f144d6a1c23d2e40d3a5e05.nq.gz
    ├── 00bccaaf03bf1b3f88796f03e7d5a56c915f89eb.nq.gz
    ├── 00d217c2ae1a2110ef836a60d8b91f5db95abef6.nq.gz
    ├── 01e3b8dcfe2bc0a928711a1bc9302d42c647cef7.nq.gz
    ├── 047d4bad9859e5eabfc5aa60cb18cfce8ca72163.nq.gz
    ├── 05ca93749da41e7f6bea59f7b09da5913a11079f.nq.gz
    ├── 05e77e6194e68754701a70786233e850c72f26a9.nq.gz
    ├── 067a1061042ab7ae69f4197740c5817804375431.nq.gz
    ├── 0725244c5d20e71a1ee602168fc7eb69828c751b.nq.gz
    ├── 0774e1623e043c388c289c0ff53655e3678e5849.nq.gz
    ├── 07d4b94c8dffdd625c5728b3c3764f4b4292c8d4.nq.gz
    ├── 09b1bd00e45f7ac018669a1ca547bb3a6ac9963b.nq.gz
    ├── 0a0f31cad24c96ae80d68a4c8e6cd55034ea19f0.nq.gz
    ├── 0b0b86f66ee00a23765815e7301e15c822708809.nq.gz
    ├── 0e31b1d8f542d11b768ee828e3648def03a84ba0.nq.gz
    ├── 0e613e603dccbc570dccf3d25fcf883b6a1ad5ff.nq.gz
    ├── 0e6a39ce13f538bfb9fba7a56904a2131805eb26.nq.gz
    ├── 0e83bed0653027ef848dd91f467de5cb57bc62a8.nq.gz
    ├── 0f177a2114d7b0bb5f350ea144601bea5c598d6f.nq.gz
    ├── 0f5f231a613e2732b5d6d8099dac53aec79bdc88.nq.gz
    ├── 0fa06763621ba591fe0c7b2b1b822cd78e54a3b7.nq.gz
    ├── 0fc8902b4c674d31e50223f275f497926986415f.nq.gz
    ├── 0ff4f7c140c2a8ab93e0b6262ecd9671e7d5d0a9.nq.gz
    ├── 101824b4237e21153a3682e36cd1265f4ea776e1.nq.gz
    ├── 105a2c784da70beae489b5f23c1567f70c3fe3b7.nq.gz
    ├── 1209c020369d94f775d029637ff838705d5e8f68.nq.gz
    ├── 1297863bb14ad15e4dfd5c5eeb2c321360fda2db.nq.gz
    ├── 135a5f244549803fcd2b509a0309455d4016fbe0.nq.gz
    ├── 14ca0312bd09144d575c8cc07c7735a534282386.nq.gz
    ├── 1539b18c3a3c4a628814617d3f0852fb79bcbbd7.nq.gz
    ├── 166472c973523606d881cfed52c3c4f76d8bfc13.nq.gz
    ├── 1727b16a30aea7cbac54fc6afa32e9925963fc22.nq.gz
    ├── 1764920c75a7b8c1b95f0be1ab5e7fe216f2f698.nq.gz
    ├── 19c30020de84b946a0f3fdbf355dcd6c0179292f.nq.gz
    ├── 1a05a5015e5ad045b68eacc5b7067544e3f95479.nq.gz
    ├── 1b201d42442cde65f679575122b868b04b8ecbfc.nq.gz
    ├── 1b2fe6b575517a06baf09590c5393ebd59f3d0e8.nq.gz
    ├── 1b5040b1c8c54b922f1d68918efe96f184ffe9d2.nq.gz
    ├── 1bb3d7f6fe74cc834ad0877f6faa262634073881.nq.gz
    ├── 1d5aae0260253d0b55640e85f28e580906c1b57e.nq.gz
    ├── 1df37594fad8e2907a915ed41c962479bb42d3e6.nq.gz
    ├── 1e9243b8da650803cd132e1cf68fb2833408f288.nq.gz
    ├── 1f07f126b7a7a86c8c9cffecd3a40c346e372f1f.nq.gz
    ├── 1f14f46d3565d45afef1e10d4c2a4e58fa3ba8ec.nq.gz
    ├── 1fa6686abaa6d73537c3644897e2923274fb1555.nq.gz
    ├── 1fb704c277158b27d806ac7af91459f162b4d4d6.nq.gz
    ├── 20c65d2c23fa84fe69d82c33f8393db2108dd172.nq.gz
    ├── 215eac234415177a2050c79b1a6541571919cbf6.nq.gz
    ├── 215ee53dfca0a081abdb43ca1f61f9da01e6f434.nq.gz
    ├── 217af53159de48e6dfa58137c4e976e23719d1e3.nq.gz
    ├── 21805093a02c7628b60b98b290a8defc538e0c99.nq.gz
    ├── 22fb82b51c0ef6d1ce8553438efda15f4098e63b.nq.gz
    ├── 25efffef74149f1dffd8e04cf7c73df2b080ac3f.nq.gz
    ├── 27ac1fa4e9485dfa83554a9a7651f48d88315d28.nq.gz
    ├── 2877eee23747ad779c66630ee31ba2e18148310c.nq.gz
    ├── 2a0a42e49edcdd760597be464a2e8539ae971230.nq.gz
    ├── 2a4970a593368b56676139dbeffa54063c2ea55c.nq.gz
    ├── 2d8c0fc792d3eab554ecca0ce79e825cbb856564.nq.gz
    ├── 2dbefb4b2b3806ca66ef6265b20fc47f24c65a2e.nq.gz
    ├── 2e43bfb1ba16e17758faebe4547af304f0ba23b2.nq.gz
    ├── 2edee43d7d572a9f72d860f51b357f0dacf98e5a.nq.gz
    ├── 2f705cd8d9fc73667480c4b72852c0ed07863fb3.nq.gz
    ├── 2fcbd237a7d37fe6f511a67f19dae15ce8e8b4d8.nq.gz
    ├── 316285554ee0fa61d05744407e7e2ca2031e4840.nq.gz
    ├── 3164c8d5e0976897c241ede15c8d60ff43f142c3.nq.gz
    ├── 31dfd44f19182f37154e3d6167db01af8aeaa4c7.nq.gz
    ├── 33a0c0c0a4f99cdd13951fe499647f43db83e6b3.nq.gz
    ├── 34183352508fac590a93e18e222c56db994ee3a1.nq.gz
    ├── 34ff59705fba92746a6927db6f9060949e4a6d56.nq.gz
    ├── 36aafc2f00fc3ad9eacc417f304f1cfa7498f4c6.nq.gz
    ├── 379445eb47f9d4e7ebdf42bcacfa25b49b83eb1d.nq.gz
    ├── 37eb99dbb8828a9f31a4c28f54cf7356b751d854.nq.gz
    ├── 383a69a497bfa1ba84782df5a2c7c107f85bd96d.nq.gz
    ├── 387c777b397b9ad2fb800045d8a9b0074cc82c6d.nq.gz
    ├── 3989e3b2687724785835d814883dd0de5981d055.nq.gz
    ├── 3b0fab355197f381c2a0770d660f94bc845dbdcb.nq.gz
    ├── 3c0e5c272eb9b7968c52a10c9f8361aade8ad8f8.nq.gz
    ├── 3c9b3e1d808aa7efc4e22f61379d3eac1f5142f2.nq.gz
    ├── 3cceda55789681d7da9a91f3915a58444628a21f.nq.gz
    ├── 3dd2ef58288336d6821259515a4e4f933fa74c75.nq.gz
    ├── 3dfa15dba641f385f1bc98397905d8b844167f38.nq.gz
    ├── 409ea5f1f2ed206ca843c9fbb31e2ce2791cd07d.nq.gz
    ├── 40f649db2036adfd07e6e709c4cbc68c4b293f7a.nq.gz
    ├── 425a66875b32df8355571e93f3e19f2819882dcc.nq.gz
    ├── 4282c3a4a39dddf691784584deb1e6903da014af.nq.gz
    ├── 42cdbf8f5a8c9fc8ee57c0e9c4b211558ba1c8a1.nq.gz
    ├── 42f3fdd98570c00c7b9f50c4dc580860d7b092ec.nq.gz
    ├── 42fc8401b75ec80ae4b8112dfadd439dabbbd623.nq.gz
    ├── 43211f252a230e7d380e3542abeedb4e7a6a9184.nq.gz
    ├── 452fafff53d944f42fc08ba4419ad323997c8747.nq.gz
    ├── 4549d70ccb1516e210f0652544bc0430f7e03f7f.nq.gz
    ├── 462612df7d43a14a733d9bdea194c70f32ba6cf4.nq.gz
    ├── 46c6f0d610d1aac6b1997f4ad2dbfd41f3dd9a03.nq.gz
    ├── 49514ef2969ce16e9d14c124aa94094541c3e2c1.nq.gz
    ├── 4962dce0c6fd6ce43d20e2346fd3d37532a215aa.nq.gz
    ├── 49fb7281edef3e54a2d14bf4eaf8a3ac5cbceac4.nq.gz
    ├── 4b465a879a60462e8578f1210c1fba26d51ca9db.nq.gz
    ├── 4b6f1ea1cb461d30909702b144d8220e9346b9b5.nq.gz
    ├── 4bc675ffc82139e2bb3498ed2fa0bd55103b2154.nq.gz
    ├── 4bdcc1ee023e3fcfb4b5924b970f6b50cce917fc.nq.gz
    ├── 4d656e6077e77350b689f205834690e56e01e7f1.nq.gz
    ├── 4db37209e7d92140de1860f2513625f81ac5b9ce.nq.gz
    ├── 4e296190e34165406d4e8d5fece6299135e9e2e3.nq.gz
    ├── 4fa757dc25ab5ea6bd74d3996497893e482a6f90.nq.gz
    ├── 50570d8c2fc1d84660cd6b6b98b6bfd293f8f9cb.nq.gz
    ├── 5259b9ec0f73ad89626fddefa938ce9dc4a2395c.nq.gz
    ├── 52a019a8e5124a2829b3416395a7372bd7c7a79b.nq.gz
    ├── 52cf0cc83961e0b83eaf2e77aadb55a4ec0419e0.nq.gz
    ├── 53c71d694f21e0875715c92b257232ee9408d1ab.nq.gz
    ├── 55b0641cf46e8a1c8c1aba27c3567b737d53b696.nq.gz
    ├── 56735dcb90d4fc7fbeed0a7509f97fd60256a073.nq.gz
    ├── 575949da4438f16d509b25f97b35fd6fd2a34ae0.nq.gz
    ├── 58d5b36ee2196be6d17ac6c75094bc512d60e6df.nq.gz
    ├── 5976f506cc2c8f37ffecbb1d5b22b2b7041589f4.nq.gz
    ├── 5991526fc2e1f612c1ceb156eb669b55cff89803.nq.gz
    ├── 5a0297a5c2943f181640cf0ba78f315cad12eecf.nq.gz
    ├── 5ab6ca464ac9b11b6b6ea84c867c5237eae1283a.nq.gz
    ├── 5b57a0a4141a3dbd4f10321768a9b8c72121420a.nq.gz
    ├── 5b61a30d39e43f371d753de0e43b731fcea9f2ee.nq.gz
    ├── 5b867fd34e00f75f25a7e6cead1ec70964e9b207.nq.gz
    ├── 5b8a0be91ee00668187d78bacd45cc63a0b61eb6.nq.gz
    ├── 5beb2f1af47a42b60ae085a799c0122919ca6704.nq.gz
    ├── 5c432d053a470a86971e24543e6cdd06d19865a2.nq.gz
    ├── 5da36792249b6bb021652087f2ee7e048aef4806.nq.gz
    ├── 604f76c49f7e8ac69268a97623d4bd65aead53c3.nq.gz
    ├── 60dc7ed9eb2b93dfe003acfa5198cad8906c0f20.nq.gz
    ├── 60e058cf18802955227e209da8e8b07952765de0.nq.gz
    ├── 615a1ae740c41755061e3e8fde2457ac5f2b173e.nq.gz
    ├── 62522369370d762f5c4419e829cf5f6d3b040802.nq.gz
    ├── 63071095946e08218b06dc8af4ad7ce0bb07e345.nq.gz
    ├── 6324d401a069f4020efcf0ff07442724b52f47c2.nq.gz
    ├── 64c894b57230e1a7e416b25eb1c6a02b4a2a2ccc.nq.gz
    ├── 65b57ffe84b4d3484aa99cb1d3e3992a48c8d2fd.nq.gz
    ├── 6747d089ea41500122de29d702affaa8a96af378.nq.gz
    ├── 683d69ef78c75e2758e83c1347bb11920b56d058.nq.gz
    ├── 69a191b4809b04fe087ed94ff2e78f6b0ecf85cf.nq.gz
    ├── 69e66fca06df02aa72315dbf86a1d7149563c687.nq.gz
    ├── 6a2758576b9df91864d90cbb1d5f0eaae6787fe3.nq.gz
    ├── 6b6524c91a212b395d1052cce6e8035a7335ab7e.nq.gz
    ├── 6bdd7698d92b8ef51f4a12bd6811cf473efc67b4.nq.gz
    ├── 6c9a3ff477fb327a1995c6bf6da36b9d7e0b8de8.nq.gz
    ├── 6f0850f843cd63bcda8920cb901b21cb6f4d89ae.nq.gz
    ├── 6f4bbf5bc4eee63a31cec7074b4c2f922bd85161.nq.gz
    ├── 6f592630d5ab7c42408a0b6a18f221d220ad7421.nq.gz
    ├── 6fb4278cd8948d54581800eab298fa11a10cd636.nq.gz
    ├── 6ff19de4b804f2eca2b2d72657dd908c216b6537.nq.gz
    ├── 701576bea54bf740fccbd6b8d8e0ae014f3d0908.nq.gz
    ├── 7032bbed202c6f02043fabc457437d743fbbb50a.nq.gz
    ├── 70edec7f6f0de9dd110695229c80453f879a01e9.nq.gz
    ├── 71c9d11edb505c0c56ef539cd57caf36ad34ea72.nq.gz
    ├── 73c34c75c66a3736af1d81cb1a6938b0b0d8fa08.nq.gz
    ├── 749e216de9b6b25be3b602aa0bda66fb767e8d2f.nq.gz
    ├── 74b0c6629270897a57ee4a47b5efbab0301f3b33.nq.gz
    ├── 74b2075e05f8f488975e33abee9fd4d5fc041bbe.nq.gz
    ├── 75f197681cfc42def60e852e6d5c70a77445850b.nq.gz
    ├── 7672d8e6c4dbc090de243d9972610f59d0ad0c3f.nq.gz
    ├── 7770d778c8ab49098e6dde306582e5545dc887ec.nq.gz
    ├── 778ab49f840f933e976bcf010f25b1820833ffb4.nq.gz
    ├── 77de3a03de6371683739739bd6cf1e9e87a4e3b5.nq.gz
    ├── 787614feca7bbdbfc94a187fa17bce79d1221d2a.nq.gz
    ├── 798788c80096ec025ccaadab12aa37e18556f0d6.nq.gz
    ├── 7a97d7ca175c403d89ed2f8ace6ed9b05b30e2b7.nq.gz
    ├── 7abab218956673aa55f7e26cf102967986682770.nq.gz
    ├── 7ad770e64492b8822741fa582cd531e8d7cd6a22.nq.gz
    ├── 7b3357dcd01bfefd36069570d2783d3624639104.nq.gz
    ├── 7b3f8896b829c68644a36c454e2840e4b28c61df.nq.gz
    ├── 7b42ebf1028cd92cac0503cc937c874e2e1bb869.nq.gz
    ├── 7b760bda64a6a123a4861eb2ab788e24e5d82b1a.nq.gz
    ├── 7ecceb596809bf61db2947e3924002d730b4d054.nq.gz
    ├── 7f173cef74b60e6c75d18d43f991a7e29df27a03.nq.gz
    ├── 8060097ec418de858fd28d9a991ba2bc013061fc.nq.gz
    ├── 81717600f0ad1963b5c1089fe7bb929dd822ae45.nq.gz
    ├── 817d983de4e13e8ca7bfa03066c89c94af421bde.nq.gz
    ├── 8216ad972d66a6f509e775f479c51108553d7784.nq.gz
    ├── 83fe1fd801c623953a9e64e66a7548b88bd1304b.nq.gz
    ├── 84a1291f45e5150b6cfd94ed04fc87ab3eee8ef3.nq.gz
    ├── 84a3c99c9445e3610ecf44625e9a809b52f4e450.nq.gz
    ├── 852b86efe1c0c195231d27fe0e74fafc1c52fb01.nq.gz
    ├── 87d883981d978b6e8c8d66d3e12b3e579a174ee4.nq.gz
    ├── 884954d1ff6f6c89e76cf1ac03ab3d8adbee3410.nq.gz
    ├── 896777229c11a3290a3a6df0fc3b6b0194ece890.nq.gz
    ├── 897ed62f4fd1315311227347d95957d5f870a48d.nq.gz
    ├── 8b2da0a438fd154a7d03afff425c2b37af2a82db.nq.gz
    ├── 8c1ad740e05ddad068ee0f592af9ad73edc0c86a.nq.gz
    ├── 8c203ea9855d2f2dbc4626b9581e0bd4045c1ecf.nq.gz
    ├── 8d47ae34c21b6cab40f031cda6b66cbbb4c8c199.nq.gz
    ├── 8deefba158183bbd7f7ddf9e076c224977283739.nq.gz
    ├── 8e24be639c7fc02f90fccc9bd6bdef13a877cdb6.nq.gz
    ├── 8eadf91840a8e9ab9591f3a8d4d74f472f0cdea7.nq.gz
    ├── 8f72f374ab06ec8081d8a7ce7e59cd36f9a2f216.nq.gz
    ├── 8ff21f37c372c768cf91caf69ba5114092182178.nq.gz
    ├── 9001a102c2ba83713de5576b75bb4b505f643fb2.nq.gz
    ├── 9075b8b07f06b1df8174c36357727654f2995383.nq.gz
    ├── 90ef013470736057b0485665d7048e0800e21d62.nq.gz
    ├── 916f885264145f3678c5a060c2ce4fc8d9721d6a.nq.gz
    └── 916fb4d569458aa33f754d8569760e3bd3d69a5c.nq.gz

8 directories, 200 files
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

[asimov-platform/asimov-sdk](https://github.com/asimov-platform/asimov-sdk)

---
*Parsed on 2026-09-27 by [repolex](https://repolex.ai)*
