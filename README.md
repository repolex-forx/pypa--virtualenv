# Repolex Knowledge Graph of pypa/virtualenv

RDF knowledge graph data for [pypa/virtualenv](https://github.com/pypa/virtualenv), parsed by [repolex](https://repolex.ai).

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
rlex download pypa/virtualenv
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a857a7823c73c35935d0318b4f36e5d582691e1c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a857a7823c73c35935d0318b4f36e5d582691e1c
│           └── chunk-001.nq.gz
└── blob
    ├── 005c23640b12996418831b6dfbe64b9bd7e97188.nq.gz
    ├── 02b865bfe4ec64bcec92d40902bf4b109bb9a9a2.nq.gz
    ├── 02c75e9ac1cedf3585d43ee015dbe476502ce5ca.nq.gz
    ├── 03dcef56a5f6eea0cf2579fb5f0624831f7145a4.nq.gz
    ├── 0466460b2f0c844dfcfeddf3de25dca8b925e97f.nq.gz
    ├── 052f56fdd46fe6f792730cf3d8584f5264e286ae.nq.gz
    ├── 057c741cd6acaec1cb679fa3f828793408465220.nq.gz
    ├── 0612fd1a5dbef2a7faaeb63aa2a8f679b3ba28d2.nq.gz
    ├── 0708672106d090f36458201efb90ec24114347c8.nq.gz
    ├── 0806ee5dc30853e8efc82be5da8494248437148a.nq.gz
    ├── 090396002eb759c78f030c5f6ca95e0614de0e3c.nq.gz
    ├── 0917872bd34669c29f77575b233ed039fa112e7b.nq.gz
    ├── 0954eed3afa075f61cc9553ef30d0f2efbf06118.nq.gz
    ├── 0a88fad758a6188f1142425aa6781e1e0c5a96c4.nq.gz
    ├── 0aec184f8ca16e0b6fb8407e846758e3d9de5364.nq.gz
    ├── 0b49d1868e1f97c16275bff24c851428f6cd886a.nq.gz
    ├── 0d5dd54c3034c1509fb6720ba3e086678996c9dd.nq.gz
    ├── 1164a23839185d001f22418e18ddf0ca366008b2.nq.gz
    ├── 12794f047695fa05937a81477d5536dd2637cae0.nq.gz
    ├── 133e1e31c444572855effd38d7042d9eac3b30f2.nq.gz
    ├── 136c1b4f62ee5ccef56d6272f49894bcab56fe9b.nq.gz
    ├── 13a6c7703476c2a47d98db4358e0fda414898358.nq.gz
    ├── 13bb94fda8272f3e528a968f531cfb9d1b3e78d4.nq.gz
    ├── 1534d34c2f7f6c2f5527058881747c81636a9601.nq.gz
    ├── 1594a93128dcc723b7bb2151611f274c48c17e39.nq.gz
    ├── 15d90e215de88b00535af0a3fa506e0ebe8a9206.nq.gz
    ├── 191f262678aed3e040f16f656edc7ab49bd43536.nq.gz
    ├── 19af92a039caf5499ec9861a3e967207e6a33070.nq.gz
    ├── 19ce0e64bf1673a32c0d65928b8f296d810d542d.nq.gz
    ├── 1cc9cf633b419f29a0dc6abd4224c43d14141ed4.nq.gz
    ├── 1d8be7311d9eeba8a201ecc3f2742c4cfbe43304.nq.gz
    ├── 1f1b15256893dd709b5c3926097e4e0e05be017d.nq.gz
    ├── 1f255cad2eaadc3253dbc611c9ee7cc50137fe84.nq.gz
    ├── 1f500d2824b4d05e2b30e35aaada3b255021df8b.nq.gz
    ├── 1f729837df9ad73fa5558c322661b0cb3bfe7c88.nq.gz
    ├── 20873f3f9b41e371c6360aa9ec552a2e55e7cc44.nq.gz
    ├── 20a398a306cbf00699bcd7910c4d580cc65ca4d1.nq.gz
    ├── 20f7b25b8b783333f1043a3cae181d2582944e9a.nq.gz
    ├── 215687a3409cb63f558e34fdd4029154fca381c0.nq.gz
    ├── 2170814a58e1c93b49427e75ba6af69f51d3720f.nq.gz
    ├── 21be96d068a55ecc3749d674db0d2a3c2abc633f.nq.gz
    ├── 21e6b81a3f98f0d0c53f7a9ca60cfe13397feca7.nq.gz
    ├── 22bb8dba79c336369447326bc8d4df60d6e311f6.nq.gz
    ├── 23bde801b53a4499b1cbc4d6b43ec3a6aa7011a2.nq.gz
    ├── 240150a3837d2e753a90c09aa1a37b8d644b82f2.nq.gz
    ├── 243691994eec1ede5aedacf02fb1a7d9446b3bf0.nq.gz
    ├── 24c0afe4566b4f9b6abd7fe41088724987423771.nq.gz
    ├── 251308ff4256e1d4086b14a1193ab12d349b3470.nq.gz
    ├── 25878957b105f07a64cdbbd43cd4943f972bbfd9.nq.gz
    ├── 2587a7ae7615a48d17bd9b3ee86d513f2c6d64cb.nq.gz
    ├── 29129cb4fc9ebc026d4dbc4054e91685e746bbf4.nq.gz
    ├── 2965915b44e96a6a0cadb68d6434f59fb40692dd.nq.gz
    ├── 299fb26f0602b4661139737cd24579fd08423455.nq.gz
    ├── 2a1676d95dff1cc7194c08a95c5827f30a301264.nq.gz
    ├── 2bb5a5d4bccc67edb3236c113c891e190ec9d063.nq.gz
    ├── 2db749a77684d3128ea8cfa9761ad281e51382e1.nq.gz
    ├── 2ead4a38da22a39caa062018ebc16aa1d6ffa100.nq.gz
    ├── 2f6d9676755253ac5d1750bcf61df57b58dd962d.nq.gz
    ├── 2fe44d67a0cfc9db69f294c0a8781ab46d4d8d10.nq.gz
    ├── 30a5f6cf9b895d77ad28f6a3df8dbe78df8b7c12.nq.gz
    ├── 31401dad663a002ad6f00cc7e9222838b351a78f.nq.gz
    ├── 3289388713f0ca3e84e4d886c5a839cdaff64e66.nq.gz
    ├── 36663b72949bfa0eaf191180983ec7ea1779746e.nq.gz
    ├── 37c3a5f55a071a714d4811b2d97a0a0247be333e.nq.gz
    ├── 3879fa271a04b07daf05891e9513ed203bb435e2.nq.gz
    ├── 3886f91ebea6363cea2881570eb44815e89412f9.nq.gz
    ├── 395e77116d8ecc61c9c20044cb31da7ec3e24f1a.nq.gz
    ├── 39d5a3b90ce47f540cab018c5bd451e72b6fa43e.nq.gz
    ├── 3a374f1c5ed91fe18e17fc72082fde18fad4e9d0.nq.gz
    ├── 3bec218a7d5d8f7bb4a3415080cf73cadedd10b8.nq.gz
    ├── 3c8280ed8d21e649d864717ee79ac70af7213898.nq.gz
    ├── 3d7626e54730a8809342da14cadbaa58a7904b04.nq.gz
    ├── 3ec017d2bb7b0235f7af0d667cc88a53a9306679.nq.gz
    ├── 3f85db4ed5b2614edb0a07030ce85d5c57bb006b.nq.gz
    ├── 4186bbf1bd2a5fc85f20b1cdcd0021780679ee43.nq.gz
    ├── 41b33136f8d5d6dfbcd55cbe4c1b0c55b911ff22.nq.gz
    ├── 41dd7b9d01788c9ac9cf9a543c70f2ef1e6e9ae9.nq.gz
    ├── 4221c0390218a767670fe1e084f8d7d538ebcad2.nq.gz
    ├── 4241b50254a7a9c873d8912c46d81df1b8904978.nq.gz
    ├── 44130a0752bb1ac0a0bbd0f1b71ba9d52aaf4635.nq.gz
    ├── 445bb3ce9aaeddc98d7c3f5f664ed86c5531d83e.nq.gz
    ├── 44f844ef4b2de7691b097ecbd8fb4fef54e5fc5e.nq.gz
    ├── 457c15903ef8b63280b5178d6012420589e5bcb3.nq.gz
    ├── 46416fb28cbe409d1ee1e0649014108bb7a677f0.nq.gz
    ├── 4723aa9e2fb4d72d91fb06c79ce9bd3eb58b0872.nq.gz
    ├── 48f2767c34a3bfc9f1ed5444102416a83856964e.nq.gz
    ├── 498e3db9c7b3fc28e3f0d37eac14db339a3bd7b6.nq.gz
    ├── 49e0f24248ad95fb206cb825f95b59a19bea56f9.nq.gz
    ├── 4b2d72f2567bc8ba9d149817ec790612bd5ba260.nq.gz
    ├── 4bb03ae1f3a4141df93ff938f09076e7cf60950c.nq.gz
    ├── 4c8cbe63c5fcbd00b49a091c33623b6519419694.nq.gz
    ├── 4ce911622e62c9f3a7f2a77e92aa00b7743e5fa6.nq.gz
    ├── 4e1fd6ee82b95504ce21fb182770fa037d0fdf93.nq.gz
    ├── 4e6ca4dda7ec6e7896a5f6cb94056252ed044b7f.nq.gz
    ├── 5115865933a5d301dead1c0d553773bdb7725293.nq.gz
    ├── 515f7b7a0419689a1e4b54055df0b6375c9ffad4.nq.gz
    ├── 53ced18b2560e405767308dde5ef0176e9924aa2.nq.gz
    ├── 55a9645bddaa8ef1741302b7349e088ed38e1086.nq.gz
    ├── 580d09a920422fcabbd462c937d08c96dd7f08bc.nq.gz
    ├── 584b0694551c39cb3c17301a5c4783fedea298a0.nq.gz
    ├── 5ab576a2f82def0f7c08e0baa1eb19ce3e683715.nq.gz
    ├── 5ca60c5d69315c49b8e1581c4fd96f320d918eaa.nq.gz
    ├── 5e1a8c4df9e475b4f1d262dc5141012741c088a8.nq.gz
    ├── 5e3e87dcc63cee828e15260a27e553ddf6a8cad6.nq.gz
    ├── 5e525f0418646d64e749ac83876e63b7ca81cbfe.nq.gz
    ├── 5f89818f9e63c2f6829c7706c57f223cdb5bbd38.nq.gz
    ├── 6210c1cdfa343169791d8ad111c7182cbc63e317.nq.gz
    ├── 65c2f4ebd850a5ac0e9e514a160e35f56cccc30d.nq.gz
    ├── 66ca61f23d124632cc094c1427fc29a325f16ede.nq.gz
    ├── 673ad3129b81acf9b052bff24babf57d13210e03.nq.gz
    ├── 6761921d0c9a54ae9fb40ba00fd93df9c712a646.nq.gz
    ├── 689337387ead83c332403a0ee1780825e292eacf.nq.gz
    ├── 6e92e2f5f7c4da1d6c3aaeb689e6b1d00d269d9c.nq.gz
    ├── 70bb24b6e97a5c270ae1342abdc216968fa9ebcf.nq.gz
    ├── 70d38343bb29e82cfdacaddee5adbb194b60815e.nq.gz
    ├── 7143b21f5b5b205f7c0c7b49b61599f4b0632e82.nq.gz
    ├── 730ec9eeddc5ba85b8028dae7504122407a729fd.nq.gz
    ├── 73668ce2ee21305a9b7bd7c48e703c96cf84ba04.nq.gz
    ├── 748196b270e6cd033ad15e9c7c24e79030c1fd79.nq.gz
    ├── 74a0ed9f7dc64b8ac29b35a2c0a0c848ce226bf4.nq.gz
    ├── 75584ec2113a90f3df8d281468d40b7859874c5d.nq.gz
    ├── 767e93ea28daa9c60012ad0b3b8f9d38759e6efb.nq.gz
    ├── 789c5b02e12ec5cf65a322b3f0a054f8022de139.nq.gz
    ├── 79b39f95255ea8261eedcb21c16dc52a37a7bf76.nq.gz
    ├── 7a49d04693cce92a653e6f6c112c988b318a2cc1.nq.gz
    ├── 7ad75a2e32767ca6dbedddc13bef238a5f6a393e.nq.gz
    ├── 7b5a1399fda39c0919dbd785d52a651ccf433f96.nq.gz
    ├── 7b9ac43025926ac6e718ca48a43f91be9ce9470d.nq.gz
    ├── 7ce6a69212328643582f1aa8698a102b121f1e74.nq.gz
    ├── 7d913fb96fc7925688eb1e763d382769f96149ba.nq.gz
    ├── 7dc421c61517303c060418b5495a64a226a9f7a8.nq.gz
    ├── 805e9c45ff1f1404f7e3163b5a2de571fca104d0.nq.gz
    ├── 81d6d92191c42387a055bf662724e4a2ab65828f.nq.gz
    ├── 837a3bcd7216714a95d3dbac9c7daea8c9258d2f.nq.gz
    ├── 8481f3ea34638c7575e34317fb24c1b7ce25a15c.nq.gz
    ├── 84f75c677ff34eae0517277c88167b0ef0db1642.nq.gz
    ├── 8543811f0522b088c3f77f2fb42ff06a7cab8e8d.nq.gz
    ├── 855285673438c26860825a354e191b5da275ac0e.nq.gz
    ├── 86257006a53d38bb2415dcd57a6372d343e9a49a.nq.gz
    ├── 87ca99b9ea0dbdb1e4a16d834bb76a618d4856be.nq.gz
    ├── 88bfa0c445d5bcd50fe0c37cb86ba5b3dd1a31f3.nq.gz
    ├── 8968ab28f9b7dfb737e4fc1fa111444bbb38ede3.nq.gz
    ├── 899070b9a931c78bcbe32d28d5cdcfd2abd0b81c.nq.gz
    ├── 8d2f21f4f81c5be3a62e595d603966f9083e5159.nq.gz
    ├── 8dcef443f214f412d843930a762fcb4398d4b0d0.nq.gz
    ├── 8e1a8cdadf2c5d3d0ca3c9965c7268ba37facabf.nq.gz
    ├── 9006e8adb61b120d1052c6a50c6d473828648561.nq.gz
    ├── 90b5db3c2c879bf6a4305eb3dfdf5cf8cd3c9b90.nq.gz
    ├── 9277c32a30684942264ebf65bf44d478e483421b.nq.gz
    ├── 92c6c046366ada193284de7c71eb069ae102835e.nq.gz
    ├── 92f781d800a60946eef8441ea6a1fbcbc21541ba.nq.gz
    ├── 948f7d01879087bef267e2416ae7537e038016bb.nq.gz
    ├── 95d1bb073402c78d7f43560eda7014ca1a27912a.nq.gz
    ├── 9788ebd38457328b0666d21b627ea8acd4841d3e.nq.gz
    ├── 99598eb01766f838b130ff04c02103c1418215e1.nq.gz
    ├── 99fc13e7194ed00739da798b650c13bdbaa950bf.nq.gz
    ├── 9a3ce4ad2c0087fa73160e5fd668cb31812fad63.nq.gz
    ├── 9d4254b127fc23fc5d7f9a63f51144b637388c4f.nq.gz
    ├── 9de49f34a7dda7dfe9656bfbc7093f1f3eaca335.nq.gz
    ├── a03590f54d8b03c2bee4276a20b3bf402d26b06c.nq.gz
    ├── a1339f22ff734f9b37788be02ccb8ef9cfecbfa4.nq.gz
    ├── a445c2ce4e62e04a55840eda5dcf350ad636e066.nq.gz
    ├── a51f8960b61e6fc4f343274660697be1e63aa577.nq.gz
    ├── a5aba7e8f2ca3feb7a16589f2e83867594f4b6b1.nq.gz
    ├── a690f3c79fa2ea5a6bca382c5c0e479e11b2beea.nq.gz
    ├── a7397c6fd1a2b28da7520f961ee255ed61346b78.nq.gz
    ├── a8ada1523209955cc14a1a346d108b6c628f88b7.nq.gz
    ├── aa11045126ffef4eadf4b92ed2c67f0da8c59f82.nq.gz
    ├── ab40a620605352a089008b2771a9dd15af42888a.nq.gz
    ├── ab511ab9883a80687360228eeac9c01de1f49ee6.nq.gz
    ├── abd939e54b744a7acdc651c1f9c389496b944f91.nq.gz
    ├── acd659bbe47b6fe72cefeef6f0d8da68c4b2130e.nq.gz
    ├── ae21622ff55e8c55b64dc91e0d02cd66b85f8023.nq.gz
    ├── b0571c38ae5d0259f7b470d9782a956d59a8958c.nq.gz
    ├── b1c9e2b20c6f30ee7a1acd29cd5dc846c36640a6.nq.gz
    ├── b3a7958659d97a3ac48bb23a43e57a2d35f80ea3.nq.gz
    ├── b3b6a1dfe5ba61a85fadbbd83d26c8f8f7c8d3cd.nq.gz
    ├── b3dd1b506511ee662344a3f2aedb122bd662d0c7.nq.gz
    ├── b3e01f11ef9c75bee72a1b6f6f0b746fe8125a09.nq.gz
    ├── b43bd86871b4f77edbb71b648aa9b0f5cbdf7bb9.nq.gz
    ├── b50c4f479ce24d15182d24a281572cd55e0c41bc.nq.gz
    ├── b5e7a985e9a81ed46ee6c5ec2b236dccb06e9f3f.nq.gz
    ├── b7621f902645271630dbf15a7e593538c1e70e4f.nq.gz
    ├── b79d297cca9ab9d45fb43a2bcc241611b0091508.nq.gz
    ├── b868311eecc565844955aaf19e545ed18fcc40a6.nq.gz
    ├── b97c0a129f5267ea961476074c4912f488d96674.nq.gz
    ├── ba823856ec5adf4ff71d24aaaaddf129642467de.nq.gz
    ├── baeabe16d0c3f33ed67a22802546949e8841c339.nq.gz
    ├── baef29d1d7b59c930c712cb8c1ba3bc27ec36616.nq.gz
    ├── bb5081b53202cc628ddacf56dd42da4dbaceaa1f.nq.gz
    ├── bc442f6b99306b37cbafcd1abb573c6c429e5c2a.nq.gz
    ├── bd0e503f2ec43af1ffb95f49dcd5fff193dee813.nq.gz
    ├── bd42796df66b1dc35ad0e02ba8cdd7592b0d42d9.nq.gz
    ├── bd7f889b5034215a21b41bcd19afc4b24a90488c.nq.gz
    ├── bfa473bce166c086cc049b7d3594b6c2e0f1f398.nq.gz
    ├── c01da2327c411ce023bb868db2ee39aec804e095.nq.gz
    ├── c11355a99e5f61a854ab93f16d07a28962585e15.nq.gz
    └── c144d8dfd7704d4727472c3695c32dddfb0b8959.nq.gz

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

[pypa/virtualenv](https://github.com/pypa/virtualenv)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
