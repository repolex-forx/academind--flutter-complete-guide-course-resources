# Repolex Knowledge Graph of academind/flutter-complete-guide-course-resources

RDF knowledge graph data for [academind/flutter-complete-guide-course-resources](https://github.com/academind/flutter-complete-guide-course-resources), parsed by [repolex](https://repolex.ai).

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
rlex download academind/flutter-complete-guide-course-resources
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ec5eac129a0a7357930788564d307c6a0eb05c0c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ec5eac129a0a7357930788564d307c6a0eb05c0c
│           └── chunk-001.nq.gz
└── blob
    ├── 00985b7336c84e515c61530c08b601f0e61d0b76.nq.gz
    ├── 031e9782670617c320770e0a27ee01daab7a303e.nq.gz
    ├── 03836045044c92fc254cc4f19f7e51c28b1e3700.nq.gz
    ├── 04095a32150e57958492c7159da701832803cb6b.nq.gz
    ├── 041c7d22d4964beae627fe475e290a8893da9748.nq.gz
    ├── 0565cc87829305038c38d402b916d52ec8e4b6db.nq.gz
    ├── 0652e60be2cba7320a406bf944f9276e39dd3b06.nq.gz
    ├── 07c227bd78b0acb0d5dec4f20b4c149f1ebd2047.nq.gz
    ├── 087ceb24ccfcf0c9c303131f761eb464a1984273.nq.gz
    ├── 087e57b2ef2cd2f22621c1bc549a65733cba05b2.nq.gz
    ├── 08eac1437d4e71003be1f515b2a270843bf88090.nq.gz
    ├── 09ab44ff52617f419cb6a64fa6c82dba32b0bac1.nq.gz
    ├── 09b3e5278954fe91970f224a4cfa56f462aaa6eb.nq.gz
    ├── 09c13f6ad593ff9cbbce95483bf03fb36209cbb6.nq.gz
    ├── 0a4a5e815b0581fb2816b4a5c97ca108cdacd0a1.nq.gz
    ├── 0a755fb62f78d8ab74b21f04d32fc8556b485555.nq.gz
    ├── 0cf4beca34fb88dd0c750bb36911fb847d56f8a1.nq.gz
    ├── 0db38e9f8c64ca8b183fa347bb5839fd4f2548f3.nq.gz
    ├── 0ead03a95b403c267b8aea974e7400151fa7e9b2.nq.gz
    ├── 1291f74e5caf6d473c990858077b9637f1768dcc.nq.gz
    ├── 12dd2c7ffea52569c88b41320ff6b34c1f1826c1.nq.gz
    ├── 1327e410c2068a4e75eee65cc970ec288a5d00c9.nq.gz
    ├── 137de4701886c5041f01b3786f6a973de10cf102.nq.gz
    ├── 148e11fea8fa3356e5c37838b2f917a029767634.nq.gz
    ├── 148e77052b228b2368cfa1fcba686590960e24bd.nq.gz
    ├── 1640bb35531aef2f1afac1fb059a3fa9e216bff9.nq.gz
    ├── 16ba865fbb9d5a5e97a93219601d7658645b3d98.nq.gz
    ├── 16f9b9c9ebcbf7f83bbfe85bff7c15999119ab1f.nq.gz
    ├── 17cf5dd6d7abde055a2e69adb0f8166cad0dfdca.nq.gz
    ├── 18dfd2072d53f495d129b88d9952e59fb3844146.nq.gz
    ├── 1a848a3953dd357dc62791cca4408a4cbf736795.nq.gz
    ├── 1acc46495457b66127367bdb29f0729438f45f7a.nq.gz
    ├── 1b7af5e51806bb023387d85a9e391793525ce0af.nq.gz
    ├── 1b92a89f932b0a92979fb91c7744f9e2cc37ff50.nq.gz
    ├── 1bcd9aa48b0806e3b397435a176c6d9060488092.nq.gz
    ├── 1c23dfa8550b86bcf1d06e3a8ac73890c9fed5b9.nq.gz
    ├── 1ef3cd02b5387b5fd748ab3c81dde7251ee29326.nq.gz
    ├── 1efb8f500ebb421c3d6f5e718e0f7bacc9bd6f96.nq.gz
    ├── 229297c4224ac2a731aca543a08ddb50108fa546.nq.gz
    ├── 23d3ee04f22bd1f4166228dba662732fb5adb376.nq.gz
    ├── 2496d53016c0304ad43e3a8e7c808431bf105168.nq.gz
    ├── 251aa855c3ffaa8846796c5174cf76d0cef126e9.nq.gz
    ├── 2550b0c310d1f64fc5e979553e36a95031b0d0d8.nq.gz
    ├── 2559c9acf89a82935126d8d061744184b47e6067.nq.gz
    ├── 26207570fe67c97ccda71c128be368ba096810e3.nq.gz
    ├── 26dce01437e143d5504e7c329538b605a892ecc9.nq.gz
    ├── 27b19e180538f2254453ef8384739e69b27dc301.nq.gz
    ├── 2800296ad9f066a77af956c2b4fc9efb74ef2aa7.nq.gz
    ├── 283eb081a984f4d8e42ba34a76ae4c57509d22f7.nq.gz
    ├── 28a92093abdd448a0f712396f69066a627b4cfcd.nq.gz
    ├── 2910480f5d25da156b0e2f1b3fd69050158282f7.nq.gz
    ├── 29afb0335512c9f99a30918822ced1eda51c14c7.nq.gz
    ├── 2a3483b610779c51166066b81fb66099aa85b70c.nq.gz
    ├── 2b10d637326fe960fbfebe1d1084a733cd7b03c8.nq.gz
    ├── 2b83f4169197d45ad5b5f78ff77b555dbba60532.nq.gz
    ├── 2bca4b6b523a69a3dfb30d1129e114a5d15e5e75.nq.gz
    ├── 2d1ef97b2214348dbe705ae3a00adfcfa7922633.nq.gz
    ├── 2d2d8df7d1102610846d0900e02899f5fe787e53.nq.gz
    ├── 2e324cb51dd748fd8139dd20851b3e2e5a0c8fcf.nq.gz
    ├── 2e4a313439f7e553c28f58a91716811e46bb2753.nq.gz
    ├── 2ea96e7da2ec65df0dec57bd498d98d348a708ee.nq.gz
    ├── 2f1af3a3a243f49004a8519c199f0fd1cbb8fe41.nq.gz
    ├── 33a41a1c682483e9c7a2ea6f329a0bd6a3ece35e.nq.gz
    ├── 33d06285c840069b68322d622812b2d7436dbcf2.nq.gz
    ├── 3476b5b423830d4de9cd020f1232163ac10f2c37.nq.gz
    ├── 352203e4f0f7eef50ff6ab366f26bc707df4a09c.nq.gz
    ├── 359f865a32d99d191165420334b8651c2ecb51ee.nq.gz
    ├── 35c5b2330622c957bf558418109d45857b04f7e5.nq.gz
    ├── 361d0286a625326568a3dbd930334a837afd4702.nq.gz
    ├── 3671e7a5577dd3e736042ee23a89f6b23248ac28.nq.gz
    ├── 3683195c08e40b5f80c21a6b7f67a8149f19b695.nq.gz
    ├── 37dc1fc37acf59936c3d7c311c5623f67f60be21.nq.gz
    ├── 38c3f343ead899facaad3173e607248a9fd2059c.nq.gz
    ├── 38d71033df9b106e6fb61fbd052cb672ca55dfb1.nq.gz
    ├── 3c98321dd40a0cc999b86b5a07271485a9db35b2.nq.gz
    ├── 3d91c6bf81ecc86693dbf6dcfa1f731c32f5a4ad.nq.gz
    ├── 3f0506dae57be7476405352c4252a1db643025d2.nq.gz
    ├── 3fac5005c01ca9a8ac3952037f7f1578e36e31db.nq.gz
    ├── 3fc9ff06f6496fd1075b212ab7cbe4f07caad6c6.nq.gz
    ├── 40408829b4b7848923c4cb9e839c60dfcf64d248.nq.gz
    ├── 40b878db5b1c97fc77049537a71bb2e249abe5dc.nq.gz
    ├── 4131828cf1017f360272b98c3ec616059b65bdd4.nq.gz
    ├── 425a98789b3b47d931a4408af0671562f0108629.nq.gz
    ├── 426c322af656bea34aa464b3e73971b0609202ec.nq.gz
    ├── 43e7f8462809433568b5f58006cc9f2bcdb8a7c4.nq.gz
    ├── 44217c7cef466f2287b35945af9206a93c1e4cf1.nq.gz
    ├── 44b2421a2baf37f10c1d715a1d10b6628e062a4a.nq.gz
    ├── 46804f43475b39e1d35b171440341d9034b46693.nq.gz
    ├── 4770a40eae2509fc3e1786384cfef7313e67aaeb.nq.gz
    ├── 477cda18f47fffd85b1cbab4430bc69ea251ff88.nq.gz
    ├── 47cd024665efffbd98331c616b23a591f9c987ff.nq.gz
    ├── 47dc2101ca6e47eff898648a1dd666fd5177f202.nq.gz
    ├── 4885fffd0d9b3a64a692e23f559cc88630efd795.nq.gz
    ├── 496ee2ca6a2f08396a4076fe43dedf3dc0da8b6d.nq.gz
    ├── 4a034315bb0621ea34e1804e181821c575b7bb78.nq.gz
    ├── 4a245006ef5c7fe89ccaffc54caba0da65ce120a.nq.gz
    ├── 4d8bd0cf4ce3b2570fbdcae923f8027243834c34.nq.gz
    ├── 500c9f181172be3a45b0e849e3f95efeaa136f9c.nq.gz
    ├── 504771cec37d9885fd86a438afe91c8af7ae3697.nq.gz
    ├── 50a41b319916298a23bc46f9d314aabec6af28f1.nq.gz
    ├── 518682a379176f742b48fa292b4a36d1fa6ae165.nq.gz
    ├── 5188d3f00ecf1436d51021ae40e940dda5f32341.nq.gz
    ├── 5416cb673bee394881fb019296bcd09320a84d89.nq.gz
    ├── 5565ee765d24f2720ce8d10523de0815c72e662b.nq.gz
    ├── 5591037625fdb76c43b8192414898526eda9d5c2.nq.gz
    ├── 55f866c1b9a155abe4d17da5bed91fbd998c2950.nq.gz
    ├── 584d2934da05407f1208b4ed9cc612b85b369fd1.nq.gz
    ├── 5880e0a24c5a278fdf4daa16cdf53559ac020027.nq.gz
    ├── 59fa347b26160ea178181f089b3d2901a9a576ad.nq.gz
    ├── 5a3dfc41ad06a7974a44a461c76a44b09f650606.nq.gz
    ├── 5cdb5399763de4527fc00ef22d4d5326aa5cf4cf.nq.gz
    ├── 5cfd5e5185bbd7108a1594a66d6a141ba5d3df52.nq.gz
    ├── 5d72bb515aefb1d0ae69ba6e0bffbbafb0822d55.nq.gz
    ├── 5eb1208485b71010bb395fc3fa4fbded8f36253e.nq.gz
    ├── 5ef8162763f07fb00f821de1948b2aca98816fa9.nq.gz
    ├── 5f3a53619ddf5e3c25a0e856180a3a9d49409642.nq.gz
    ├── 5fa0c8e411c5a027063f97d4465e2b6b14fb64b6.nq.gz
    ├── 5fc4e5b9c5d0b135897300cdd94749a9b9f87940.nq.gz
    ├── 609306c11b722dcd678182cf55971112c66e890e.nq.gz
    ├── 63ee681e2c6b1c8da0ed7f324dbb699ac7d6d915.nq.gz
    ├── 63fce25be2d41ce5a963cfae660b809310ee9d37.nq.gz
    ├── 640a51ad707c6baba4b3a13c0357066c7e8963ba.nq.gz
    ├── 6449fb5d636152e6ade89cc2dc34c5426cc0f363.nq.gz
    ├── 6562709c56505a5c533cc6615822782f60fb6f77.nq.gz
    ├── 678305d02c5f45dd1b866bace8ec42faa5f37e71.nq.gz
    ├── 678b35611cd048c5db67c26b8aa3e6b235683ee9.nq.gz
    ├── 67d72e2c356469b1044ce75a5d0a40e6853e9c7a.nq.gz
    ├── 68de6ee99fb8c73b3bdb79857353fe901849b993.nq.gz
    ├── 6908df4123f3775ee3838fa4c0f21aacd5abeec6.nq.gz
    ├── 6956e6c6ea69a76660536d4ffe7d6a642151190c.nq.gz
    ├── 699d01aaa246583f9042fe2f732a3e66c5ec390e.nq.gz
    ├── 69c2023b5066586cc496d6ea23c32ba48f2caf90.nq.gz
    ├── 6a856c2e3d9e97e433b0de7a8e231a9158afa579.nq.gz
    ├── 6b899f7d06bc6219cc96d4bb83d5401257344ccb.nq.gz
    ├── 6d6f2aa43cfff08b9b9bff5b91a7e53b9d4bd29f.nq.gz
    ├── 6d80f09e3e6d981b8c49a29ea96b478a33eb99f1.nq.gz
    ├── 6dc6d2d7094f9defc487b458c5fb9b16c6985a88.nq.gz
    ├── 6ea37174f9c73121ed671ae8cd8d6ccd7c3a521d.nq.gz
    ├── 6ea952d47c4098fd6866205f424c2bcb6d1c3f0e.nq.gz
    ├── 6fc3ad07afac39029556516d0598d934ae88cd12.nq.gz
    ├── 6fd78d05b453b56c7b8d69f62f13b9b9da5a64dc.nq.gz
    ├── 6fea0f12523b1eb03d686446dadaa6c3fc3d638c.nq.gz
    ├── 7183984fdf30fb644a77ab13021850f2bc9637f7.nq.gz
    ├── 71e73be3f9638f7d761be0205b923f131bcf2378.nq.gz
    ├── 7259079f64026f6709f2a224bc51ab2cc227a6c5.nq.gz
    ├── 72d9f544e076b67d15c583062780d0308ef55170.nq.gz
    ├── 730ecd6a328c2b03ef1132d4eec6a97d510e0387.nq.gz
    ├── 73287bfc05449871d9b640ab428205bb13b1fdd1.nq.gz
    ├── 7377a880079574d7f1751ab80a1b8b5d36e77849.nq.gz
    ├── 740f3e240722f09c752172ee253bc9179163f0be.nq.gz
    ├── 7413372fcb748d4a3a5374b74b4646a8fecf6673.nq.gz
    ├── 742eb52884bb0a54772b444a49e7694fe626c6b4.nq.gz
    ├── 743c36c71e7821ffc5c2d3e2884aed96e3a70ded.nq.gz
    ├── 74b669b28d0714d4b9bd4d1f793a25fa9d510bc9.nq.gz
    ├── 756097023492f1d126817bf76b06fc7170a2ad2c.nq.gz
    ├── 75a9eb9f4c7ae328eee58d5ad288c7dd6c42ac71.nq.gz
    ├── 760f84d2a35ea2c9222d64568b8207d15ea0483f.nq.gz
    ├── 764ff8f6775cc7aef2d24b9a3afff40e935cc546.nq.gz
    ├── 775b6a4daaa907ea9e5f3cb5c41b1b47534b8a97.nq.gz
    ├── 7766d062c18730f92ee1e83c912e0d88ec4ddc33.nq.gz
    ├── 777c00c43b1e2493f8588e7bf3f849b37b2c8cab.nq.gz
    ├── 78304c8e22fd19e95626eb39b998254a08708511.nq.gz
    ├── 7a355043bd343bd3861ddb0c8f8452b27c8fd2a2.nq.gz
    ├── 7bca4156eb6e3fc7b8a6c74ea2414fd21c94e673.nq.gz
    ├── 7c6dfb3d9a597c801363fa64ebe0d9c6363fd6d9.nq.gz
    ├── 7d022e5389e7b695f9dedcf5b196f363aaeb5bba.nq.gz
    ├── 7f4dedf8af2eb79509f1bedd8c431bf6253834c4.nq.gz
    ├── 7fc395b96da77bdbe4e5c8504fc4299a54a40287.nq.gz
    ├── 801e26d9c2cd67d4f0af9e1e8e6d31d3c3cca724.nq.gz
    ├── 80b2429345d396f62597cf6274b21051ec6c8c15.nq.gz
    ├── 81652854dc0482f762f1d152a723a683826c8f96.nq.gz
    ├── 819e1e4ff6099169875f8364ba57c4ab045066bb.nq.gz
    ├── 81fe952862ed640e2f750d38fc7e3f927322c0c8.nq.gz
    ├── 82671adb6025e348b4c636e92eec81176c6d5085.nq.gz
    ├── 827a9105e973f353e4a310f96cf6af1ea5320afb.nq.gz
    ├── 82e5086a5df064927e9c870222c68523ebf6597d.nq.gz
    ├── 8520e1b5ed005ba7c42b3523f29ef841574fadb5.nq.gz
    ├── 85cdcf4402f36b570cbc4ee2ecc5578201e3c284.nq.gz
    ├── 868b0accf030947e0942a6996a4e9850f99ba308.nq.gz
    ├── 87c56d6093b95dcee78e679a36340f2407f01499.nq.gz
    ├── 884dfbc9ff457331fb7cf313649b5b6c70e8ba97.nq.gz
    ├── 8889d5bf6fdeee3289bbdb2cc2b7f9c3198f36a5.nq.gz
    ├── 88e2dc744a739656d3dd51960378bae1c8ad9c17.nq.gz
    ├── 895b038219ed3de3cd2748dcacf8428659cf429f.nq.gz
    ├── 89b14f4e6d3801bfd58e0362f1a5d8be696d1286.nq.gz
    ├── 89be25cfd618ce30b7a8899008f4b349ab51ba9a.nq.gz
    ├── 8a9d40b2dadac2b09fe6d86ebea14bfded2fd26d.nq.gz
    ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
    ├── 8b1563a371ba2710f1f02dddec964585eed46dd9.nq.gz
    ├── 8d386d4f85d8558d368a6e19790463f1e1b8cf2f.nq.gz
    ├── 8da1f9bf94ea871922f6042ce0418de358ba9f91.nq.gz
    ├── 8de6470502d1d351b352889cabe01cf5423f6e07.nq.gz
    ├── 8e076e134f0129efc960c118dc7e5c6f9af1dd13.nq.gz
    ├── 8e1ec18bf714625180a1478c0a3d76fc2dc8bab1.nq.gz
    ├── 8fbe84ab49b48732ed622c18ce525979fe32f298.nq.gz
    ├── 90083aa993cf25069de8b38d0b7eeb5cd85cb79f.nq.gz
    ├── 90a58e2f6fa2d5f8c7562effb435e2d2aeeb2e9e.nq.gz
    └── 90a9f7a99faf8a6929da3c3e6c596e004d92b7d2.nq.gz

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

[academind/flutter-complete-guide-course-resources](https://github.com/academind/flutter-complete-guide-course-resources)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
