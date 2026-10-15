# Repolex Knowledge Graph of sphinx-gallery/sphinx-gallery

RDF knowledge graph data for [sphinx-gallery/sphinx-gallery](https://github.com/sphinx-gallery/sphinx-gallery), parsed by [repolex](https://repolex.ai).

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
rlex download sphinx-gallery/sphinx-gallery
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a7f3bac58f0d8f2006325ccd6ab746f6f55c504d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a7f3bac58f0d8f2006325ccd6ab746f6f55c504d
│           └── chunk-001.nq.gz
└── blob
    ├── 000a2e3bab55bc59dd2e34038d3f1fe1b249317c.nq.gz
    ├── 00a7b00c94e08b86c765d47689b6523148c46eec.nq.gz
    ├── 0117e7caf88690910c5eedff347169b29ba0bf8c.nq.gz
    ├── 025c890ebcde547834dbfd3bb8109e54fefbe6f7.nq.gz
    ├── 030bc209de2430c47f5fcff0f0fb01ca26a6b254.nq.gz
    ├── 0331ad93f7ffad525b38262ca2894dbab9475566.nq.gz
    ├── 035ddd7c9918328720e0f306fd12e2495b637fb0.nq.gz
    ├── 03e513114507f3c19cdafdb2462cb074822279a6.nq.gz
    ├── 07162ad5b111081d8b1753599458e4ebf348a425.nq.gz
    ├── 085374f8347525a061d5433566fe0876b0773e84.nq.gz
    ├── 092ecbee0eb6af850ad0d79eb4c2530596c987ed.nq.gz
    ├── 0a75d594dea5cb8f0cf91171c37d34d14e1be428.nq.gz
    ├── 0afa57b32009061b0ea9c3e41cf2c02c170d5bf0.nq.gz
    ├── 0bca19700718d7d294ca5271d6d562391d7bb1d9.nq.gz
    ├── 0cef514d1ecdc0515bdb58a6e2546903d4521e38.nq.gz
    ├── 0d4c5c2751a4f499cbf9fb5633ef2ad56204e8e6.nq.gz
    ├── 0eecfc8853fa8628b6a7eba2b5947f82979b0e33.nq.gz
    ├── 13b5ef273b583cc7a12bdbc8e1924dacad741859.nq.gz
    ├── 141ea55d0f4e23406eaf45e82142f7ad23587e95.nq.gz
    ├── 15dd1bd51beec71385e6f6b5b328fd7ce82b651c.nq.gz
    ├── 15ef6b6ebbba45ab62c98bb2c3c44fdecc993308.nq.gz
    ├── 15f8ce9d6fbe9d50544f418e2e41607dac017c41.nq.gz
    ├── 1744f5bbccc75d8ba2ff7f0789ecc8192ed0d262.nq.gz
    ├── 18bdbfc72583c98ce21fa589c2051bdad27aa1ae.nq.gz
    ├── 18bedee2f383ff6c0f6e8629b8a80c61d1a30a54.nq.gz
    ├── 19a29ee7f5d7d186deb136188ddab0c3314476d2.nq.gz
    ├── 1ad8acd45c59bfaf6c5d11a18015640c09589c80.nq.gz
    ├── 1d6c78fd941bbda9cdba999b45b36a91640c8d44.nq.gz
    ├── 1dc497c731ea7ca3984ec2f1ce7aabb221c94189.nq.gz
    ├── 1e79da36a2dee51c09fdb0bc7e698cb38785325e.nq.gz
    ├── 1ee82d5a1f9a900d05636a7529a9b87a58bb2a4f.nq.gz
    ├── 1f20c954bcee7c13aea450eb2d22e352e7342fa5.nq.gz
    ├── 1f95645d8e46232451d05a316073906a4282d321.nq.gz
    ├── 209d2f617ee7db0e0076bc62164944e84fb7e763.nq.gz
    ├── 21ceafdf9074fff6a5eec9916ec0ab41e9f07d3d.nq.gz
    ├── 21f71271b4a77fa5544e2c9c0128f902ce929664.nq.gz
    ├── 29bc8bed730dbb254af2d084ae3faba5a54e8856.nq.gz
    ├── 2a0aa0f92ce1550f44fb23aec98bbcf794688388.nq.gz
    ├── 2d35a3bb1e84d50f0d310fa000164bc6191e760e.nq.gz
    ├── 31dce0acd6937c8893f7be0ac0781d71c77fcbc1.nq.gz
    ├── 3277d9da998fa2cc947cf59e8a1b9de6eb800972.nq.gz
    ├── 327f6b639a9c4dc4d7701e46ca736e6841e6bf8b.nq.gz
    ├── 3523d6724e3aa69eb6f71c42a0f3355e50538810.nq.gz
    ├── 352963a345d490057cfb5cf08a8c67b319868d08.nq.gz
    ├── 356cb08ce839c1445b192cc5af632641d9490cf7.nq.gz
    ├── 36f24e8e59dc6393d25218b2a4e1669b47fe6818.nq.gz
    ├── 3aa3671d55806abafdacf91a302119f3ceb302aa.nq.gz
    ├── 3aa73ae9df8f9e10715257716e045700ba7aeef0.nq.gz
    ├── 3ae02c308c14fe1d3bd5741d1cf2ff257f7cff95.nq.gz
    ├── 3af7ab6891d3d290dd4dd27321d86d35a64677b0.nq.gz
    ├── 3b6be0901b532da68e437a17fa38d974e9756221.nq.gz
    ├── 3bfb935943cae999fd50d4d6f9a018683752254b.nq.gz
    ├── 3e26f256009a0deaf96f005ee82fe2cc61ed2bf6.nq.gz
    ├── 3ee20920b21316bbd9f427197a46c821cd54038a.nq.gz
    ├── 3fcb083c741188e6213f5e919861176cf44240c0.nq.gz
    ├── 408f379cd31b55b4717ea896e0c8eb5bf1f2496d.nq.gz
    ├── 420005d227094df5ce9da2b82d7fd23c5a33f86c.nq.gz
    ├── 422465a2c6cfc3f19465409a8bf7fb839d15f072.nq.gz
    ├── 46ce873963454c76396628f8039333f284fb2b39.nq.gz
    ├── 46e3512a629fd61efe4a3e6f13d304250d33d3cd.nq.gz
    ├── 4700f6cc034c1ef39b8e82ab0a5e03b1e6d087db.nq.gz
    ├── 47f8d6f840ed45f2c076494dcb2b83cfbdfd7b46.nq.gz
    ├── 494690d0d2f43e9762aa7c6f3d39f5e762dc6bd9.nq.gz
    ├── 4ac2a56b2dabb37ac7a34103fdbad61bd576a6e1.nq.gz
    ├── 4dd736b7b1dccbba1b4da5728092b76511e4eca6.nq.gz
    ├── 4fea24e7df4781c2c32c8d7995511ac89e953145.nq.gz
    ├── 51d0558d6da0a58076060ce1d6331e1164b3dd5f.nq.gz
    ├── 53d2ca0fe7e970533166850f43c4ff4f20668bbc.nq.gz
    ├── 56d173be9a3dd6a463868394d7b9d283c2ee020b.nq.gz
    ├── 59462eae1b920e173144de85c51775dfb2e8aab9.nq.gz
    ├── 5a6532ca34edad5d260b880389eac64a24f4814c.nq.gz
    ├── 5b1c085bd4fa363fbb601dcc1b310c5343be166d.nq.gz
    ├── 5b4c1e64fc0cd13b34ee7b8e1cd92ae6ce295005.nq.gz
    ├── 5d8dcddbcdbf8d0f9cfeaa34f5ef5b2a45915a5d.nq.gz
    ├── 5de36d7fd5b02994de175199e5e8b54a3cc812d8.nq.gz
    ├── 5f0c034ba0119388c34e9efb3cf52699f3b1b3f9.nq.gz
    ├── 5f89818f9e63c2f6829c7706c57f223cdb5bbd38.nq.gz
    ├── 5fa1b5703c5f1e83f58b0108ee36cedc13e5f4cb.nq.gz
    ├── 6263b61fe7a1315436dd4be0322b3552e6aa4e4c.nq.gz
    ├── 631e41eb1a2d78a259425f85423000ce613d0735.nq.gz
    ├── 63ba163179ab2d2c2805ed024f7c5f009d8a30d4.nq.gz
    ├── 6821a84b012c739c20d76e641f371eb455bc38d0.nq.gz
    ├── 6a4516146c371f7b7ac9cacd6d3845afd8af315d.nq.gz
    ├── 6aa361e0c8887405e62a1204308b22cef0bb591b.nq.gz
    ├── 6aee41ca20705328066f92ec186448ff72f95c73.nq.gz
    ├── 6c0e236be0944a0530900b904daa55236ff931e9.nq.gz
    ├── 6c4caf561bfddb542eeabb1340d426d44dbe29e8.nq.gz
    ├── 6df91f3c411fa439ce876a0fea7c6e229c26188d.nq.gz
    ├── 6e12917aba45bd36e74bb80372bc6456002e23b4.nq.gz
    ├── 6ee65fa68b23a83fa635eb0a39d34fb897adcad7.nq.gz
    ├── 711cb596d707c2f2ace29702889c8f965f4f699f.nq.gz
    ├── 717bdc5c6e9c8ee384e663bcff2f53780d35cde9.nq.gz
    ├── 71997be00b54b6b7fd2039102fe66acf7556d1df.nq.gz
    ├── 731e77ef2de969c491802cbb12434e1283a534aa.nq.gz
    ├── 7487e40f23529231d001bd4e6bd09ffab3669767.nq.gz
    ├── 777a193671f3bf6bab54e95c53166928d5525435.nq.gz
    ├── 7acfe1b602f60313bbdc6d1ad40a17dfdd420edd.nq.gz
    ├── 7c5100942aae489ca04d07d2c69a4d8f6f8470fe.nq.gz
    ├── 7cb8b662c2d89719a11f745672bebed59560b550.nq.gz
    ├── 7e86112cd41b723ea53779cd6e7a0051fc3723c3.nq.gz
    ├── 7f1d3f007a44cc16adc4b27362f7493040e0a069.nq.gz
    ├── 8134891cb515006b3097cf06c59f9cf23f1ce641.nq.gz
    ├── 850c2d6f0bc691dc91b7e48b0395f8b24e831fc4.nq.gz
    ├── 8563e57a316a9255ad1bf8121ee06e72f22cf409.nq.gz
    ├── 86356ce2e2203250214a98db53dc1f6077533d1b.nq.gz
    ├── 8779d3b9d6255a3c2e23297e809f3fb038a0debd.nq.gz
    ├── 8883d447a1e8edac53381dce065f92ad9a7b5b0f.nq.gz
    ├── 897bf2e11bfed2c113bb8f204e55a76549d21ebc.nq.gz
    ├── 8a98d2dec6254bdda34170e220b52479f8897a66.nq.gz
    ├── 8b290568e0d54d2c1308fcd74cd27baa0a202955.nq.gz
    ├── 8c2d48d5d3f0044cf0399b3608d8eb5db6f9d12d.nq.gz
    ├── 8d62c302839817349f728e275204bf5c022d5b2f.nq.gz
    ├── 93dc2ffb024690d69060c65000f2cc24f307a190.nq.gz
    ├── 950e407add235a6bbd4f9690d49328065e5db484.nq.gz
    ├── 95992d803bbad1d55f1ec6d97922104baf5f3b49.nq.gz
    ├── 9753d8ad34d116f982dd2dcde4276be4b64e0870.nq.gz
    ├── 9770133fea5e0c8dee42737fb44bba3f864f4e69.nq.gz
    ├── 9850d3af6e8fccc0114b155d28a96e6eb7dc13b2.nq.gz
    ├── 9b024939b3621a6768345b33d12c9f2c8e0f8a78.nq.gz
    ├── 9e238965939f975b102e0255503b1d62dfb56716.nq.gz
    ├── a21a19791263fd59839a2ec3228b7e0cf19b29f5.nq.gz
    ├── a309036cf6ade7dae482eed0b228b92fd9b0f16a.nq.gz
    ├── a4f029df01a55059ce03ac45b1f4bb1bc7638471.nq.gz
    ├── a7c3da3243d02dd1027108e9ab2fe025268192fd.nq.gz
    ├── a9ad98ae939927d38a56c5e6e56372e4bac6b10d.nq.gz
    ├── a9d20c402f5a32d6eec4affe5007ae2d9670ec22.nq.gz
    ├── abc4adfed430e9fb2d11d1ebfd81406ccb4f27a7.nq.gz
    ├── ae44297c7b4e8ec9f8807b6741c0ec295dade1ec.nq.gz
    ├── b3d50f193e5692cf7b069924f87eaf7dbb050e0e.nq.gz
    ├── b465f32d5e4843d2594998f0fae7931aae7de783.nq.gz
    ├── b4ed3c852af34d2168beb9be9d0554800d3c3892.nq.gz
    ├── b57e25fa54641f7578776c56acea14afc0ed8c42.nq.gz
    ├── b58fee72b85c3940dc471d821aa4c3b0c2daebb8.nq.gz
    ├── b7b38a8584eae4529d20e30612ec9d49cdf7811e.nq.gz
    ├── bac9bff0245e32cb7209af7ae7bef3645b5f5147.nq.gz
    ├── bbc9f325e7893a36eeff1d0899176192f95ab4d4.nq.gz
    ├── bbe3aa3e5f07eebd875017861bb9654bb03942a2.nq.gz
    ├── bcdf2a7068c719ca4257116f75d2f432f599eb93.nq.gz
    ├── bd2e553bf0cc458e5035828b610a7d777391e519.nq.gz
    ├── be6978357547b5cb9a8ce7188a713dad5011f775.nq.gz
    ├── c0614449286a44f2a9aa52cae87e8916d816bfc3.nq.gz
    ├── c4c71e16286d89fc9af7360156d2d432ac8715c3.nq.gz
    ├── c4e188adcce0ed4f8a1ea1f322ec0555498923c3.nq.gz
    ├── c56f91720c018e5b0e152a55cf077f84b0633e51.nq.gz
    ├── c63fafb9b28ad4a5d15aa740cea1e941ab6aad47.nq.gz
    ├── c640c19a0deaa5c5706c5cd3890c7e57d4ec26cc.nq.gz
    ├── c6f395aa2e62e56d2a96f13a95032275a194ab4c.nq.gz
    ├── c86495d3b693c11cf3458c125881ef4ed35b3da0.nq.gz
    ├── c8c2af2679c40723fb0b0173978484c9acf62cf3.nq.gz
    ├── c8d28311d9aeff8af1f664a8beffcfe35e5960d5.nq.gz
    ├── c9b552e44aca4e211f887222e0a5f23c78dff22a.nq.gz
    ├── ca2e390990900f7ecb671b2d1541abeea80d46eb.nq.gz
    ├── d06e17de4b6dece1be23b9e689ac4c90f3067e1f.nq.gz
    ├── d205b16d0056dfe7d00698153ca3d2fe4533a859.nq.gz
    ├── d2a865d39f4a3e0326d0e2a627adc2ce5dca7cac.nq.gz
    ├── d34f32216347593a9b93895102431fb56af4c73c.nq.gz
    ├── d572c4ee603d29a42f658ad9aec733cab8d434a8.nq.gz
    ├── d5c0fcfcbdb5ff17435dab7b8b1b43accaa3c021.nq.gz
    ├── d5d5ce5098ed5d397c8a355babb26a5255fb09b1.nq.gz
    ├── d66e294a0facd9096ef9cef0a70c4cf70830392f.nq.gz
    ├── d871ea50ad5514a10e3a28b0f6608f837f9f3375.nq.gz
    ├── d8d68a122d17159481623b38b392b330ae57dcec.nq.gz
    ├── dbd3d946d2c6224db0eaf19bd4fa0fd48d7c0fd1.nq.gz
    ├── dda158ec1ce7d9c6de0aed69231201383b7508da.nq.gz
    ├── dfcf4ddd90d26da72c2ee38aef3a8aab8e5d77f8.nq.gz
    ├── e026f44002f33d18fd63b46e7602f9ce955a0c81.nq.gz
    ├── e0565e846ed888c1455997a97bc87e7da3245e71.nq.gz
    ├── e22abf2b8a3806bdcd134e0050c653ed3d6cc750.nq.gz
    ├── e2face38af2170e25ac810c54f4c2925d211202d.nq.gz
    ├── e528fcfe39f13ff339dff9f07eca5a92d19cc1d5.nq.gz
    ├── e5e4f77c41e5011369d395c50a88b6b4671bcfe8.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e7e0a2e4c39d6a1bcd74c5083c39aac295872385.nq.gz
    ├── ea4c63444499b936c0b7184796a35ed65eb75afa.nq.gz
    ├── eac51ba218c7ec2985c9fd7a0eb75be11ca6036e.nq.gz
    ├── eba8c91d34d9256a149ca71d199c8c8e6e92fd53.nq.gz
    ├── ed976656ff0c93f1151469cf805f6ac8448364c7.nq.gz
    ├── ee77bd84ba1492d979a7afc3a414026ffd224cda.nq.gz
    ├── f14a1bc19d9df02cbbe5bf4d817d5ca7563afa6f.nq.gz
    ├── f1d7bb3436b50d3143b56e48ac2bd3691cd76ecd.nq.gz
    ├── f39d2978c4854de0edcb4ed9c9ed285caaa15380.nq.gz
    ├── f44e0bfe67b6488a2b2c351b4c45dadb912b8827.nq.gz
    ├── f47572de3696013a215bfb537edd12dcb1fa16da.nq.gz
    ├── f54915d4c1cfe4fb79b8e0f80f390bb9bf02e5a1.nq.gz
    ├── f624b2aa12464f13211b739383d6d9e1a5b4feca.nq.gz
    ├── f634a1b51f004dedd178c79ab70ff9cfa5b633a1.nq.gz
    ├── f8163d2b5fb760b807ff2181c8e9d08ff9adc3b9.nq.gz
    ├── f883e9279fa5d0d25c305a4291eaef517564afce.nq.gz
    ├── f890d1c9d0592732569bc6836f4c6b6921ed922d.nq.gz
    ├── f956e735ef2c900eee0820bafd2a072758c927e2.nq.gz
    ├── f976db28a869169edfdf5ffe7f0b31ee164618db.nq.gz
    ├── f9b47616c2a64a2a05be04670239df5622c3a120.nq.gz
    ├── fac74c43b7c9a755710933d94f4ca9203144346c.nq.gz
    ├── fb577c44a73de6b72f6f07aafa92ad6cd6b67a92.nq.gz
    ├── fc7b34d026811139cc7470b34250d075e3ff845f.nq.gz
    ├── fcafa56e86d397f7d607bb809b3c624450b0b1b9.nq.gz
    ├── fd834c8f5de47789249679d53a9398ec7efc6932.nq.gz
    └── fdb8474f2d9c64994bd386ceb7adc2ea86cebf7b.nq.gz

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

[sphinx-gallery/sphinx-gallery](https://github.com/sphinx-gallery/sphinx-gallery)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
