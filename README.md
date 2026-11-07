# Repolex Knowledge Graph of ansible-collections/netapp.storagegrid

RDF knowledge graph data for [ansible-collections/netapp.storagegrid](https://github.com/ansible-collections/netapp.storagegrid), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/netapp.storagegrid
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5f8478771f683520b8cec75f6600876258e5037e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5f8478771f683520b8cec75f6600876258e5037e
│           └── chunk-001.nq.gz
├── blob
│   ├── 009e4f078f5591f7747aa2ace90e80d514b80477.nq.gz
│   ├── 02c940b066a6053dc651238cf7ddba2ed07b56b3.nq.gz
│   ├── 0320ba79cf272f1181b07ee2442b92de6db05a4e.nq.gz
│   ├── 035df014a62a26369b4a8a75d9a2f4551af551d8.nq.gz
│   ├── 03dd3ddd221147a0a1d09558f218c48ae3764025.nq.gz
│   ├── 08a5a64fa8584ba704e4873108b4a6a37ce52ff2.nq.gz
│   ├── 0a190da20d1ff10a4aad572eae02881a7a917eb4.nq.gz
│   ├── 0a3c3614c9ca583912841edce0ebd93787e6b45f.nq.gz
│   ├── 0a7aaf599c23d4bb4cca8aa6bde171aec4fe8341.nq.gz
│   ├── 0b3062c73950811de075117150c2e9146b557c4a.nq.gz
│   ├── 108768eeb70832dabb6d9c9743b4b2ff8a35071e.nq.gz
│   ├── 12546e069acb5af4523cd505bbb655588ff98c96.nq.gz
│   ├── 16ca863d091731121ef0c888b5bea9fd15319f93.nq.gz
│   ├── 190ace164a70cf0d4edf45d1fb447f9c603f8470.nq.gz
│   ├── 1ee5a34276c4b57f1c6c7d7b42cbdbd776693961.nq.gz
│   ├── 1f07e36e7d0de9a4354e5b9c3e411c03652389f5.nq.gz
│   ├── 1f1bf1a48599998430cc0254d09fb095bd8a3442.nq.gz
│   ├── 1fa3148941e942b4dd412ea308edfaa8e7ee6e6c.nq.gz
│   ├── 20d40b6bceca3a6c0237d7455ebf1820aeff3680.nq.gz
│   ├── 2165a8461498d652e45f2b43de5c1f72584edef5.nq.gz
│   ├── 229a6c51fc3289dabaaf6018aad8d747f13a0bcd.nq.gz
│   ├── 280bd4296eafbfba2f29ee1d46c6c18b7f76bfa0.nq.gz
│   ├── 29d3a30347d63264d74cc4a2ec2e9a14028a9ec7.nq.gz
│   ├── 2a8ffa6fc2bfd5f54afd3f6e7901f39756ab2203.nq.gz
│   ├── 2b5bcf567263d0281f79b6482fcaf1ae924329d2.nq.gz
│   ├── 2cbe4a120aaf0b3a660267a0843c8db598c08b37.nq.gz
│   ├── 2d73814d234a6112e9438708fc53d5ff85d32a9d.nq.gz
│   ├── 2e28b451acb418ff35cedcef7d6f6540ebbb41fa.nq.gz
│   ├── 2e500a527fda06416b4794beb76181789eeab06c.nq.gz
│   ├── 34b8b7f9eb5f2794812de629d99c252f8d4ababc.nq.gz
│   ├── 350ee15dcafb61a5e69e4d882650a81d75555418.nq.gz
│   ├── 35fc5e40622dd1dead50ecd4de8f229c4f11accd.nq.gz
│   ├── 3715e10ec017163ffc5e73345e8bca0bcc91ce19.nq.gz
│   ├── 379085f5dbeb0c8b0bba250c5fce314dadf20410.nq.gz
│   ├── 39b74d39688f1f4d0d56aa8fb467a2cc9e346459.nq.gz
│   ├── 3b0d2661909e66840b4801c0efaed026f04570b8.nq.gz
│   ├── 3b25f82cb5376c4752b4a179a46357d89c9247c4.nq.gz
│   ├── 3b32cd684cc4a11f5000564aa53d1a115cc1f7fe.nq.gz
│   ├── 3cfec2ebf4f2f336f5399965b1c88a24f002eb6a.nq.gz
│   ├── 3d1bb11a0f7fe030b56246bfedeb84792fc3cba3.nq.gz
│   ├── 3e0717d727cdb0bf7aa5fe51c9062e46b96ccd75.nq.gz
│   ├── 3e0d44262e083a4099e68ccad9534696c658e561.nq.gz
│   ├── 3e7b977a7c0867ecb1224661a1119a204baa0bc6.nq.gz
│   ├── 3f69308888379bf0603e1cd130e56341def30377.nq.gz
│   ├── 3ff911dd9514270d4631442dba417dbe21f03d20.nq.gz
│   ├── 40e6da8420025968b38acff2c0b2a253bb799a48.nq.gz
│   ├── 4159a5eae016a1d139fbe0bb0d2c7a421d1e411c.nq.gz
│   ├── 43bc9fcada463c8a957e9c8f4234c928d443993c.nq.gz
│   ├── 4988c840dd3a46a84ed71882e4ad1e67ba65072f.nq.gz
│   ├── 4b66a4d534b62e55142ab1fff3ae96b99cf18221.nq.gz
│   ├── 4c034e3576a94af9c7f4fed9feb9f4c2e3630576.nq.gz
│   ├── 4cbf55c2f7c2f1c0aae38c2c6b528ed7c5ae0319.nq.gz
│   ├── 4d753c5ee829e8b67f7cfa6a4180b79aecd6e2b8.nq.gz
│   ├── 4df2a4295e71eda782b0907f987fb56241222838.nq.gz
│   ├── 52349c93a358ee118bfb2f22f7d828dc05d215f7.nq.gz
│   ├── 5311e1421e9abe48008e9dbb06e3ed377979a613.nq.gz
│   ├── 531b2d5ffe6c9b595a1ce59f1aaaaee95f9fe79b.nq.gz
│   ├── 551299f2fbc3963fffb156807b14e277e1b81136.nq.gz
│   ├── 554f16aea5c342ea8cdd2e3b006ccae6f52d0208.nq.gz
│   ├── 56564d5a8c6a53a4de877130f90c773184eff096.nq.gz
│   ├── 56c13ad0b281adb7778c523b2bd40eb4272b70f4.nq.gz
│   ├── 57b1eeff650da4596e14a9b50363d31cda610fe8.nq.gz
│   ├── 57d0a2c45adba9bd72a8ce9dd742bc79dd645135.nq.gz
│   ├── 5a9eac8401bb3fd571e67f841f00ed5271c32b4a.nq.gz
│   ├── 5b6c7867e4bb8c238f2d3a2711c886a0eb952b73.nq.gz
│   ├── 5c356f2023e121e1d7a259217265979497c12a1a.nq.gz
│   ├── 5f9726fe71338c8a6cbd73933571d5ac267d0b74.nq.gz
│   ├── 615bf35a7cea83172fda5c9c0840b63d7beb8773.nq.gz
│   ├── 6198bd5cfd523808696a6f639a108a6189f2790e.nq.gz
│   ├── 62e8845c6a4b29eb54d61da9b20ef9caa63f4b58.nq.gz
│   ├── 63514c5c55431859a3a1a77e18260758818e04c6.nq.gz
│   ├── 6467d3ca52c51f9b06745aa75eca90cb629750f3.nq.gz
│   ├── 649ff24ea791a0aae7e91f6c95de5c5e999f6903.nq.gz
│   ├── 6c154ad539a6149f5149abd075c5ef4c815cd6a3.nq.gz
│   ├── 6c3b631256138570e1d368f7035ba6b0291ffa63.nq.gz
│   ├── 6d0f0d7d3580b22a9c28095e67192bfda7b59c40.nq.gz
│   ├── 6e514305ac84c76ea72280e1961aeb6f49708382.nq.gz
│   ├── 6f8a660ebf65fd7b5a6b0b3b76dfacbb187b8fcd.nq.gz
│   ├── 7286e3590d10b7835582ad16446a5ab8fb4b9381.nq.gz
│   ├── 7761a5148ad8cc74d001de0b20a30adea864ed32.nq.gz
│   ├── 7bad522c88ce7259b2a8feb6b573cf52a4020f4d.nq.gz
│   ├── 7d0fadbd959daf2f90c392d05b0c4aead74404f1.nq.gz
│   ├── 7e88c5e66311d268c3b2067631e37404a1541fbf.nq.gz
│   ├── 84a23193eeb09e5436c1f01c2e74b0bf2b42c79c.nq.gz
│   ├── 871e634c1c7a4fb5b35f7a4bd709728995c46618.nq.gz
│   ├── 875140df24ecdeda41750e9b1d0b3d24abec5815.nq.gz
│   ├── 87aecb16ccf25f67b6f8836c5905a3237e62923b.nq.gz
│   ├── 884d6d9b4917ecd53f86fb762531bca918742c88.nq.gz
│   ├── 899fc3f825a21d9b11b2f0e735143bdf6ae179a1.nq.gz
│   ├── 8b587bbb497b511d2bdeaffb133a92fd94438142.nq.gz
│   ├── 8bb1c7b2dee873973cf9a0d5fc17a7ab5d54e2e4.nq.gz
│   ├── 8c960637bdb8c25977709ecb17652ba10d625e1f.nq.gz
│   ├── 8ded44e1548a40373847722930561bc9eaa7bc2d.nq.gz
│   ├── 8ed386213836a38c76f508c17049898f93e444a4.nq.gz
│   ├── 934a312c479bd471c013ec5c63a289572a3cec0e.nq.gz
│   ├── 939a104dfebb8c36b95c76c1f2bca7ee7e1832a3.nq.gz
│   ├── 95df6b7950840fdf6bc08598e23b31a0f52f14bc.nq.gz
│   ├── 99c30f25dd8e3234e8018ae25d96946339c009cc.nq.gz
│   ├── 9d03be5b7f998af9413cfda0e2a9c6dd5554cff4.nq.gz
│   ├── 9dcfc9d2da034117504edde67ab8fe5d3128f552.nq.gz
│   ├── a012dda849653e8005da86f16e593ed001bebedc.nq.gz
│   ├── a3c8fe6ff5a632fcee466def59e54f15ea7cc676.nq.gz
│   ├── a3e6b54951221e679817e8d91cd1e491b8373031.nq.gz
│   ├── a40a51ed3df7ee7f7e9e1b228af4a5ba4d072baa.nq.gz
│   ├── a4e7f648442cf2fe01aa7843326a6065fdff3d09.nq.gz
│   ├── a50668e721f58c333cc09ad58d289cd4466d7033.nq.gz
│   ├── a515be8c2c82751db5098e1b2f3b3273cda9b46b.nq.gz
│   ├── a5af1dcccf09c6288161ad656d8820a6a662f232.nq.gz
│   ├── a5b04c08823378257341e626b9e27daa3aeea5a5.nq.gz
│   ├── a8fbff2df198a9c9517eace62a22271a3ff759d5.nq.gz
│   ├── a904c9b73ea925db173e8893fec833b827679e99.nq.gz
│   ├── a91168e87d4eeb9394616514e7a4f02824df4214.nq.gz
│   ├── acafe43fac557cb990b8198ff23fb39539517fb9.nq.gz
│   ├── af4fef0beeebbc337012294f246f4024de93f588.nq.gz
│   ├── b0f1f7ee2590a4cec351eeaf954283059152bec5.nq.gz
│   ├── b124137cde912de2a41b9fc74c88264da52bdb66.nq.gz
│   ├── b416774176160415a70d4bd155d778919219e8f7.nq.gz
│   ├── b54cf7b2c3a699bf9468e3410ec451bb039f5bc3.nq.gz
│   ├── b5b4d5caf1a6ab1452f594d92ac8b93e46272220.nq.gz
│   ├── b5ef6b9ef01df872d45d616668ff73213e0d24c9.nq.gz
│   ├── b6777eb817d0c2b466052d16be9aabd1a0d659ca.nq.gz
│   ├── b753c54145a3b68104ca837a6a58c9f07d3e3e85.nq.gz
│   ├── b8ab53ecbaa23061e9616a5271d58034f24c400e.nq.gz
│   ├── b94726ae8ccba8c8a64ae0642db02e233153ff75.nq.gz
│   ├── be557466d044e985369cb4d26c230fb4c6efc9ae.nq.gz
│   ├── c198cecf7b13889c05d92c723155fda17a772603.nq.gz
│   ├── c37befc019364ada14f32d74086cc6920d72ab79.nq.gz
│   ├── c4fd55f4de78dcc94d2853668d18e15989a440a9.nq.gz
│   ├── c67db830975c97815d1843daa10e45157a6d8000.nq.gz
│   ├── c8b2600b9fdb2ebf08893b939c0642e42be47c14.nq.gz
│   ├── c91f1214f40bdd344424f8c544b45e7bf91cb52e.nq.gz
│   ├── cd8d39217df1ff0bf25deb986fa7564188224f49.nq.gz
│   ├── cde50bc22459a1a3e015a3ca3475d7ec3dcf5661.nq.gz
│   ├── cf21e38498522c3504e75c68310fb439467a5452.nq.gz
│   ├── d13f9f5c141e74ec1347f382f8e0d4a365563c6e.nq.gz
│   ├── d2bbddc6ebe9fac073913d631ac9e9f7a8e473bf.nq.gz
│   ├── d33950e7a51353c0aaefe59fa86d8426a34d979b.nq.gz
│   ├── d41392e6d058fa860b79ccb2b3390b38e9662c3e.nq.gz
│   ├── d44e0e201773546be5b8c4ab663b1f6864457ea3.nq.gz
│   ├── d4c6994abfb42d2c2ba393f99f57b51734ae9ede.nq.gz
│   ├── d4e8923c932dcc7ae64edf6ac5f7d0dd7498c522.nq.gz
│   ├── d514ac1cd87eb3492f76f46f795a5dde65cc8919.nq.gz
│   ├── d7e9eba0b6c83edf00c4362a9b72da508eca209c.nq.gz
│   ├── d85f96328c599b05cfcbe09f2ae5cfcf9b94a9fd.nq.gz
│   ├── da39db36ba65fdea57999b363f9c9d98400efd04.nq.gz
│   ├── db471b5bec707161c42b46c2de3632a48f913521.nq.gz
│   ├── dbc339d54a2544a505771e68a72dfed8d97cca75.nq.gz
│   ├── dc96c9c1c69597bb3fd81cd0df002bf12f777926.nq.gz
│   ├── dd5ccfbc04801bed278854ad33017361c5dc3184.nq.gz
│   ├── df65e980be5970dcce0775577ff6df62d72640c6.nq.gz
│   ├── e03bdb79ba26a55a3eeadfa9daf9bd2354454d74.nq.gz
│   ├── e325250b956f9e15aeda75e8b4d5cdebc397283e.nq.gz
│   ├── e348d9f31dc0666d59ddcbabd39d9f249bab4f8f.nq.gz
│   ├── e3f4ba8ad04f4d7d3047968bcae7d6462b5a8029.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e72785bbe3899355fcc0a515bee6453bc9e55de0.nq.gz
│   ├── e7c3a30b725f931bab92708acd6e5f6000688e3a.nq.gz
│   ├── e8b21767aa7eccbd16d46ee0e1165ebd8024a3e8.nq.gz
│   ├── e973c944d7d73352b610535e88ec67354ec04442.nq.gz
│   ├── ec3a04b3188350ff26e9b174f12b897607922efb.nq.gz
│   ├── ecf62a4af9324ff557fb9925ee8b495dd19075f2.nq.gz
│   ├── ee9efa70111cdf002ab973b1ec09bfba29276d7f.nq.gz
│   ├── f1359b299d3f05b8d2fc5fce7665b91bb780f8db.nq.gz
│   ├── f1e404e16c484793bb4df3d0e2410b350f4c8abf.nq.gz
│   ├── f21ecbe464422c747413f8031cc52937dddb5a93.nq.gz
│   ├── f2293605cf1b01dca72aad0a15c45b72ed5429a2.nq.gz
│   ├── f2397b12b785934449d6d7e74ac36247ae327f26.nq.gz
│   ├── f79246842961b76c43133f350f86f08a0a0dea07.nq.gz
│   ├── f83d9353fb2b8c2246724af5104e8793b1391d74.nq.gz
│   ├── fdaa84f89a3f85592cfc205d08e649410355c843.nq.gz
│   └── fe5b607409172dae30003fe8d3d5b7a6a7e813ca.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5f8478771f683520b8cec75f6600876258e5037e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 179 files
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

[ansible-collections/netapp.storagegrid](https://github.com/ansible-collections/netapp.storagegrid)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
