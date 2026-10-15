# Repolex Knowledge Graph of twisted/nevow

RDF knowledge graph data for [twisted/nevow](https://github.com/twisted/nevow), parsed by [repolex](https://repolex.ai).

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
rlex download twisted/nevow
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── aff713a6884a0ebf2214af5cfa3c1ea2d7d70669
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── aff713a6884a0ebf2214af5cfa3c1ea2d7d70669
│           └── chunk-001.nq.gz
└── blob
    ├── 00e5c674c6bb8f1bab685575bdb2e1640f07f295.nq.gz
    ├── 01f4a8e89499c56ce8e4b40d1e050c85fc579222.nq.gz
    ├── 021331f0e846b57fe5eefccd67431aa57ddeead7.nq.gz
    ├── 026d108ce9826015502c2fe0e55d6432dcfb432d.nq.gz
    ├── 04c8ebc674f865c2939867088f95f26cdedda054.nq.gz
    ├── 053cdc1ff915f0eec40e179e81afc1475d8d48c6.nq.gz
    ├── 059e0f450521da36cb63c0b8fe990f3e468a744c.nq.gz
    ├── 063c0757dacf6d2475dcb3a7a570177b5ed40da1.nq.gz
    ├── 07244c03773a6a117b49047ff4fa19069d8d597e.nq.gz
    ├── 0749e332a0b39c3abe01aaf2be0b7d092147c9cc.nq.gz
    ├── 07c3280bb1660b601aae8d7f84971ad5c91e3558.nq.gz
    ├── 08475ab3ab8ffe86f6d419809ed4487002729844.nq.gz
    ├── 0901f2be34357121def0ebb32615809d28870ef5.nq.gz
    ├── 091aa7dc49edc16c629edf1c1eca12288fb7ce2f.nq.gz
    ├── 09572b57984f54a7b6e91d171e8e304876a3ccdf.nq.gz
    ├── 0ab33d9fbf7fbc566b8b4808e768013bc210afda.nq.gz
    ├── 0b39c36726668adc9c122472416374f4e3d90468.nq.gz
    ├── 0bb4b5a4aecb253ebd23ff57d626fdb86739d989.nq.gz
    ├── 0c3c03723e4ad80aa65a27aea6f9ccc2fb9744f6.nq.gz
    ├── 0c51167ac26755b5ba271768040b04c0e6118e2e.nq.gz
    ├── 0e008429b785c9ab7a98db5d2df059b9e5f75d15.nq.gz
    ├── 0fc3252baff8174b1fdfe5fe75f293a3a9c6fed9.nq.gz
    ├── 10e807f50a4be29e54359f69533008062dbaa390.nq.gz
    ├── 113fbf6df4ded406c635316ef57d370fe7782cdb.nq.gz
    ├── 120dc98d4a6b45fd3cbfcf34c1fbf0bc77648ab6.nq.gz
    ├── 123dec6608f39a7c869ec0646d85a11c5756d670.nq.gz
    ├── 12512086e7f921eaa78a20c468c0a16ff51ed7af.nq.gz
    ├── 12fb98cce68245fe2aea54bf2e96491660df7411.nq.gz
    ├── 13c0ecdb2a49121a45ece4d593131966a8cf98e9.nq.gz
    ├── 146acbf9adc08b25f1c801bc4d2dea6d9e238640.nq.gz
    ├── 16e681e34a4c4947885357d074523c4de2fd8eb9.nq.gz
    ├── 195f00e53255014c98ca6dba74b68df2a2efe0c3.nq.gz
    ├── 19e2acaba26a08c51d420ae6fa2c7cb01533a5f5.nq.gz
    ├── 1a30e581eb48676fc687fbe304f3177148960ed0.nq.gz
    ├── 1aeaa505ad3d892d9a9e10623871c414bb91b08d.nq.gz
    ├── 1b862321ac79232adfb509e8831b1da2e03088c6.nq.gz
    ├── 1c2bf165335c159012d35da21c1793b566b09b91.nq.gz
    ├── 1c49528da610c932ac9f2acf464f4904887a33e0.nq.gz
    ├── 1c65b145b94979e253514b51fc233b177684e02c.nq.gz
    ├── 1c73db4d934f16d70b1befb55dbfb66a2b9433f9.nq.gz
    ├── 1c986b228d37eee7ffc3da7638d392714ab69085.nq.gz
    ├── 1ce9ce8357743282ba6a5b79bf5695a5af277469.nq.gz
    ├── 1d270fd9afa9ec4accc42fa1099e2af79915cde9.nq.gz
    ├── 1f046cdb74747ef1d4f0d4dcafd8806c713f4baf.nq.gz
    ├── 1f53798bb4fe33c86020be7f10c44f29486fd190.nq.gz
    ├── 21801786ed8acbc068d27172dc51477de2f08a3e.nq.gz
    ├── 21c90b02a4c0bcc16c02fb9306c49e122cb2a615.nq.gz
    ├── 21d1fdbe378afe90aa4032e9c5a410b2c4587250.nq.gz
    ├── 22438f8b50914488c93be3e4eec65eea444d562c.nq.gz
    ├── 22bf77708c80e18175977a0819ac223c3802c455.nq.gz
    ├── 23bd662b9a3eb375e42e2d29937173d16f08ae0d.nq.gz
    ├── 266580d495c7ff378a8e22d813d05c33d0b34081.nq.gz
    ├── 2a21ab7a5b9fc32ef16522a43c146696e7df949a.nq.gz
    ├── 2a991ce83412024f1ac60989ab93bc10de733ffe.nq.gz
    ├── 2aed6d540976d997fdde0e2f7078ffd264da5d65.nq.gz
    ├── 2bed42868b23606e1d656288440814644228595d.nq.gz
    ├── 2d32e0edc4ffb913fa8e78c615b8966077a7745a.nq.gz
    ├── 2e1b2821862f707b98a599c5e1070932707760b5.nq.gz
    ├── 2e2b6461499cdfc3f41f15e1930f596e8301e0dd.nq.gz
    ├── 2e4dd31b2dd9e385f671975a22d26bb7b221afa2.nq.gz
    ├── 2f24bb3e8c518553d91964714305ed05c39947b1.nq.gz
    ├── 30202d928d1cace35af544958a44180dd3a77e89.nq.gz
    ├── 31b4e75ff213880dc498a9953c8ecde100dd37d8.nq.gz
    ├── 32842030c089c1708931b166e339a9ad3fc4a800.nq.gz
    ├── 3293ffa7963600974ed0dfe8f2e02309086de509.nq.gz
    ├── 32c6877db722ab756e16338a1a04b2c5a87abbb2.nq.gz
    ├── 33e06b0bd65288cf223b4b6f13b392b07e42eb13.nq.gz
    ├── 33f577d1ca82d167f3d24fd438a905207bc84050.nq.gz
    ├── 348c69d2863a1a61569fbfa2c87f5d554c2f1c42.nq.gz
    ├── 34d7f9d811db0edd9add57e2f52a82bf6df28a29.nq.gz
    ├── 36989d060dbf96cb45e932619c3c3a02dab3ec6a.nq.gz
    ├── 385b433200dc22598c868586549a00a89f43fa5b.nq.gz
    ├── 393d266ba1eef8f001f4020d08e8295a29c8e206.nq.gz
    ├── 39be16e88ed51fb4f2c3ca7a5f26b412c01886ff.nq.gz
    ├── 3a472174727658f3517e473b37807e6932c15b98.nq.gz
    ├── 3af87ab4dd188c7c82ee08ee2f6b65789fc93887.nq.gz
    ├── 3b00e45f82855f66891ff56f6327b0bd5b5c303f.nq.gz
    ├── 3b69708afb7b536e262d01ed0732a529275f69f0.nq.gz
    ├── 3b812556c544b9508421d46e6b9ec82d2779b5f6.nq.gz
    ├── 3bba7522b6ba679365779099c25fa759ead23610.nq.gz
    ├── 3bf9b038d6e29a08f6cbb441a78fa48dde2079d5.nq.gz
    ├── 3cca51c89c92cb5b877d2c0cc7dca0e92df3e3d0.nq.gz
    ├── 3e32715926603ab4ce651990dac06528bc7458c1.nq.gz
    ├── 3e8fd8704f1d49c47e9db7241f64305855d3cfe1.nq.gz
    ├── 3f5a2bb8b5d739cf5ee8dbba3c816aa83fc25a19.nq.gz
    ├── 401e768562df076e4ad63e4ff521d7a3733e55ef.nq.gz
    ├── 4029201f825657f6a87c4f463f7a368d5f6a2a1a.nq.gz
    ├── 41be38556d7fd06e47c1c69b4982e2686e73d0df.nq.gz
    ├── 41d5e3f1b85e1f1632c4487d085971118b47c556.nq.gz
    ├── 4254f1f211438120715ab04e321e3921bcb1e222.nq.gz
    ├── 43649616cefb973e328fd4f099436b8d96c61492.nq.gz
    ├── 45ac0a7e7ecb64263e25e6299f385b118568bff1.nq.gz
    ├── 46697b4214e52d8d62e4f52b9cc47abbcbfa1b90.nq.gz
    ├── 47a03f89fcf443d9ae592738cb4cc8c9d3f6ea62.nq.gz
    ├── 47fc23821cf839e589aa9efab69d026263513f00.nq.gz
    ├── 485d9a99195db60f1c604512bfed89eeca22077f.nq.gz
    ├── 4b5b7df3a4ec7bccc07d88d47d815258dd3061b2.nq.gz
    ├── 4da18d49b9122cd364f9393408064949f4edc3ec.nq.gz
    ├── 4f42258557a88eab9cdde429f0d4449e5bffdcc5.nq.gz
    ├── 4f894e5e8e4f658a04f53cf15a32843ab55904ea.nq.gz
    ├── 50406e901a0db23453dcf2991596b42ec8ab5d6c.nq.gz
    ├── 50c0e388fece9d3162ee8d853bfecc6be64a99c3.nq.gz
    ├── 574f163a85dbdd6462886e27f3d02e67788d44d4.nq.gz
    ├── 58a1681fe285d720a80b5c37c88a0aada1de3bd7.nq.gz
    ├── 59ca9b71b74597eec726459d85d43c5e99a54434.nq.gz
    ├── 5a47fc071bdf0d66ed6ce5b0a19898aa07a83263.nq.gz
    ├── 5af804052860ae74416bf02641169abbf0e4aca7.nq.gz
    ├── 5d0e3dbbe663d7f1094f570bc49c9ca09d160e07.nq.gz
    ├── 5deff352deab1aa9173eeea2dfded1cec93ebf80.nq.gz
    ├── 5e027454139f3ab5a099f22d0f7872d706ce4618.nq.gz
    ├── 5e4f6e590fe3994b28640725f8c7e6844a0bcc3b.nq.gz
    ├── 5ed55e1786424a54ba68096e8f91a6755c66c608.nq.gz
    ├── 5efe93e2ce9cdd93627f21fad670de3c82a36343.nq.gz
    ├── 5f8d97b600632234120da2f5054a4bae3c281d9c.nq.gz
    ├── 617e2a0693ee186ed7f2d5cf7f11a3eb05bf318b.nq.gz
    ├── 61b69c2275aca30f68ec2ece5f6d22041e059d2d.nq.gz
    ├── 61d8300d845ba990ca28181b9c423e10d6b72bdd.nq.gz
    ├── 61f617e4fdf815815efeb170e27fdf7a075ef597.nq.gz
    ├── 623dde7863499b955f3635c78d25d708f0510e39.nq.gz
    ├── 63ca74be46dab7a668525f50f252633dba4cd64f.nq.gz
    ├── 63ecf79666772818b5f38dc24284f443bc80e1f1.nq.gz
    ├── 63ffdcaa783a550bc68447f727fbf722a12cbaee.nq.gz
    ├── 6461b555361522d4631009d087cf90c11e5f3b3c.nq.gz
    ├── 64bbb7b340a074280fcf22c3ad26d98d23fb809b.nq.gz
    ├── 64e142655c70c22c1063b1c8b8b0be9e06b2bb93.nq.gz
    ├── 65f7059c85177feb61e9e09e790cb1acd7e400c1.nq.gz
    ├── 6630aafdaa7aeeb66395b0f332ffb7b2aae1d27a.nq.gz
    ├── 6656c3640b76ae23f248f5dc53b1a07dd3977983.nq.gz
    ├── 66cd723be590649d2b4ef5e60d5bae07db595010.nq.gz
    ├── 66eef889ea782ff30870814f3e05813407925498.nq.gz
    ├── 6715ee8ab026a9ff4bef118652c53a822ed36a22.nq.gz
    ├── 673643e361f60d41414c6989c28ef09feba2bb69.nq.gz
    ├── 68b876cdfdd8211146d451d2b739ea6d5c5e95c0.nq.gz
    ├── 6a4b2e1b72bb9f4c8aac61ecdf75764c95772dcd.nq.gz
    ├── 6a96d2a4f53dd91526e8f13ecfe5a18a9a325129.nq.gz
    ├── 6c04c558efed29dfcd9a9e897e95d0cd970cc0c2.nq.gz
    ├── 6dda4d50dea47ba152ae1cbdf4925c2197ee428e.nq.gz
    ├── 70947d1bea87f66eab56fa4e0612bcde65344256.nq.gz
    ├── 70a6dda3eb93afc91819ea4b61820cf8bd7c611d.nq.gz
    ├── 718c0a9b45cb5e431c85dfcb36e80e81f3081170.nq.gz
    ├── 71e842ac931957a2260c7008fd5b6e617226a10d.nq.gz
    ├── 7316e4761e77fcb18c76c576c058e9208e36b847.nq.gz
    ├── 75a809bc4ae46e610e6e5330b69974915a59099a.nq.gz
    ├── 768583b1976b02689b016e36c8a4d08c67c4c3ac.nq.gz
    ├── 779ec338a5adfe00bbbdf7af1d2d78d5e42f2fde.nq.gz
    ├── 78e3a548f45b1a689bdd4ea0dab4ec636a111cd3.nq.gz
    ├── 79180ce385b894026fbf524f19ba6ef705fa4918.nq.gz
    ├── 799c99dea38c4cc326cc3edbeef28574e40a35e3.nq.gz
    ├── 7d0753d99a318977a90f623611090778941eeac6.nq.gz
    ├── 7d94702d5c531e0af128a15adfabee493f70c586.nq.gz
    ├── 7da99ce3b88068dc4410e67a101035d6d5f8f372.nq.gz
    ├── 7dbfbe02caa4dbe97377062e8138769be203e8d0.nq.gz
    ├── 7ec35303d6920286eaa0bcc8e3c7b86984927446.nq.gz
    ├── 7eebefc30eb4c448d1343bfc3aba992981f4e40a.nq.gz
    ├── 8019d86ce808da074dc68b7ef7c02cdd4d2681d5.nq.gz
    ├── 82336846574748734472cea154a26b13d07eb5c2.nq.gz
    ├── 8486bb300fe534792182c261362738ecf7a1872c.nq.gz
    ├── 859e2f97f462249fbc066e5c74cd36e2f56e1e6b.nq.gz
    ├── 863a80099af6c1de09ace75012f729857bc12931.nq.gz
    ├── 8669f9488248441658e6ee41c143aeb4daa2ffd4.nq.gz
    ├── 881ba2a46eb75062f89b3233b2cd1558b546f631.nq.gz
    ├── 887fc0c37b9a8b36d38f398021f3ba2a5fdc836c.nq.gz
    ├── 88eb68b42610e2c02997ff9ddbeeb9f518215642.nq.gz
    ├── 8a7960349e225a27084ad8a964afb661872a6e8c.nq.gz
    ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
    ├── 8c34f8ffc221c4ee84049eefc0495b9b9a53259c.nq.gz
    ├── 8cc1a930c776e3f1c7708ba252fce89273fd4856.nq.gz
    ├── 8d20556d5bab74243e7e7ab221a4761c98b94a98.nq.gz
    ├── 8d8c8ed350de57e997d8eff2a0b7f6d741d76add.nq.gz
    ├── 8e153e30e6022c1c53cce2411ef2293eaa15a4a7.nq.gz
    ├── 8e38831a35c3acab5e2570ef2aa6dc48f9ad3234.nq.gz
    ├── 8e5d9189bbe093e398b891263d99125078b66933.nq.gz
    ├── 8f9d006d6f1840a3c4a2d1cab4db54b52948290d.nq.gz
    ├── 8fed094bfde047c0e0e5e013c27d1ae2b91ea0e6.nq.gz
    ├── 9060dc9723cd921f20eac7f9802fd51f0fb831f5.nq.gz
    ├── 91ca9cfe6e6e364784dd2cb0c61b8930459df78a.nq.gz
    ├── 939b8acaae89805ec3c301ba1744e40fb9860aa9.nq.gz
    ├── 94d49890a2cbc30f0efa7600be67b9dee7a66061.nq.gz
    ├── 9643a39bc0bc635d1257545385369c3030187dad.nq.gz
    ├── 965f01e32c6deb26068ef7f401befbd4ea74b0bd.nq.gz
    ├── 96c5f4436e54868f8b747ea46f02506ae1c3bf64.nq.gz
    ├── 981e0b28356ce4bd8c43fa28b4ae3ffca07f7634.nq.gz
    ├── 9abc32548808450d4835c636bd04385af1766369.nq.gz
    ├── 9abfcba1ea3ab092b375392bc6112ff0351aa2f8.nq.gz
    ├── 9ac30533b19120b20dcf5eb5a6a2011bc83c8f20.nq.gz
    ├── 9b56071f97759c39014955d5a2468a4738e6911e.nq.gz
    ├── 9bb02d114e8f8a446505b82a52b9f9fdb7b31e78.nq.gz
    ├── 9bd73c0a2a25a0b0da559b6dde97ddee9d901e9f.nq.gz
    ├── 9bfadca94ce18c6d6b0778cc39c045795906e659.nq.gz
    ├── 9c3e19c40eb9ed79d5e1b427e18b9955047f4bd7.nq.gz
    ├── 9c4f2c7ff1746f1ce3e9ef4d70a5e8395e08be69.nq.gz
    ├── 9c500ef16e720b04e43122bc6784c36c23d01e91.nq.gz
    ├── 9c506b128deffa7d6bed97323a23db440b98ffe3.nq.gz
    ├── 9d6c3a69e5dbda145f458f4a51a118846b0649f1.nq.gz
    ├── 9db7f3abc27dca695d79c5a02876e36276e86a65.nq.gz
    ├── 9e68adec3f985916972e97987deb24f078406c16.nq.gz
    ├── 9e90b3cd383d8c1646e5754c29a4462caaea0da3.nq.gz
    └── 9fe64df701213aa09a1187811d6b69134350dc98.nq.gz

7 directories, 200 files
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

[twisted/nevow](https://github.com/twisted/nevow)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
