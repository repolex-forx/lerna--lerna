# Repolex Knowledge Graph of lerna/lerna

RDF knowledge graph data for [lerna/lerna](https://github.com/lerna/lerna), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download lerna/lerna
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4322536e385c067afe743c089430dd5cfe35d010
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 4322536e385c067afe743c089430dd5cfe35d010.nq.gz
│   └── repolex
│       └── 4322536e385c067afe743c089430dd5cfe35d010
│           └── chunk-001.nq.gz
└── blob
    ├── 001c2742cf0d0539349a80c147fc9175faf35cba.nq.gz
    ├── 0056dcc29190c0d94c448c80b09bb98334f0c08f.nq.gz
    ├── 005755a1df65190eedf5a25b12f742fdc6f25b7f.nq.gz
    ├── 0096560486bf016bf41f699198fd64b268f67252.nq.gz
    ├── 00a88993a7f46ed16d8037e49b0039970491148e.nq.gz
    ├── 00acb49ace75c692934680cad63c6778f6185ecc.nq.gz
    ├── 00fa5a6f5335afb90bba14427528f969c2124531.nq.gz
    ├── 01152693a0cd1016a75b6a950daef03e5c6d0717.nq.gz
    ├── 0116fafb7cd2a0e258b69c0eb1ebfd11f7a0f7e4.nq.gz
    ├── 012662351a78bd63fe4d7fe3e98e3648b30b6c33.nq.gz
    ├── 012c971fd8dd7a63653d43c9739b9a024dc5390c.nq.gz
    ├── 018e93aefb0683b2552088db5162e17f680b1cde.nq.gz
    ├── 01a125568385911fc6f6b36b52b40301b90930fa.nq.gz
    ├── 021cbf091448218008b549c731831d88aae885f3.nq.gz
    ├── 0240f2df549b2164bff0b4b64fadb432ffdab1cf.nq.gz
    ├── 025de7c9c958f5b5f4c0885565327687b7a82bc5.nq.gz
    ├── 0263c64c699cef1de677faf86736745065da8477.nq.gz
    ├── 02774b231323212a68e779c84daa0a666e7ae2e3.nq.gz
    ├── 0291b9189cb733621f3be431c4e3b1c485325e2a.nq.gz
    ├── 02bd6610c9f09dfbf0b5a2b207967f7d4d3f8a8c.nq.gz
    ├── 02c615af08a838927d333798db322201a812ba2f.nq.gz
    ├── 04080aebef3707deee3d88e38b32d1509457c623.nq.gz
    ├── 048d5e9b9309d046468263b8916f627b8f84697e.nq.gz
    ├── 049512c7c8e48d6f826a06f7feaadb42b942d0c8.nq.gz
    ├── 049f833040f066578b2650b06913d76076718df7.nq.gz
    ├── 04aa79da3e8c5c4aa9d13c257d95d537c256e1c6.nq.gz
    ├── 04d242c15b11ebc90d1df8a54629a5302dcc66d5.nq.gz
    ├── 04db3f5dbce70f5fa78bf7846caf53dfe443d99c.nq.gz
    ├── 04ed15ddc9a81518b02210ba5477985e939204ca.nq.gz
    ├── 051984b465ee642db0eb7ae9a33f7eab7880a49e.nq.gz
    ├── 051fb63194d93c492c5a459dace64e7f8a075f43.nq.gz
    ├── 05bf2bee288a2314a07ea82be02ebf516411e304.nq.gz
    ├── 061a655d08e8a41dc34127667d166d6173bd9a51.nq.gz
    ├── 06af252b200acc241e423329be303d96cee728df.nq.gz
    ├── 06ed4610b64737a2248a2bf2be43134298e9a814.nq.gz
    ├── 07578f61ca7c2565d251e7e846f9d24392ae2fb1.nq.gz
    ├── 078ba428b408dcdac293a3a7532eee0ef8bdd735.nq.gz
    ├── 07afd393814bcbb2f3f41cc969fcd98d43bb620e.nq.gz
    ├── 07d0e47016c620dbb84e40fca1147b4d06baefd1.nq.gz
    ├── 07d4f3ec352ea5e0bfa90b5e01e49f671f61bd72.nq.gz
    ├── 0831404e501be7f6da967d3015c1e7c46fae2391.nq.gz
    ├── 088215bfe54ce334743e55341c0013286e7e5737.nq.gz
    ├── 08858d0c068660577d05aff89fc54bb0de60b653.nq.gz
    ├── 08b39868e87dcc9acddd8e2fe62d65724197e129.nq.gz
    ├── 0909fe70b2daddd66e5ba6c1812e2e6a496173d7.nq.gz
    ├── 0922bab45fdaf7957fee9547f7b4fd68c744942e.nq.gz
    ├── 0950f8db089c32abae8f0364fa4c40b2b214d1c7.nq.gz
    ├── 097f4148273e1c73310037b4b938efc4aee15c26.nq.gz
    ├── 09a16b112de690a63a4afc3ee9675a71a681698f.nq.gz
    ├── 09fb774a3702b5a1b38bc95bf52a5053d12532a1.nq.gz
    ├── 0a2b674fff8ed7cb88ba0425cc92face0663aa92.nq.gz
    ├── 0a3d970374c99d99ec7b5656a5d8e3ecdc037670.nq.gz
    ├── 0a46b8033666de87893c9219de6a7a996839d059.nq.gz
    ├── 0a54232fce5a778130732f34ecbc30c192b4b603.nq.gz
    ├── 0a986be2839854369f9a99fdbeeebcc3f21ba7de.nq.gz
    ├── 0abe2ab7f816ccf1b4cb076b30adaefe3d2d1cb2.nq.gz
    ├── 0b408fdfb5ac9dd5f1f1f0095404df556f14ca6c.nq.gz
    ├── 0b4258351e0ea586e49fb8b7daf131fa891deaa5.nq.gz
    ├── 0b9506b3a3d78915a60098ba45b6e5bce575ae3c.nq.gz
    ├── 0b99994e720f376c4b368ec974ddc965813ddd4e.nq.gz
    ├── 0bbe32281e0306a5b14f919d2e6fdd4488db2f16.nq.gz
    ├── 0bda09b8835d678179d44f2b66f66fec13a84e57.nq.gz
    ├── 0c1748748b049a592535f31f3c9cbdc654941d7f.nq.gz
    ├── 0c3c0d6207b5d9751994c4acb841c9e6e19b990c.nq.gz
    ├── 0c3f385c6a2d00c5c5ead93be97e5af4f09247cb.nq.gz
    ├── 0c5bdd53ab6e36ce1c6deb12a7ecbb5022a55762.nq.gz
    ├── 0c759aab57afb9e8ee4c75048ea27c7965dabb4e.nq.gz
    ├── 0c7735e083e33952e546ca25b3aabaefac3c6166.nq.gz
    ├── 0cedd3e41733c1f9e31f78a29a0cbf08e9c086d9.nq.gz
    ├── 0d04899f572cf0b7ff152baf94dfea22166d6cd6.nq.gz
    ├── 0d5d1ac386e6c9a4e21e271940f6527231406292.nq.gz
    ├── 0d6d69b78777e13ed220deb5f9de7bb639391c4f.nq.gz
    ├── 0da10e6492e064afa27d7ed77d9fb337c26905ff.nq.gz
    ├── 0da3949ca9d6ee29a85af04d41e01ff50e21197d.nq.gz
    ├── 0db12ec125d170f9b415c330b83709ba6611d1c5.nq.gz
    ├── 0db5c8b75dc4ae8884e0327adc7f38614b887145.nq.gz
    ├── 0dd14efbf75e286f631a7a6153f5246241678901.nq.gz
    ├── 0dd22e08b9b9a2c00bc01832d8f5ca4ed7b76af5.nq.gz
    ├── 0dd5e50ed760a3d9a17324075c27f1fcf057b54c.nq.gz
    ├── 0dd6536aaa6b18ea7b97cc454f35bbb5ef3e3c46.nq.gz
    ├── 0e0bbf84e3ad68cc4c5d92fdee6d47f77a990a42.nq.gz
    ├── 0e72a417dc61e280a42a85e8ed4008d00c698cbd.nq.gz
    ├── 0e77c1e3bb79c752ee51a42e69890d14212dfb9e.nq.gz
    ├── 0eae769845c950d1730f29f14127b35e15c24993.nq.gz
    ├── 0efb931b8daa0f06a54399ec78db18e5e4a3eee8.nq.gz
    ├── 0f930f46571f37e1e4e9485e7c0b4c4062b2725b.nq.gz
    ├── 0fc52f5ca1093d02579ef7afba3beb86816a2969.nq.gz
    ├── 0fc884f90096ca72c28d079404de1e91b9ade5b4.nq.gz
    ├── 0feea1704b0e8e18d5c61b294c8f291a8df76d13.nq.gz
    ├── 100c0063676c12fa2369aecbfa6805d789e0d843.nq.gz
    ├── 1037d133e3295e5351ef48acbc00042e8b18a57e.nq.gz
    ├── 104c796d2c86a91845cc4a6e9d2cfdf632c1bbc5.nq.gz
    ├── 1051e1bff01b8c33a87a5bc34f3e4a0db6fcd2a0.nq.gz
    ├── 105a363b1fb7b34872971e3520e00f197fc72788.nq.gz
    ├── 105cc0f98a1413a160a9483a3413413ccc72f59a.nq.gz
    ├── 10a7dbc4c3e95531db5be0fb6d082a44fffe0848.nq.gz
    ├── 10da5081672f27fb4046e33f501518cbe65405a0.nq.gz
    ├── 1155bae0a46f2b387f7d1259ddf2969b9d5d0f84.nq.gz
    ├── 11bfd3b0b39db602fd933dd34bd418297dfa06c7.nq.gz
    ├── 11c1682d1b620815f11f731168148a15666ea97b.nq.gz
    ├── 11d0c0758fd20321bdda24886f3fd573092fc5ac.nq.gz
    ├── 12231d2e24f970c4f0191131cbe90be12317d6bc.nq.gz
    ├── 12517acd54b6a42915efe187be469c15c97d56af.nq.gz
    ├── 1259b7993d3a63b42620695db805726fcce52ee5.nq.gz
    ├── 12602432fdf393abb7a833abf5b567ae0066acf6.nq.gz
    ├── 1269a547a75a1a0c016087075e4fd8f9387b46ce.nq.gz
    ├── 126e262b41dd1961256f8357ea5be08da148db8f.nq.gz
    ├── 129512e2ffe6a9cd77473683223da829ac847d20.nq.gz
    ├── 129dc71bcc5a09311eb3587593b608fbf7f54ffc.nq.gz
    ├── 12bc76b5e2a08d4f02688b22c12884427b12b478.nq.gz
    ├── 12c8b0cbc79111e41b921a07f46d4654d516ea54.nq.gz
    ├── 1403ad4c3561d04784e35f41d1e1dad35d47d7d1.nq.gz
    ├── 14170add707ab47c3f2a2e2d9d3e98c01476cfdf.nq.gz
    ├── 14c127cf1d50478d0df4c5d74666e7ed891b2db8.nq.gz
    ├── 14c1c05601d84978e5db897ce481ca293af41d90.nq.gz
    ├── 15176de65f9dfd4085f13a194c67f0eb1123403a.nq.gz
    ├── 1587a669681c9a7e2aa097fbdc4b9882051fb58c.nq.gz
    ├── 16c89a5c2aa642f2b4d0aade97d95b538f49aa60.nq.gz
    ├── 16f8d35299b66f44f5de0339863c58e1f4e9bda0.nq.gz
    ├── 17057bb7df25c994cee88e4f203f2c890b508a79.nq.gz
    ├── 17d56085ae14ed945f36fabc0a67f4f4456f5f64.nq.gz
    ├── 1808539a893441d07a26b9bda1cf0a0416cd86f5.nq.gz
    ├── 1816adea85ad486645cac271c1d29af94ac868f1.nq.gz
    ├── 1929750c316265d498adf8a89bb2c76480eae4fc.nq.gz
    ├── 199db271c2ff90c6a49787c130b7f4770e5eccd7.nq.gz
    ├── 19a367202e80fd61d45f073e14288b8774e14a16.nq.gz
    ├── 19af7d8bb3ac85faf281bb20a9f0e9e904270dce.nq.gz
    ├── 19b9eece4df1455f1bf7755731506dc80ec399e5.nq.gz
    ├── 19cde7960425cf0a14b496d6bad43fbabdcd227b.nq.gz
    ├── 19daacaa0826b57bff64d2444a1048dab50b0186.nq.gz
    ├── 1a12e0c9b4944bcca1a9150bc766d86fbbf6e8f3.nq.gz
    ├── 1a386da981adf71c33dbbc0580074d4a29ce56f0.nq.gz
    ├── 1a5704c015c050a8b18e081dde6cd229ea1194c1.nq.gz
    ├── 1af456aa8cd95a0c7aed776aa1b4d6fea54775e8.nq.gz
    ├── 1b045fbeb2f6c80fcfdd051a8e9aa7020b7e27af.nq.gz
    ├── 1b0c905a0faee0103b9142627d0a8677a5887ed1.nq.gz
    ├── 1b4785beb08930d21781aeabcc3e4034b5345ce3.nq.gz
    ├── 1b9b4a5512854ddf6e3f90916b0e086fe9cc9af5.nq.gz
    ├── 1c33202096fd7b73e77305e5f967e261616ada35.nq.gz
    ├── 1c3cec088a7f5a2884385582c876638513ed86aa.nq.gz
    ├── 1c7a1afa892b12f7a758193446609e3a3bd87456.nq.gz
    ├── 1cf40355de25f1d23052617a8a8027d4cba33bc8.nq.gz
    ├── 1cf4cbf13c9f7e7c7717f26c9147f3ee08cbf98e.nq.gz
    ├── 1d018f796dde529fd102a3b8daefb93f4508ac58.nq.gz
    ├── 1dac71fceb631565daeb88911579a5d774609e2d.nq.gz
    ├── 1dd8438c4e7e18f5a7bd9789c90312aaeedcd287.nq.gz
    ├── 1e2cb89368a2dc0c7cc4256bc710bd395224a904.nq.gz
    ├── 1eb3e56de0f0754f86759578a950d52d618a814d.nq.gz
    ├── 1f0d27c974988b069adf6b26de230945e60dad19.nq.gz
    ├── 1f23ca6eb4b391ad76404d745dfea64d04f3aaf7.nq.gz
    ├── 1f9be65014e88febb628684d445ae85c2ee98b7b.nq.gz
    ├── 1fa32ea7f82296970fb34296732953a08eb2f002.nq.gz
    ├── 20008924a808f606a65a4d04a98deb94a760f439.nq.gz
    ├── 20310ed42111cd9b6e0a4ea0c8e9edb019901225.nq.gz
    ├── 20ad418c7fa129dd7f71bc3373265e306cae8d45.nq.gz
    ├── 20b944b4e6dbaafcf74b65adbc9d243b82539412.nq.gz
    ├── 20bd4b1f45e40b5c189618decf824428e950b089.nq.gz
    ├── 20cea2960568a721b99a9277ff0ada87783b73de.nq.gz
    ├── 20ffda36ce642ae12167e5920c3e123dd0e7cb41.nq.gz
    ├── 210652fa8acefd37b0c34277dbdf73d22741f6b2.nq.gz
    ├── 2165be7bc131bbf6cc8b64ef3179e7c1e256ca97.nq.gz
    ├── 219ebdd866d86b9fa783fccf90062b9d66842aae.nq.gz
    ├── 21d1a8a7a5ec8686ddf31b9a8b10aa4940c9fdd5.nq.gz
    ├── 21e205c759e30c4f8a8c8d2fdf36c2bb09267132.nq.gz
    ├── 21e31cdb74a86c93fb7de9d62fd2c92f80d2678b.nq.gz
    ├── 222a17fdb365d39f0e64beef1ec734661877b259.nq.gz
    ├── 22405011bed2919fcf4c003428a2cebd5cab47b2.nq.gz
    ├── 2274ba0453d719cb3918e368a759d7e8666953d7.nq.gz
    ├── 2355d147b14680f2bdb54db9a9aa6bc0fa5c8a52.nq.gz
    ├── 2384e0d39c8ea1d71db5d005892d50fbbd399663.nq.gz
    ├── 239180c1371219f044a3ec202d5a198338c63aeb.nq.gz
    ├── 23a671630b70adc0f0591c2c3af738ec4022e521.nq.gz
    ├── 23e70da3844604bcb9e31e68aaa9e2ffcdfa9aee.nq.gz
    ├── 23ea3c817d6ca967de3644c0ac32f1ae86572d3b.nq.gz
    ├── 243dcea8e33a3f7d6916fc9b50e6e7dd6e798536.nq.gz
    ├── 245c057088161632f0431876ab31c2b7f2c58b1c.nq.gz
    ├── 24d157a4ab56047eb5de318bbbc5cf7296a80545.nq.gz
    ├── 256ab45c3ad0b0a23af4adff2ccc1d19dadd6cc9.nq.gz
    ├── 25ebd9d47be6a9ae4ff55030ef3b6845eba859b1.nq.gz
    ├── 25f7201d870ebf9dc76b68f41fdc5044b32eab20.nq.gz
    ├── 260304d00fd0e8a4090cd91d86b1d1c546145b54.nq.gz
    ├── 266c1e2e4cb61880a8171250a11979afc856fded.nq.gz
    ├── 26ef046ac5e544a09e6c07a1da6d4067fc3f7ed2.nq.gz
    ├── 271c876d4043c2dbfc7a6e9129c453de2a22b730.nq.gz
    ├── 2765a3e25081a1c1fee5dbfcb5c0ebd8e4c2332f.nq.gz
    ├── 27679cff04d160ad928d783f12c1e17b5da8c47b.nq.gz
    ├── 2778755524f70ff5dc6a785e0624db2acf15653f.nq.gz
    ├── 278fd1bf173748f9ceafadc2a335128bc9b6bcba.nq.gz
    ├── 27f98ab2c41571dd9c0b1d6b55b1308ed41b1dff.nq.gz
    ├── 2870fa58db795a5f5457a16ebff248ee89c7bbc7.nq.gz
    ├── 28a946e9dfc1a70c206630d72b055582f5823dbc.nq.gz
    ├── 293ea7e032fafab7468211a55de5ff51b694507b.nq.gz
    ├── 29749da5fedbfd8ba4a29151838099c23606fc71.nq.gz
    ├── 2a785c71a5bbb474097493d781804c965149b752.nq.gz
    ├── 2a9b78305362fd95a5a19b9a27a32d134006ab19.nq.gz
    ├── 2b066371e3d56f34430e398e93701634d3c98a2f.nq.gz
    └── 2b68fb66ea8fd9d91de073bc677a36ea14678251.nq.gz

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

## Source repository

[lerna/lerna](https://github.com/lerna/lerna)

---
*Parsed on 2026-04-17 by [repolex](https://repolex.ai)*
