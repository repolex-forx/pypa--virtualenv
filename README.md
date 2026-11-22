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
│   │   ├── a5fb4a290d60776e2b3f81696bd7291913aa25d4
│   │   │   └── chunk-001.nq.gz
│   │   └── a857a7823c73c35935d0318b4f36e5d582691e1c
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── a5fb4a290d60776e2b3f81696bd7291913aa25d4.nq.gz
│   └── repolex
│       ├── a5fb4a290d60776e2b3f81696bd7291913aa25d4
│       │   └── chunk-001.nq.gz
│       └── a857a7823c73c35935d0318b4f36e5d582691e1c
│           └── chunk-001.nq.gz
└── blob
    ├── 005c23640b12996418831b6dfbe64b9bd7e97188.nq.gz
    ├── 01d0955a6dfd9ff70c2a3c86d7aa6e4e82da2f57.nq.gz
    ├── 02b865bfe4ec64bcec92d40902bf4b109bb9a9a2.nq.gz
    ├── 02c75e9ac1cedf3585d43ee015dbe476502ce5ca.nq.gz
    ├── 03dcef56a5f6eea0cf2579fb5f0624831f7145a4.nq.gz
    ├── 0466460b2f0c844dfcfeddf3de25dca8b925e97f.nq.gz
    ├── 04f0acb6c070d012189e140a1c2fd8e2e041e661.nq.gz
    ├── 050eed9f52ce4535a030cc15608d5a168edc098c.nq.gz
    ├── 052f56fdd46fe6f792730cf3d8584f5264e286ae.nq.gz
    ├── 057c741cd6acaec1cb679fa3f828793408465220.nq.gz
    ├── 0612fd1a5dbef2a7faaeb63aa2a8f679b3ba28d2.nq.gz
    ├── 06192921fd2bcc84ca852788e0cd4a26ee998000.nq.gz
    ├── 065d48e0026e13015addaa8669d4ddc43a5cd361.nq.gz
    ├── 0708672106d090f36458201efb90ec24114347c8.nq.gz
    ├── 0806ee5dc30853e8efc82be5da8494248437148a.nq.gz
    ├── 090396002eb759c78f030c5f6ca95e0614de0e3c.nq.gz
    ├── 0917872bd34669c29f77575b233ed039fa112e7b.nq.gz
    ├── 092ef74bce62087e57b10a2f796a4e6c18a021e6.nq.gz
    ├── 0954eed3afa075f61cc9553ef30d0f2efbf06118.nq.gz
    ├── 0a6580a9bb0c76d67564434e95655e4f95a6c894.nq.gz
    ├── 0a88fad758a6188f1142425aa6781e1e0c5a96c4.nq.gz
    ├── 0aec184f8ca16e0b6fb8407e846758e3d9de5364.nq.gz
    ├── 0b49d1868e1f97c16275bff24c851428f6cd886a.nq.gz
    ├── 0d5dd54c3034c1509fb6720ba3e086678996c9dd.nq.gz
    ├── 1164a23839185d001f22418e18ddf0ca366008b2.nq.gz
    ├── 11f48a6719a052c1adc689b39afd182adf860767.nq.gz
    ├── 12794f047695fa05937a81477d5536dd2637cae0.nq.gz
    ├── 133e1e31c444572855effd38d7042d9eac3b30f2.nq.gz
    ├── 136c1b4f62ee5ccef56d6272f49894bcab56fe9b.nq.gz
    ├── 13a6c7703476c2a47d98db4358e0fda414898358.nq.gz
    ├── 13bb94fda8272f3e528a968f531cfb9d1b3e78d4.nq.gz
    ├── 1534d34c2f7f6c2f5527058881747c81636a9601.nq.gz
    ├── 1594a93128dcc723b7bb2151611f274c48c17e39.nq.gz
    ├── 159a3e99f54d59465d39b59cd740c7aa80358cd6.nq.gz
    ├── 15d90e215de88b00535af0a3fa506e0ebe8a9206.nq.gz
    ├── 1612a8b627857b9c8550356315268b5ada96efc2.nq.gz
    ├── 191f262678aed3e040f16f656edc7ab49bd43536.nq.gz
    ├── 19af92a039caf5499ec9861a3e967207e6a33070.nq.gz
    ├── 19ce0e64bf1673a32c0d65928b8f296d810d542d.nq.gz
    ├── 19d9a782b99a7cd9ced0e53782bc7d24ea523318.nq.gz
    ├── 1b3dc9886faeb07a8f68c714c7fa0f2ab2a972ca.nq.gz
    ├── 1cc9cf633b419f29a0dc6abd4224c43d14141ed4.nq.gz
    ├── 1cfffe26603c89696ad309941f35c7c4b91416db.nq.gz
    ├── 1d8be7311d9eeba8a201ecc3f2742c4cfbe43304.nq.gz
    ├── 1da339701308420e89a841b88c6583a9ca9cb498.nq.gz
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
    ├── 22b635337cac88f6d9582f46c9614053ebdbc981.nq.gz
    ├── 22bb8dba79c336369447326bc8d4df60d6e311f6.nq.gz
    ├── 23bde801b53a4499b1cbc4d6b43ec3a6aa7011a2.nq.gz
    ├── 240150a3837d2e753a90c09aa1a37b8d644b82f2.nq.gz
    ├── 243691994eec1ede5aedacf02fb1a7d9446b3bf0.nq.gz
    ├── 24c0afe4566b4f9b6abd7fe41088724987423771.nq.gz
    ├── 251308ff4256e1d4086b14a1193ab12d349b3470.nq.gz
    ├── 25878957b105f07a64cdbbd43cd4943f972bbfd9.nq.gz
    ├── 2587a7ae7615a48d17bd9b3ee86d513f2c6d64cb.nq.gz
    ├── 2590fe1365bef62bce1534ca82d21b25a411691a.nq.gz
    ├── 29129cb4fc9ebc026d4dbc4054e91685e746bbf4.nq.gz
    ├── 2965915b44e96a6a0cadb68d6434f59fb40692dd.nq.gz
    ├── 299fb26f0602b4661139737cd24579fd08423455.nq.gz
    ├── 2a1676d95dff1cc7194c08a95c5827f30a301264.nq.gz
    ├── 2a1b732f792a193d2536958f912ebbb937f98686.nq.gz
    ├── 2bb5a5d4bccc67edb3236c113c891e190ec9d063.nq.gz
    ├── 2cbca4d3347586c512acd1d3f60229858f75e4ef.nq.gz
    ├── 2cdc03838256d5409232df6e198ce36bcf897605.nq.gz
    ├── 2db749a77684d3128ea8cfa9761ad281e51382e1.nq.gz
    ├── 2ead4a38da22a39caa062018ebc16aa1d6ffa100.nq.gz
    ├── 2f6d9676755253ac5d1750bcf61df57b58dd962d.nq.gz
    ├── 2fe44d67a0cfc9db69f294c0a8781ab46d4d8d10.nq.gz
    ├── 30a5f6cf9b895d77ad28f6a3df8dbe78df8b7c12.nq.gz
    ├── 31401dad663a002ad6f00cc7e9222838b351a78f.nq.gz
    ├── 3289388713f0ca3e84e4d886c5a839cdaff64e66.nq.gz
    ├── 3398ac2c59aeaa5c7efa760ee7d1f725236a9b2b.nq.gz
    ├── 33a1615f747bb4c03a66192eb72e933acca38c9d.nq.gz
    ├── 33a8c7fc4d96aaa20d80b5992991d0605ce6c7db.nq.gz
    ├── 33bb22dedc77f897765a0c3df2731fc7c0c6b52c.nq.gz
    ├── 36663b72949bfa0eaf191180983ec7ea1779746e.nq.gz
    ├── 377b58e0616a8c544464695281e6a6984936052a.nq.gz
    ├── 37c3a5f55a071a714d4811b2d97a0a0247be333e.nq.gz
    ├── 3879fa271a04b07daf05891e9513ed203bb435e2.nq.gz
    ├── 3886f91ebea6363cea2881570eb44815e89412f9.nq.gz
    ├── 395e77116d8ecc61c9c20044cb31da7ec3e24f1a.nq.gz
    ├── 39d5a3b90ce47f540cab018c5bd451e72b6fa43e.nq.gz
    ├── 3a374f1c5ed91fe18e17fc72082fde18fad4e9d0.nq.gz
    ├── 3a8ad25dcd04b2aba9f0eacbe73974ec65d2cef6.nq.gz
    ├── 3bec218a7d5d8f7bb4a3415080cf73cadedd10b8.nq.gz
    ├── 3c75558ba646847aa81650b84e539e222f796b04.nq.gz
    ├── 3c8280ed8d21e649d864717ee79ac70af7213898.nq.gz
    ├── 3d7626e54730a8809342da14cadbaa58a7904b04.nq.gz
    ├── 3de6726b2e9132aa1edc9b3269f096e2bdfaf394.nq.gz
    ├── 3e591344e959f42168e1210c9ba35ac327143223.nq.gz
    ├── 3ec017d2bb7b0235f7af0d667cc88a53a9306679.nq.gz
    ├── 3ec4147c55316f1bdcf85bf15e5bacdce573e280.nq.gz
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
    ├── 489517514710404307d14eac20161e35a3f28a91.nq.gz
    ├── 48f2767c34a3bfc9f1ed5444102416a83856964e.nq.gz
    ├── 4968d0aa00376b20bae6c76a1c9cce9b6fa657c9.nq.gz
    ├── 4969daa17a480bdfabc8f19c6659724fbc57eaf7.nq.gz
    ├── 498e3db9c7b3fc28e3f0d37eac14db339a3bd7b6.nq.gz
    ├── 49e0f24248ad95fb206cb825f95b59a19bea56f9.nq.gz
    ├── 4ae6276bec843df2e53b603e407057da9adc0b38.nq.gz
    ├── 4b2d72f2567bc8ba9d149817ec790612bd5ba260.nq.gz
    ├── 4ba74a12a226c6ba4bea39caa03d6df2a77c1e93.nq.gz
    ├── 4bb03ae1f3a4141df93ff938f09076e7cf60950c.nq.gz
    ├── 4bf391107903389f32831140b1bfce1e97fa058d.nq.gz
    ├── 4c8cbe63c5fcbd00b49a091c33623b6519419694.nq.gz
    ├── 4cacd34c27d899aac691852d2e88054d205b36bb.nq.gz
    ├── 4cb32956934bf10cee5d6c79f5c5879978f3a859.nq.gz
    ├── 4ce911622e62c9f3a7f2a77e92aa00b7743e5fa6.nq.gz
    ├── 4d28b78663658f451251e5c4db88574f41c59c3f.nq.gz
    ├── 4dd83756a69f2893cd74246ce5ed684a23942c72.nq.gz
    ├── 4e1fd6ee82b95504ce21fb182770fa037d0fdf93.nq.gz
    ├── 4e6ca4dda7ec6e7896a5f6cb94056252ed044b7f.nq.gz
    ├── 502f32a607a13d6fbf9e9f2ff8c3357abbb98536.nq.gz
    ├── 5115865933a5d301dead1c0d553773bdb7725293.nq.gz
    ├── 515f7b7a0419689a1e4b54055df0b6375c9ffad4.nq.gz
    ├── 51f6cc97daab22c85109b71d8d52292ab4eaf9aa.nq.gz
    ├── 53ced18b2560e405767308dde5ef0176e9924aa2.nq.gz
    ├── 5498c01304bb0138e1a57b2a918887b6ab590c29.nq.gz
    ├── 559872d237692869ff9c208349bbfef7321b8f95.nq.gz
    ├── 55a9645bddaa8ef1741302b7349e088ed38e1086.nq.gz
    ├── 57193ee7c886b0064820606e42adba7523af157d.nq.gz
    ├── 576b5665108fc1b1ae1be9872c6309b7d282e488.nq.gz
    ├── 580d09a920422fcabbd462c937d08c96dd7f08bc.nq.gz
    ├── 584b0694551c39cb3c17301a5c4783fedea298a0.nq.gz
    ├── 589308a21938f25bd1300dae8ffd7488a8df00ca.nq.gz
    ├── 5aa4a9d7691dc44168553afa31aab43fde2c9adc.nq.gz
    ├── 5ab576a2f82def0f7c08e0baa1eb19ce3e683715.nq.gz
    ├── 5bd62c7f5f33b35e8688e0a2b11247d640db31be.nq.gz
    ├── 5ca60c5d69315c49b8e1581c4fd96f320d918eaa.nq.gz
    ├── 5cb8e1297c45644e7236600e058391d615a65d91.nq.gz
    ├── 5d75002031e2256bc59e21893d1bef587b40e18c.nq.gz
    ├── 5e1a8c4df9e475b4f1d262dc5141012741c088a8.nq.gz
    ├── 5e3e87dcc63cee828e15260a27e553ddf6a8cad6.nq.gz
    ├── 5e4251f206bc9cbe7c602962ce69f3e69ed8c431.nq.gz
    ├── 5e525f0418646d64e749ac83876e63b7ca81cbfe.nq.gz
    ├── 5f89818f9e63c2f6829c7706c57f223cdb5bbd38.nq.gz
    ├── 60a0d78be14ac1cec446e0d8c77fc41623e5971e.nq.gz
    ├── 60e9a43d06dff352df965aefb7bef0ca410cabd7.nq.gz
    ├── 6210c1cdfa343169791d8ad111c7182cbc63e317.nq.gz
    ├── 62e583555b46c7217a9c9812efedc264aa6df6aa.nq.gz
    ├── 65c2f4ebd850a5ac0e9e514a160e35f56cccc30d.nq.gz
    ├── 66ca61f23d124632cc094c1427fc29a325f16ede.nq.gz
    ├── 673ad3129b81acf9b052bff24babf57d13210e03.nq.gz
    ├── 6753fc20a8f711444a1848ba60bbd258822ef443.nq.gz
    ├── 6761921d0c9a54ae9fb40ba00fd93df9c712a646.nq.gz
    ├── 676720afe38e2f35435866e9b8155f626e3a0562.nq.gz
    ├── 67695d3ee849d1fb51a457ed9c3708c20e673f40.nq.gz
    ├── 689337387ead83c332403a0ee1780825e292eacf.nq.gz
    ├── 6901850fde266cbac1b84a93cbe3e5d0f13ed53d.nq.gz
    ├── 69a4b67c8d78af48e76669ff0feab6400b83f09d.nq.gz
    ├── 69a6e607a2533ecbfac478bce83b221fa4c3a134.nq.gz
    ├── 6c167c287c64f1e26bebb206add6d8352fb57610.nq.gz
    ├── 6d701b906d440bba9b90a1a321a9e9b813182457.nq.gz
    ├── 6e92e2f5f7c4da1d6c3aaeb689e6b1d00d269d9c.nq.gz
    ├── 6ef5df0149e2cf21c70bfb7100cb3894d611b896.nq.gz
    ├── 70bb24b6e97a5c270ae1342abdc216968fa9ebcf.nq.gz
    ├── 70d38343bb29e82cfdacaddee5adbb194b60815e.nq.gz
    ├── 7143b21f5b5b205f7c0c7b49b61599f4b0632e82.nq.gz
    ├── 71d71525b16888b34407bd7d0205718feefdbfce.nq.gz
    ├── 730ec9eeddc5ba85b8028dae7504122407a729fd.nq.gz
    ├── 732f95f0cdf57d5624ed1ebe7164f65383236bf1.nq.gz
    ├── 73668ce2ee21305a9b7bd7c48e703c96cf84ba04.nq.gz
    ├── 74300db75de73bd4fc5afabb2d8eddab6b53cf18.nq.gz
    ├── 748196b270e6cd033ad15e9c7c24e79030c1fd79.nq.gz
    ├── 74a0ed9f7dc64b8ac29b35a2c0a0c848ce226bf4.nq.gz
    ├── 75584ec2113a90f3df8d281468d40b7859874c5d.nq.gz
    ├── 76341c52a977f5fcabeabc6785952fb224e3ab40.nq.gz
    ├── 767e93ea28daa9c60012ad0b3b8f9d38759e6efb.nq.gz
    ├── 7754a8cb968965c7f2f242f0a559476235a60e6b.nq.gz
    ├── 7882e7f45e56fd8a567ed4f858b1831042b8402d.nq.gz
    ├── 789c5b02e12ec5cf65a322b3f0a054f8022de139.nq.gz
    ├── 78ad552c5835864f200a348a8835af6d17c8fa59.nq.gz
    ├── 79b39f95255ea8261eedcb21c16dc52a37a7bf76.nq.gz
    └── 79ccab7401680a5ef76ed96d5a0ff8ddcb089602.nq.gz

10 directories, 200 files
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
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
