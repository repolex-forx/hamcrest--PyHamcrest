# Repolex Knowledge Graph of hamcrest/PyHamcrest

RDF knowledge graph data for [hamcrest/PyHamcrest](https://github.com/hamcrest/PyHamcrest), parsed by [repolex](https://repolex.ai).

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
rlex download hamcrest/PyHamcrest
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 59139e31d64423e0253997a32be4b86c14063193
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 59139e31d64423e0253997a32be4b86c14063193
│           └── chunk-001.nq.gz
├── blob
│   ├── 00e21718c3fbb35477fdd37e6563abbe0df5408f.nq.gz
│   ├── 013ff17e5d1b0c9849297bd0711cdfdbbdb6583e.nq.gz
│   ├── 02e759dabf8549bb40380d5d61c17066f1635a25.nq.gz
│   ├── 03c39632214c2ccf5ea876c9f973a6c57ead9128.nq.gz
│   ├── 04fee897c8448308cb12fc69a02204ac6a78b092.nq.gz
│   ├── 05995c308447933d35c307094c9b0d96cae9e524.nq.gz
│   ├── 05b115d4900c6fd445e1778cde99871f0affbf74.nq.gz
│   ├── 10bfa4e459c87c20c99e417ed35e216a5980d75f.nq.gz
│   ├── 12982de94a4605bd583490c0f67bdf9f912e2b43.nq.gz
│   ├── 13f130f55587d9cb6f32d9f6af6ecd942c259f33.nq.gz
│   ├── 148ca01f4f69d19b1eb6241135d89b7a72bb4277.nq.gz
│   ├── 1621ae8d8c32c61fdac1009a2cc02b90914013e9.nq.gz
│   ├── 16bebbdcddeccd2d3094a0d21a2b53bddf257b1f.nq.gz
│   ├── 16f7f110235a409941ea0bbd466901610cea2f66.nq.gz
│   ├── 171de6eda6950c8e3dc0bf8b24aa55cc0bef9d94.nq.gz
│   ├── 18160919c174c15d6ede15b1b2723dfba6d6eee3.nq.gz
│   ├── 193a2066255674854d4c9ae4f5762d223d74411b.nq.gz
│   ├── 19e46c4c88a8b054d251d47d50d60e24439dac1e.nq.gz
│   ├── 1ade46cbc25582633a209da78bdb44cce61c0a88.nq.gz
│   ├── 1b4fbc123ae1f066507e29fa9fff574ef45892cb.nq.gz
│   ├── 1d1cbc01af92b5900a9d430a5b804f4fcac23b91.nq.gz
│   ├── 1f49a578c2e71a7e1e07ac1e59478df757f51f0f.nq.gz
│   ├── 23925c1f345b0f3005cc504d3593850844d9feac.nq.gz
│   ├── 25b11cb3783397f01f4718fed31376ffa2a217b9.nq.gz
│   ├── 260bce603bf5ca4750954ddb24b81b5d63965a6d.nq.gz
│   ├── 2e09225543eb3aaf8c5a2b7798a4143fbe8d39d6.nq.gz
│   ├── 2efd0793912d4fd4128781c622560459e9471537.nq.gz
│   ├── 2f7587dbc87ef43015ee49bc7fa77373aa0ac3db.nq.gz
│   ├── 2fcb9a385ecc37e562890da266100305a713e231.nq.gz
│   ├── 3125265a8551cdc91632873f1cbcadaa48f0152d.nq.gz
│   ├── 32e16a7c4fc4ec09cc3488b7b9ab5bf5183f0363.nq.gz
│   ├── 33494ef2d59e4d849f3d66c8aba707e818d6223c.nq.gz
│   ├── 34df2f6f01dbf13cee7be169df842ae021b8f766.nq.gz
│   ├── 3bb11209fb5f38331614c624bf7333115d951f88.nq.gz
│   ├── 3d0bcf12224a71170bf78e8a6644f288ba159d01.nq.gz
│   ├── 3ddde49853e27bcaaac0d9d93f8621400a3e96b9.nq.gz
│   ├── 4135494a1fc30ce333096707fa97555e9ae03381.nq.gz
│   ├── 417268af3e4768af3df1c7f6db0824b2403f4d2b.nq.gz
│   ├── 421ec5b427c92416e497411f007bf427d3388f70.nq.gz
│   ├── 43a3d84a8f12ff2f373abbd97b9bc3ffdbc88576.nq.gz
│   ├── 4448559f148fc7005ed9feae4f7b164655523bb9.nq.gz
│   ├── 4454b030fde142088f6817e61db1c8a62f7cdb64.nq.gz
│   ├── 44b5292f033cb4a41e1a1c68c847d028e017e7eb.nq.gz
│   ├── 4666d5f1771f60052396425757d7f9b08930e192.nq.gz
│   ├── 48361d935d9be3df273038c4ab9cefcf9ef3bd92.nq.gz
│   ├── 48d42a03efcfb0d03a8be0bd9f8e6a1ce4cfae39.nq.gz
│   ├── 49b29345b68d9c362de943949e33d558a57248c6.nq.gz
│   ├── 53497949796522136a1ce327794f498bd7b49723.nq.gz
│   ├── 54d7e6d8f6ebda18fa47d7a83899df345de7b81d.nq.gz
│   ├── 56ddbd19d078499a8efb47bc833baf0eb0be7e01.nq.gz
│   ├── 56f24f4ab51b8d64714ca6b502e4922fda956af3.nq.gz
│   ├── 59fa36c96820794cf9e6f14c6e845678d89e98f3.nq.gz
│   ├── 5ad2a610e6f10a982636d04f7fd570f124ae32dd.nq.gz
│   ├── 5b313f3657ee1f5a50107c7cbaae1c21eb2bb61e.nq.gz
│   ├── 5c83b62d4066b4d001542d014209889ad21f8e6c.nq.gz
│   ├── 5e1a6e033e65a7b224fae9e12fce03bcdaa92128.nq.gz
│   ├── 5f3a1612f6cb22ea873b23e3c9d16a4a2e3a35c6.nq.gz
│   ├── 61cb82d43b52bf0b5f3bd66e9c1eeb3d51439f67.nq.gz
│   ├── 63a5f472c837394f1c2fa2e87d4fe83c151041f0.nq.gz
│   ├── 68d56c76b6eb56aad2a1f41fe4066e8885f79990.nq.gz
│   ├── 69fa449dd96e2405945b2e4cff2fd0ab8b102097.nq.gz
│   ├── 6bb18b3da0fa274dc36f26445e829ea3f6717259.nq.gz
│   ├── 6c2992cfdf93bb4cc4d6ca7187f69177f109ba19.nq.gz
│   ├── 6e6fe1ac4346507e2921b2637be2156fb8ff07c9.nq.gz
│   ├── 6f22414bfda1f2da49c0ed745484674c6baf4118.nq.gz
│   ├── 72284ccd764991b9676d656e7bf429b9221ef881.nq.gz
│   ├── 73b2d75a40e5ece36d48b02284858dc32e1b0392.nq.gz
│   ├── 74abbafa85ccd9f8364b13bb285c58820aa64638.nq.gz
│   ├── 763c1045e2c2755532f1f9e0f06b19deb24db66d.nq.gz
│   ├── 792d6005489ebee62cde02066f19c5521e620451.nq.gz
│   ├── 7dcdb17f7aad797c9dfe555dda92f4b304e59269.nq.gz
│   ├── 7e6e555520323399a5e81ce83a19bf8ece43af9a.nq.gz
│   ├── 7edc994f9c1f2c84412960a07b5380bd2b98cd5f.nq.gz
│   ├── 80f11c51190229627511b6933dfe0ba926214306.nq.gz
│   ├── 821ba1461768a2c68ff52d4c600dbce500f9cea4.nq.gz
│   ├── 83f4d8cfa83cd4ebbb034a283fcd8551481ebce5.nq.gz
│   ├── 8532da4ffc53503692197dbb7289d31e0c8c828b.nq.gz
│   ├── 85f4cf69982c5f0463794db7eb06354149135238.nq.gz
│   ├── 86d03999d7070c9ca97638715ed1eb6f49c71c5c.nq.gz
│   ├── 875b6e26daba6f8a70980a43aaa0f3e544ce1121.nq.gz
│   ├── 8ac58f045a3bce23eb84f3253ef9babf7dd81ddb.nq.gz
│   ├── 8d05742429a27de0794deb5c4a904c6f2a7d7811.nq.gz
│   ├── 90c7cc79ac6a2bd4310262f61f1e0db79d03e4dc.nq.gz
│   ├── 921e3b2f9f5adc9b6df215f63ae52856cd50b688.nq.gz
│   ├── 937245d0a9c74a01eb276866b409cb0b74107e2e.nq.gz
│   ├── 96fbb26080d6e0fa19cf53f42f56133b09ae6a9a.nq.gz
│   ├── 99d3fc09888b59d1c5891defab2bb0e60e7d5e77.nq.gz
│   ├── 9acd43f8bdc2a4bd915c0f684e3e2b91b2c7786d.nq.gz
│   ├── 9c7c39c027e4ba7ed85a5505e22edeb338c453a5.nq.gz
│   ├── 9fbcfcfef048c416621175d651c817c2b49dd352.nq.gz
│   ├── a011c67fe43c311249c2efadeae098125830c360.nq.gz
│   ├── a0d09b49a782e2ad6fda8451f8f190306f2f1f38.nq.gz
│   ├── a222d253de23264643e110a25ec58a0554c10533.nq.gz
│   ├── a6141f71cadbed0bce89dda51b7804ca25544d71.nq.gz
│   ├── a8c927a567cf3da6e23dd7c527ee28c86a4b49f5.nq.gz
│   ├── b03d46615b6f0207d82155e649f828935909ec8f.nq.gz
│   ├── b0737876a6aefe1dfd7ad0c856638e75b3237176.nq.gz
│   ├── b234ca6e082aa62686e6d0236ce57f9397c09d52.nq.gz
│   ├── b36d1925b9efe5c8235126533e51eb2abb23a7cc.nq.gz
│   ├── b40f70119c43e4d4fa35fc98d4a9d17e8bab63c4.nq.gz
│   ├── b5727f5fc7da37a10eb9bc4fb6333b0d66901ad3.nq.gz
│   ├── ba3f2fdf8a7b390b36a6234a8d603f84410980da.nq.gz
│   ├── bb6c778edc470a5e6e68528d509963e1e173e8c1.nq.gz
│   ├── bed86d82a375e0bccffd36f823b4eabb25170707.nq.gz
│   ├── bffb4503069372a9f3bc076762f123f89c96d79b.nq.gz
│   ├── c022e7ced73fe924b32c7fb37083bf79279f00ba.nq.gz
│   ├── c11669c036fd33bdf19a4602ac0b646931f7b674.nq.gz
│   ├── c3cc7eef4082c0230a4351f324f174ab3c1ff42e.nq.gz
│   ├── c3f310b36784d9bbb2216efb416bf811a882b795.nq.gz
│   ├── c3fb7bf21ca548fc2808934692d7d76587c839b9.nq.gz
│   ├── c433f3c13263b8d0a025f737304cac2f730235e6.nq.gz
│   ├── c5940683a8fabc7cc1339d0378d2cc0f8911a6ea.nq.gz
│   ├── c62bc0c9f67d720d9f38c12b80eb3d8b82f3d28c.nq.gz
│   ├── c7afb18464f9876b6c53b438584e2b24c9712c7c.nq.gz
│   ├── c800f1da31dd9de22ef55ff13ef3f0072278b840.nq.gz
│   ├── ca5b71aa38031a499499b8e2ab6aac19e3049636.nq.gz
│   ├── cef4ef7be56b27472e2ce8773035a1257d4ddf95.nq.gz
│   ├── cfe1a5e86ae6fd6b1bcf14925765533931f017e2.nq.gz
│   ├── cff60d636d0516333aa4e337b5c613744096d997.nq.gz
│   ├── d10f1cb5b33ae7b4f1b98eed3575ab9d0abbabd2.nq.gz
│   ├── d288bd4b463e3141c9e2d28c248bb3992515e67f.nq.gz
│   ├── d2962efc3d90b9ba2b672e692f94f7caa9f7f7f5.nq.gz
│   ├── d4269444e6cf922b2e337ba5b9066098bb6466a5.nq.gz
│   ├── d56262c4e75bc6addc156ef784767405fa72d10d.nq.gz
│   ├── d57cb6ef0c00bbf48f59d55807d54b0244418cdf.nq.gz
│   ├── d5e90a54de3577d61516fa102e85fa791595dc55.nq.gz
│   ├── d944519857682ea73cde453d2ab8e93b328d70c2.nq.gz
│   ├── da2e799beaf0909c0c5a1ed85756f030f6a23d3c.nq.gz
│   ├── dbbd02bbe2e9f2ea443a2ebd9f9b06bedf4ad37b.nq.gz
│   ├── dc5f70350fae0f14417af7096a119647a2db4588.nq.gz
│   ├── dc652438e9dca30bd12b7b1e119c402eee1cbad0.nq.gz
│   ├── dcb7e853343221d53e0472e034e5668dc3837d5b.nq.gz
│   ├── dce1489c3c8be6f2cdb07d8835a00bac33b04170.nq.gz
│   ├── e015671d9d8e5d8ce1085b20a7766ed2e890c90c.nq.gz
│   ├── e0ceea34ff0dbbd7234720edebb919790d4abc80.nq.gz
│   ├── e0db59692b4974e755fd3c0e297c375eb20791fa.nq.gz
│   ├── e27f927c19692b1046c31f65208919fa2bec5db8.nq.gz
│   ├── e57c5a4f8f2cb5f65b8aa16440a4bf51c72e89ce.nq.gz
│   ├── e65ff92f744c66c7b7375a7ecbdc1ab050f8565c.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7c729dfb03c611836259ce4def98a984f8dd745.nq.gz
│   ├── e7e8dd4190f26eec08ed9f5b67a8adf2999707de.nq.gz
│   ├── e877a2a37501ba65e20cf2f17b7e6aa631ea9e25.nq.gz
│   ├── e87d6e1ffc5468377e402d7b9c8ba549953d3bf4.nq.gz
│   ├── e8964613a1b665a5279aba4411f977a02e0e0d8d.nq.gz
│   ├── e958ea315cae3d43365b95a081e8a781e912212a.nq.gz
│   ├── eb958839692f66c9bb7cb615c8aa1f8e3448752a.nq.gz
│   ├── f00a8ce0f765936f5c10192dc1f592e1fad05cc4.nq.gz
│   ├── f121caf45f9d58329de80d5089447652eae46dd2.nq.gz
│   ├── f615dcc7427b0bb275baa352ce06f7fbe0ca5f91.nq.gz
│   ├── f7819987e199b1f610973833f6f62ec671e7063a.nq.gz
│   ├── f9552b7fd98f8d7beea5119171ecdb4c989a548d.nq.gz
│   ├── f96f33813c29fc22224ecd173475551521ed1576.nq.gz
│   ├── fb97ffe0f9c4e54ad3ae8a88a81e398fde42b0e0.nq.gz
│   ├── fc58db1b6bb4a97020c4e09495f74aa701790e89.nq.gz
│   ├── fcf41208b9d1d13b244822b7bd12a22bad197359.nq.gz
│   ├── fe93ce18e18d475c84f20c7cb38fdedb9f22c571.nq.gz
│   ├── ffb62f6c3e04f1d8ce8a9db43a3e2a2b885a07de.nq.gz
│   └── fffa82cdd03d08872ed97e127c0f90d7f828174e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 59139e31d64423e0253997a32be4b86c14063193.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 167 files
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

[hamcrest/PyHamcrest](https://github.com/hamcrest/PyHamcrest)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
