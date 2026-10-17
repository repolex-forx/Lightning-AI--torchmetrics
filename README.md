# Repolex Knowledge Graph of Lightning-AI/torchmetrics

RDF knowledge graph data for [Lightning-AI/torchmetrics](https://github.com/Lightning-AI/torchmetrics), parsed by [repolex](https://repolex.ai).

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
rlex download Lightning-AI/torchmetrics
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6c551c6469dc04fe92291c000ce2607860df92d2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6c551c6469dc04fe92291c000ce2607860df92d2
│           └── chunk-001.nq.gz
└── blob
    ├── 0054e842585e0207126def09cb9cc6fca236d1c0.nq.gz
    ├── 01ea27ae12be55f17c5c71ff0d40e3d2d6089249.nq.gz
    ├── 02db67c7cb68598058de8fef8e09d0f2f251c524.nq.gz
    ├── 032705e66a870f3876ae0ba164b960f52a690c08.nq.gz
    ├── 03e6408ad9197039d59faee6eb07865a5dea1de8.nq.gz
    ├── 04afe3f6fe783a6103b12467c60cd4d11da8d4c8.nq.gz
    ├── 04e8d2c82a175ae1b6254f586034a8fe08c3e6dc.nq.gz
    ├── 04fe881bc9961b4405010b1584581444f1bb6056.nq.gz
    ├── 05de928779356fbb41d5604aaad88f2c9313e30a.nq.gz
    ├── 064b54d06d3c7ce508b93997b9624bd8fb14ca84.nq.gz
    ├── 069b6a3089cd053f05067c252face8c5d67a4148.nq.gz
    ├── 06ccdf2bfc4d90382ff060a9964039d1c60d8aab.nq.gz
    ├── 06e06356fbd96b4d7527205d2c1245fc742d80c0.nq.gz
    ├── 0824d06bea3be5dac4567a65ab47435e68e798eb.nq.gz
    ├── 08c99fa53ba0a483ae3cc2f663abf9ef18f899a0.nq.gz
    ├── 094f87c5c83352c53b96adcbfd7f46fad59c4114.nq.gz
    ├── 09f6052eca4ca4b33f4ab8d5c7e6fac911071460.nq.gz
    ├── 09feca9839a6f728c7c7f32b50d84c201f3d7c60.nq.gz
    ├── 0a04517b7c151f1357dd81a19761c77b130b90aa.nq.gz
    ├── 0a37b689ff9f2c1a9d89b39f0e4f51705205bf06.nq.gz
    ├── 0b46b6986383dca718ac6d4694f2995f5535e1cf.nq.gz
    ├── 0c3877e099d26a19bb00062147bd15892eef81c3.nq.gz
    ├── 0ce1f94bf6620e1a28298e1fc511a9671687c02d.nq.gz
    ├── 0d24d9634a00f0253225c82596a9cfab893f0195.nq.gz
    ├── 0d5117956f2fb115f099e12755939bd7235c8506.nq.gz
    ├── 0d710b5c0719c3491b144d34e071ad238426b693.nq.gz
    ├── 0e11bffeb01d99f0363501d07723268c8d4b22d4.nq.gz
    ├── 0e4d3b8bf2f9c790af1bbd5673bf73924657dd3f.nq.gz
    ├── 0e55458451f5ec72cd038da858ba9eb112af1b77.nq.gz
    ├── 0e5903f59052e1e354c103034944947f4cab2bc7.nq.gz
    ├── 10976a31ea9b5cde05860ead7d07d3f867f04472.nq.gz
    ├── 1125bc7a9ea87b0d82df0b73eca5007942907556.nq.gz
    ├── 12fe0fa28155b5af1371c4fd80d589ad8a811489.nq.gz
    ├── 138b7407839e83cb2a3353f0e32c374d39588bd1.nq.gz
    ├── 13ab22f7140d3bc9aa7939823893ed1a40faa0b9.nq.gz
    ├── 1403c0b1a37e74b538b489d4951b67797ae5e365.nq.gz
    ├── 1545ab62a8329e39a088a70d08552d83cd355d38.nq.gz
    ├── 155f1bb8f608480d4e4403a624b89a8d52d0372f.nq.gz
    ├── 15b0cea06f02c246d808ed3159edc1e56b04a63b.nq.gz
    ├── 15bb356a236b8e835ac68b005f9be66a039db57a.nq.gz
    ├── 15be1bd43b462ecbbbadba1811829f0a5dbc5515.nq.gz
    ├── 16fa9392ca349e77c288b943b3efca0e6d096ae1.nq.gz
    ├── 1744df6f66b101d4bd01024cc1cd2116b39d8df4.nq.gz
    ├── 17ca8c9f58a8aac9b40405517cb9ee11e73da3fb.nq.gz
    ├── 17ff4bbbceb4424e0bc806a710d2a309448c7f37.nq.gz
    ├── 182e57260a598683fe99f70b422ae02c3e3f1504.nq.gz
    ├── 1909c4f3f5d918d1d0c6a94ceedbc2ec90e29424.nq.gz
    ├── 1937c51eac43c317f9f3f4c4f4f58652272a9539.nq.gz
    ├── 198d7982646d8f1b651b2eedc158612b1c8e7349.nq.gz
    ├── 19b9897db29fbd8c5ea2fa622f1843f750918af3.nq.gz
    ├── 1a13d8aeaefc8453890aedce0229cab5b0f195c8.nq.gz
    ├── 1a3ec618d536a7e52198e909a93d844b7bf680dd.nq.gz
    ├── 1a46ca97e29a1b1fe45c1b3045985e17b3bc52e4.nq.gz
    ├── 1ab881bded2d37888f36bf9a182769c96f68eccc.nq.gz
    ├── 1ade34c46a9ff90e1f86e59d8408150b74ece28f.nq.gz
    ├── 1b371a96d9de90c28371de7be7d67a42451176bb.nq.gz
    ├── 1c0e704d2726aec7cfc70f4a12ee9adf50f0db68.nq.gz
    ├── 1cc9dde2439b10b94c759b93bbe685be10218871.nq.gz
    ├── 1df9dfe62abb1fc89cc7f82b4e5fe886c979708e.nq.gz
    ├── 1dfd752ee2265792cca17cdb61ce262e5b6356d5.nq.gz
    ├── 1fa6b31fd627056b9e038b2380e508adc44613d5.nq.gz
    ├── 20278f74bc3e80ad8b7fd111505a2e0362add08c.nq.gz
    ├── 20963940a021fca153605fc0a4c2575bbc22dc04.nq.gz
    ├── 20a1d9d2c718d818078ac60f1afc333d41fb81f8.nq.gz
    ├── 20a3123150387a4efcf29fbbc23da565a1d1d560.nq.gz
    ├── 20b582309542179a52f2091c83ba9278928427fd.nq.gz
    ├── 22364bfc93da4c7d5498b9b1353a73fcea9a810b.nq.gz
    ├── 22c24b164f13fc837cb25f4d9c259b410f393d2b.nq.gz
    ├── 22d256d33d12c288aca7627e51c54b72b9594ff3.nq.gz
    ├── 22f9b8506e75b6e87bbda425e927dae1ae4a788d.nq.gz
    ├── 2302df854c2101c3e56b93ab22d06eb125b21030.nq.gz
    ├── 234d1fd29cf85ceaf661d224eaf5c6da237cbae4.nq.gz
    ├── 23cf06638b09822658937da51523a2b002460c4d.nq.gz
    ├── 246b9adf5af05c08f778431a2a65d077768467c7.nq.gz
    ├── 24e3295d861e2ce8e9c7cca46c1f871a7c2f6c85.nq.gz
    ├── 254796e96c9fddc5c5c24eeba43176296b76ac93.nq.gz
    ├── 25a9b680b1424f270d5f54ebe800544ad963ecdc.nq.gz
    ├── 25fa99bbd5cf43470057eaac399046291e5660c2.nq.gz
    ├── 26bad0fd801c94e19d8558bfb19e62b8e6af5403.nq.gz
    ├── 2776f8c9fdaec3acaf864055f3a867422be65f4d.nq.gz
    ├── 27bdfc0a9f3b9966c632dfc4564b9277b7ab3bd8.nq.gz
    ├── 281204d347131964e6655df2a8f3b7cbc8872ad7.nq.gz
    ├── 28619effcbae755926d7ae4ac21ce67bdceb7007.nq.gz
    ├── 288b08601e06bc744f3533c10829348efc15210e.nq.gz
    ├── 289d4d861e683b63266dcc90a11917665ffa35c9.nq.gz
    ├── 298cedd14862511c9304699f2a531cf19d8a60ce.nq.gz
    ├── 2b7fac1b2903e2eab9ef96770b0f5e39ad243e13.nq.gz
    ├── 2b8d6f3cfa77ac62d38592b23f30fbf72d62c5bf.nq.gz
    ├── 2b90685912d3b4697a5c8e447fcdde86546bc587.nq.gz
    ├── 2c2466af4307618533c2743327b883cc603aedd8.nq.gz
    ├── 2c4fe2709dbe063d9623f0963789ed675705e875.nq.gz
    ├── 2cb06964ed71881310420846603f82f2e799fd29.nq.gz
    ├── 2d190395dd3e1e66c43e7d5a10075a857b899de5.nq.gz
    ├── 2d90238bfca452eec403c73be9fc1b57486760fe.nq.gz
    ├── 2dd804e9691d453daea0c028ef80e8dfd1a17843.nq.gz
    ├── 2de4a9ef94b353b4fca8f917b819d56a6437d1f0.nq.gz
    ├── 2e00cc9bd1c5705a89607fdb8fbe928e7275db12.nq.gz
    ├── 2e6f9cd3c114be94cb814163ffb1eb6f53156e58.nq.gz
    ├── 2eb3eb6a45060127bec182c396bf2fd3b34e2366.nq.gz
    ├── 2f26b452e25732c1ee6fe89297f83e89a6a8c2d9.nq.gz
    ├── 2ff4fb94a52d491dcbe238c2eaf56c93552607a5.nq.gz
    ├── 305c6f7c4553044202a8d7d2459a97e679b016a1.nq.gz
    ├── 30a6da7d9542d8b1bfdd7b4f52c79a05442752b1.nq.gz
    ├── 30dca188b74a2edea396ecfae7e554688a854a76.nq.gz
    ├── 312c39c1a10c6e35803e56c2aedebcbb96c27bbf.nq.gz
    ├── 31884b24ab8a3c03cb6d8c2af0c63a9bc4db4a52.nq.gz
    ├── 3204df2b72ec9971bc3597d86286214b21203db4.nq.gz
    ├── 328829dffe36f0e26a859e58e1766380ec1fb809.nq.gz
    ├── 348e851c23865d47d1f3e7f3abf72053e09d3a98.nq.gz
    ├── 357685faa11a42082e83877f67e022b65f2c8630.nq.gz
    ├── 35f88cf51b09d28677062a168850cbd2954ea703.nq.gz
    ├── 371ad88c58876caeaf2517c7beb3d7a95c56973b.nq.gz
    ├── 373374fcda71095398a355265d3401d3b7a20787.nq.gz
    ├── 37c87f699f78bba1f18e50523c9ce03299cb5e7e.nq.gz
    ├── 38d48fc81f49e722595dac08942b164cbb324930.nq.gz
    ├── 3905136ab1bfbf2d78b5dd69c5ad16a32edeb067.nq.gz
    ├── 3a5cd73a9b5beaf08877cdf087e6faccd7073edc.nq.gz
    ├── 3b4fa05e3d1fd07ec99d46c7b2f422fac2763a52.nq.gz
    ├── 3b8afb9b3478399100e09743882f64fa804a3954.nq.gz
    ├── 3be6e0696308a4095d18ee0995e9451881b85552.nq.gz
    ├── 3d71843ac6288b721fd459123a3c1ff17b617620.nq.gz
    ├── 3e4140723f5a6b699584574994e945d807205051.nq.gz
    ├── 3eda0c07a3820b56d92bc6497e667a05f63233a0.nq.gz
    ├── 3edc7f730ec86d454b9d6506bc4c3f6d5c7083e1.nq.gz
    ├── 3fc78b6057e4abe66636057901d1bc30cc759bd4.nq.gz
    ├── 3fca98258c7fe3409097e632274e7db77b5accd4.nq.gz
    ├── 40c62707f014c1815c092e21e1e75c7d78ab0a6c.nq.gz
    ├── 40d1a396f31c13c066ec85015d278ea13e517da6.nq.gz
    ├── 40dfff10d08daa8adf365c048b5cce1993a68324.nq.gz
    ├── 40e32fb96cff92833d1dde7e91be0870565cec2f.nq.gz
    ├── 429766ffe2531fda81025daa412336c270ac1ee9.nq.gz
    ├── 43211f836a7b8205701aadf0ec0b4fcf1d583a7d.nq.gz
    ├── 4336b195ebb5170cf93d392b94ff1df513c52ec8.nq.gz
    ├── 43a15bd1b0509d957ef44bad03ea0e8aec0decd8.nq.gz
    ├── 43c117a3008de3400a1235b460c53bf799e357d4.nq.gz
    ├── 44b097ac8e2f5919c4cb092b1d9495d2eaf85404.nq.gz
    ├── 44d19f9baf4adaa6c584ef14d4c78ef7c4b7f636.nq.gz
    ├── 456d49be454ffdcf1f7e2939ac0fec1b50039adb.nq.gz
    ├── 4647fb1c205aba9480a6c45058ef6e2b689320c4.nq.gz
    ├── 46c8acdab56b2fb8d3de233231a76f3314eca4d4.nq.gz
    ├── 478455c0a685dd0c97e33cd3049d0997efc2ab74.nq.gz
    ├── 47fbff38d080fc6e0ee6559846bba1746a2e53f2.nq.gz
    ├── 480ce14ba6130deaa88307d34f0337083b1176c3.nq.gz
    ├── 48393c55bd4e1b4fb6b92d40e1719995bef57819.nq.gz
    ├── 48b0bc6c6044fb29cbef1f8fc96311516c24fa13.nq.gz
    ├── 48c31a7f7fa8a92bf48a98aa0258f3fa8ada9b5b.nq.gz
    ├── 4947d5141c394968204dd7964e33a08a3f7f997b.nq.gz
    ├── 49bd692d6427c8aa604a9b75730b80a004cb902b.nq.gz
    ├── 49f9f057d837ef375bad1074f1a8aafc4f732d9d.nq.gz
    ├── 4b793e008b7b40fc03d23ae5960bc3dfa5d82b67.nq.gz
    ├── 4bb07002bfc3d8355baeed5953b9c89ead8813a1.nq.gz
    ├── 4bf3afbe70b75c21ef878ef5297994d6c7384551.nq.gz
    ├── 4c8efe0fc7e15332813d660df67632842a3b9042.nq.gz
    ├── 4cda2036c4d868f2a8ff0fa28228e94e5b695db3.nq.gz
    ├── 4d9248d8b7e8c314cbb8fdba4fab4079c4908881.nq.gz
    ├── 4d9eb83d9f9309029f4b14ff09024658bb0f5563.nq.gz
    ├── 4ea9490c8414bf3771f249bbf4237e4b35e31020.nq.gz
    ├── 4f22e1343f4fc93dbf38596af3565cda19b7e879.nq.gz
    ├── 4f74842394ec9807fb1ae2d8f05a8a57e9a2e24c.nq.gz
    ├── 50785f5425c25124fe562328f9988cc705155729.nq.gz
    ├── 50ad2af3bc31f4ee873c197895c131d1545b0618.nq.gz
    ├── 50c5091de287ec0d083d45f82b36d570ab2a3158.nq.gz
    ├── 51b719641fd975bb45dfd291929f9da262315230.nq.gz
    ├── 52008319009220c20f31d4e6b865d69d1c931f0e.nq.gz
    ├── 52b8bb17432ba6ad61073f30517f58c137e48fc1.nq.gz
    ├── 535c209796bf4f33b17d6a636eea4468386f9d9a.nq.gz
    ├── 55ab63946f928e228a9a9e6b85ea42f9ca615fcb.nq.gz
    ├── 55fe1681bf754654e863aff3c572ea69837212c8.nq.gz
    ├── 566f489d48f8257895509bdab67d1ea84cc6d282.nq.gz
    ├── 567cbfd4906422ca11773cb48a46323e427384b3.nq.gz
    ├── 56cf02383e472cef2e19dd810e3ed340b2c0371e.nq.gz
    ├── 5733d8b49d7ac911c576b8ca2d76e4cf64d336d9.nq.gz
    ├── 5837218ac827d77108e181bb9781ca0c8b2195f4.nq.gz
    ├── 5910fe98e58d48bd08bcc321d9822ac21a75a7a2.nq.gz
    ├── 5931b7b6944166c3f1278367845e8b198cbcead9.nq.gz
    ├── 596b2757fcaed7cdb3ed62699b8edcea45b5dd97.nq.gz
    ├── 5a0e2da04367c53aa09cc05ae858f8613762e437.nq.gz
    ├── 5ae3382ac3e385ad06a17edb8a713eb011825984.nq.gz
    ├── 5c48b57c3fefb7911d372d7ad14b8132777dc179.nq.gz
    ├── 5c86ac00cab671e35093dedd252aa1e14f933e24.nq.gz
    ├── 5c8fe20a2f7241856426163267cf5ffd4ad8ac61.nq.gz
    ├── 5cdc81b960d700acfe607ce3720d87adedbfbd8f.nq.gz
    ├── 5d729b766f1326d1392621b1b8c1fd167d3e3ab5.nq.gz
    ├── 5f65ea00d0fb7b2b45412693f5477e3e1b4f09a3.nq.gz
    ├── 5fa8f2264980119625465067c9c2beffba9d05c2.nq.gz
    ├── 5ffa800d69103d620aa0c6a3e9b65b1a1f284dd0.nq.gz
    ├── 60d1fb9d67087f75cec6a4334e62c270206f08ba.nq.gz
    ├── 613dc69a1410cdd2df3e17f391aead71e433a28b.nq.gz
    ├── 61b0e3b667330b930caac7b19329f08a5fbf0778.nq.gz
    ├── 6270d8a5a0c24e5cba395e39904840759b3ca60d.nq.gz
    ├── 6284470d1b2fd97164c98b8eccf0006add39c8ca.nq.gz
    ├── 62873c86f588223e5ce9b5ded0c6e67eed48e584.nq.gz
    ├── 62cfb78e1a94b45383dffcd1985eae6c7d951ea8.nq.gz
    ├── 62d3eebcebd4770de27b6d4061bea6c36175356b.nq.gz
    ├── 63f004082fa5742d81432225f140576fb9342c29.nq.gz
    ├── 64dd7e0823a3d9fe8eb77b63452582001680c6ab.nq.gz
    ├── 64eb7c6b1d4bea0d9b3318b578a3d9e0c478aef7.nq.gz
    └── 653d957c64ced2cdb6f42ee87aa2e2314f912d86.nq.gz

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

[Lightning-AI/torchmetrics](https://github.com/Lightning-AI/torchmetrics)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
