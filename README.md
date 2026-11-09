# Repolex Knowledge Graph of apache/avro

RDF knowledge graph data for [apache/avro](https://github.com/apache/avro), parsed by [repolex](https://repolex.ai).

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
rlex download apache/avro
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 726c25e2cf40b181a725335a21934f88c57068f3
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 726c25e2cf40b181a725335a21934f88c57068f3
│           └── chunk-001.nq.gz
└── blob
    ├── 00b76e28b944c6c7b0774620f17c57bc9d9e5ea5.nq.gz
    ├── 00c6c91e9d9c0b6301a94b0071907f7963cc092f.nq.gz
    ├── 00fe1b10efd4ca0e02bf5936c332f639a85f391f.nq.gz
    ├── 013afe4d1f271e48d6c713759d00d46980ea5b7b.nq.gz
    ├── 01596a50579b74d3da2ab7ce53a92392ca50ee20.nq.gz
    ├── 031eb21eaae383e3657382401985a0ef68e3e745.nq.gz
    ├── 032c21254dd32a3eec306498a32e8d1bb3b9644f.nq.gz
    ├── 034bb99dcce5b6b94450f12c2cf33a426fe05106.nq.gz
    ├── 03948107427da6efa19a284e95b210cdaa040aea.nq.gz
    ├── 03f6f7c6f276d535f74e7551e493c9c245441218.nq.gz
    ├── 040a71e2ea0d16c644ed51f0d0aced1d16682770.nq.gz
    ├── 0492850ef5e2504f68ebe8eb8633a9059e9eecbd.nq.gz
    ├── 050c25b467f8ee10c4c8b8cf2fc68d49fc01ada1.nq.gz
    ├── 059b0976808b146729149d0beb56247138336de0.nq.gz
    ├── 05a8dcaf2db034268b0083603d1bf15a6b3cc2f5.nq.gz
    ├── 060424461887327865d22be1484f28c31f3f72d1.nq.gz
    ├── 064fffd87695b1d5478a3ef34c36554bdcf30799.nq.gz
    ├── 0663ad3f6bb2cee5daf292e732acfeefbbe2dd4d.nq.gz
    ├── 06792b28de06e7634e0bd9d57b8bdca1f9dea03f.nq.gz
    ├── 06efa7bcef9acfd11f843dccc93f85caa209e0ff.nq.gz
    ├── 06f140bde45602c24c6e2e8ea94702ff6460fb86.nq.gz
    ├── 072b9775666e36c04611765f257d0cb8366eee2c.nq.gz
    ├── 089adf79764528eba35f6ba860d0d482366cbce1.nq.gz
    ├── 0967bb4aed3a98b4acac75e9d856e7cc7ea2846d.nq.gz
    ├── 09dd9f14f8e2ab69bb70ed7348a2bb806d54a8b1.nq.gz
    ├── 0a033cf55be1ede692a626af0749e8b2e73390ab.nq.gz
    ├── 0be9694d7d45aff24714ca6f7235693b66f0fcbf.nq.gz
    ├── 0c06035f11dd209d9e01857ec0349a671a64daed.nq.gz
    ├── 0ce6602071763f394863e1cb9d55686407afab1f.nq.gz
    ├── 0d6e0a0341b0ffbb65a19f9ed6767ad814cc81d6.nq.gz
    ├── 0dba9dc21292dc4986fcc893b89ba3ea40a77359.nq.gz
    ├── 0e24e0aec29620141401d35ab7fa7a7df73b0a46.nq.gz
    ├── 0eb56b7e91ac42778f374bfc908e29f1ebc8eac1.nq.gz
    ├── 0fef3d89e0df1f8bc49a0cd827f2607c7d7fd2f0.nq.gz
    ├── 0fffa418bce1a7f67a4439f9cfb5ef2add20842e.nq.gz
    ├── 10d5eaa4f00fb16cd431ac99393ab78f82680aa3.nq.gz
    ├── 10e527630da095ea5d528154c2a949fa61b3177e.nq.gz
    ├── 119c1a7457418c9610966cafe1ec1d8f48897b4f.nq.gz
    ├── 11b6bf196221dde4ddc9a0c527e5042060985454.nq.gz
    ├── 11ffd9851e9615057e0ad1e430f221f8fc512793.nq.gz
    ├── 133480af4abac7c4abf19e097fe87e4a5f8d19fe.nq.gz
    ├── 1351d900abe74eeada03ea04384450c4c07d6205.nq.gz
    ├── 136344bc15ac404e68de376df06bd872ca36deba.nq.gz
    ├── 14a8388fef040312385420355bdd670ff0108fea.nq.gz
    ├── 1535c604be78e542905c95015c41b75f0a991640.nq.gz
    ├── 15eeabd4ecf83c786bb25dfcdd3d6da035af40f2.nq.gz
    ├── 15fdd3b46fcd6d519f1bc44ea59c9d65ff87023f.nq.gz
    ├── 1735dfcf09878f905d424c3d844518061dc694c9.nq.gz
    ├── 17a830d21d5332333f85ddf8bc85c66c047fe958.nq.gz
    ├── 17c99f91302e450f6902fc88a840859e08f6a01d.nq.gz
    ├── 182f7dd8bcaaae898ebc2e102d4b55d4b9ea82cf.nq.gz
    ├── 18ccb10a29391b8d8495673746eafc8696e71613.nq.gz
    ├── 18fcbad70838f3dd2019f6475ebb59baed33cbea.nq.gz
    ├── 1902130be2e7d19821ac1df53c86a728bce0e133.nq.gz
    ├── 1935b5c285d0bcc14a8de22c8e4996a3ba513b7a.nq.gz
    ├── 1a340b7fa5dcffbd2fbce996f6275704a0825c7e.nq.gz
    ├── 1ac35baeda7df4523bb4b2cd79554ab61499483f.nq.gz
    ├── 1b5ea42e680fb012955a715865ae561e0b4f3217.nq.gz
    ├── 1b881b3a646f2485bcaada0096690cbe581d0ff3.nq.gz
    ├── 1c0ff95763506054e53082e87c4adf576f5d7d93.nq.gz
    ├── 1c7175461cc5d4287da7c2827a34d4b042c432ef.nq.gz
    ├── 1d9d58b05180a3e978717e074c36e58613179173.nq.gz
    ├── 1ee1b314d9d32b024362095b72300a704e3982b4.nq.gz
    ├── 1f052a327a705c0f8c131ba2a27b7034b66a8a00.nq.gz
    ├── 1f2129576a120e24107d73bba33b8b3bcb1faafd.nq.gz
    ├── 1f4aac91f9683de1a1478dd64e91bad1d03137b3.nq.gz
    ├── 1f699ea82665fe3f78352062afcb9b6a98af6da4.nq.gz
    ├── 1f9e05dad5ee563b2cae5a669019b369a133d665.nq.gz
    ├── 1ff3580d22f047450c93a7a3489d5653f34f91a1.nq.gz
    ├── 20bd29c216cad1c018513230fcbe42704b98d61e.nq.gz
    ├── 218e2f6a42017c0fa8b4de42e34609a86bd95d86.nq.gz
    ├── 21a1bf361d792c4889f10cf0f4fe572ae5f1c8f6.nq.gz
    ├── 21a32c5f2f848c4d15323af177ef70a933a66cab.nq.gz
    ├── 2263d91c81be6d725d790252888003464301b013.nq.gz
    ├── 22a6991eb44483cae0ab0ed6fcc562173489b84f.nq.gz
    ├── 2313daa1a23d216a09fc683d3c3ad19aa32f3c7b.nq.gz
    ├── 2316dc8c3e4ffeb5e28722c5f68d0406e456c984.nq.gz
    ├── 243dcf5f4a27c8a60584de8d2cd606ce8c43759d.nq.gz
    ├── 2537599edcb6ff7c9fa9dbbe5c1a9b9b0cbed300.nq.gz
    ├── 25716561498b115c46ff8ee13c58acbe60cd18ea.nq.gz
    ├── 26f1a07b1f84986502f7a06167071c2e224ddca3.nq.gz
    ├── 2763318c875d6d185933e35f6318f83de45f74fa.nq.gz
    ├── 278bc59b76efea44066d9ab6d9f951fc619864a2.nq.gz
    ├── 279909f483ecb0406f0a3ce98441ea649583722c.nq.gz
    ├── 27bf69c6cf1a56517b7d4ef1bbef591049eb6a40.nq.gz
    ├── 2823e406003e191fa24a88859fdc4c349bf01ab6.nq.gz
    ├── 29317d72cf836fcf1a792299033d2a6679b2a4e1.nq.gz
    ├── 29932c0bce91eb244fdd2de668a5f3c35837d5fd.nq.gz
    ├── 2a04a8a62d69d6a5a94c8cb4a4a814d78401967c.nq.gz
    ├── 2a9282544e48f8f9d3024cf19671d8ab091205fc.nq.gz
    ├── 2b24e6b86898620302f90559202f99cb9e870e3e.nq.gz
    ├── 2b6f516275a10bd17b67fbe55f585cdf05e9fa8f.nq.gz
    ├── 2bbe77d26b8208ce1fb564cdac67c44426fe2c5b.nq.gz
    ├── 2c5d7b0bbc686833d7c7d7db434b283ed05ee0aa.nq.gz
    ├── 2db5bfd03ec86197c71032488343aadde8832179.nq.gz
    ├── 2e6b46e5d1f467e0cbcd4aa1bab5bad115e1b40d.nq.gz
    ├── 2f2b873aa813d9eaa92c675be2b020ad780f1298.nq.gz
    ├── 2fa15eb959cc36cae49333341f747e31d63d7642.nq.gz
    ├── 2fb799fdfeaaae27a6661750cbc2c9dc2f93f9fb.nq.gz
    ├── 3029f9e4739bb21879e7543a28ce34de558de99e.nq.gz
    ├── 30abcc52cabb38a9f13d0fa0b0ccc4d0e8d44195.nq.gz
    ├── 30e4eedb0ae67e2eccd60e82d1ccd943cf759d41.nq.gz
    ├── 30f51153c5bc11fb41404a25a35de23f9702fab3.nq.gz
    ├── 3221d91d1f2f4b0ad01d7d473f2b4f8049942957.nq.gz
    ├── 336dc289e88d240b3bd0344ab4a4cb9f7fa5b64a.nq.gz
    ├── 337d7874fcd459d8bcb78ffed21d28173d233a83.nq.gz
    ├── 33c7f0cf6ee374089d25d224b6d01f2b386350de.nq.gz
    ├── 33e0c6d40e9ce85d348a9e32f025fe2ccf77627f.nq.gz
    ├── 33e6f09892654e16c40a8ed3c900573d850273a5.nq.gz
    ├── 3525834e217411db3d6916341a4f0c1b5f440193.nq.gz
    ├── 36014c97aef99b0de83d06cab126a94864916800.nq.gz
    ├── 360e88eb59be6726793bca21eb778450d64638d9.nq.gz
    ├── 36241c8b60145d3505d77d7891b9a1e206887f47.nq.gz
    ├── 36f81d4c08c3fc23e460fcba172e44257031753f.nq.gz
    ├── 3714bd18fe8488d4dce79d445b90a15ed0d90a78.nq.gz
    ├── 3740ca437586cfda7893fe2f16c3a57b4066523b.nq.gz
    ├── 37731091c080939d20828747140776b9ecf55556.nq.gz
    ├── 38024af415abed770ad7ca0f026b10c36329c265.nq.gz
    ├── 3877f31384c1221cff835d2c476604123bf49712.nq.gz
    ├── 38c0bb2fe03cc605efa9732786c49d9856dd90bb.nq.gz
    ├── 39614f5868e5ed1b484e3a4f4371ce86658f25e0.nq.gz
    ├── 3974eb5c62168704930e361620c0d6b4a9b0e58b.nq.gz
    ├── 3a6c3f137e0e496b8e0aba185f361050880d3ed4.nq.gz
    ├── 3abd37eccbc1285876328767453be14ea4e19e17.nq.gz
    ├── 3b91ef0173d20f14cc9a7135d7ca529c3120f987.nq.gz
    ├── 3baecbb8fef3056a92b97be0f92a5098deafe017.nq.gz
    ├── 3c9751ef2a584ea2d312066469c04a8a83458b68.nq.gz
    ├── 3c99ee630c4a8adc86c9cea1f4a0f8706e345be1.nq.gz
    ├── 3ebe7c3f82864b35d01c68ee5c62644f1200f019.nq.gz
    ├── 3f45626891d204e1580513ffe7e10c8a917ca1f1.nq.gz
    ├── 3f999fc88b360074e41f38c3b4bc06ccb3bb7cf8.nq.gz
    ├── 401b65d3a35095de68536559d38f828e96e8f51b.nq.gz
    ├── 4099de55c7636905a1e71c5b3bd588ed60cbd06a.nq.gz
    ├── 419fb26177098c461645f643c284f7ec110a695b.nq.gz
    ├── 426d6000c402ee8a5828420b4b32b9bd477ebc8f.nq.gz
    ├── 43a037104f3dfdc4d3f620c8480354507ce6dd27.nq.gz
    ├── 44288ccf66eb3ddd46c051e1d9a6ef1addbbf51f.nq.gz
    ├── 44a495c4a9770d8bb6818091f25cf978b056f7e6.nq.gz
    ├── 44a5809293ca9899cf7ba83bec2301c7e22a8926.nq.gz
    ├── 44aeae4767d27e0135e3377ea6d10b088897c290.nq.gz
    ├── 4585d33fb1ab7897dced40ced45ffeb7bb4caa16.nq.gz
    ├── 462f90e903adc821af17d3175565f48d53c21fa8.nq.gz
    ├── 466fa28135cc44a460ffd003a9d3e027930f0c9e.nq.gz
    ├── 46951c2d485c9df1b4c4fc781a0d7e1079013a85.nq.gz
    ├── 480d02614cab2889c4b86598d1bba3c6f7ec731b.nq.gz
    ├── 481b3c620a3d21baa14c55895fe9762c6095f87c.nq.gz
    ├── 484167f9178b6d6c6ddd91e7c40e43219c7c10a8.nq.gz
    ├── 484a477ca931468716afb5a4453434f0229286a5.nq.gz
    ├── 49700a927f5413c055663bc66fbdb065b43d5215.nq.gz
    ├── 4a2207b9786e265603903f2ad4612417d51439fa.nq.gz
    ├── 4ae86fd087b83dd84601f172869b6407f2c08827.nq.gz
    ├── 4b18dd54b913151d785896c0af5a194add9f2bc2.nq.gz
    ├── 4b8fa3fd06c39a80d56bf0845b79af3cda392b63.nq.gz
    ├── 4bf2f79a0b2ca4817239ae56a016727791d37cb2.nq.gz
    ├── 4c07baac00eae9681561738e52f1ea8c09cdef6e.nq.gz
    ├── 4cedaa075dde1eecd670bcd28b4bddd8be0753d2.nq.gz
    ├── 4d12eccc764b875a14b86f7d9c5824bab3899cf8.nq.gz
    ├── 4d5322051a90875e7c8343f1bd5b5cf798d122c2.nq.gz
    ├── 4e2218875945bb57764f32f97d8a63c67c068068.nq.gz
    ├── 4ec24ae454582816a7d9ee9c0463e92910741e65.nq.gz
    ├── 508c99fe44736c7cf9298574cf34fb5d87c635a2.nq.gz
    ├── 51b5570f661da021a26eb85b49a7ff57fe95d08a.nq.gz
    ├── 51b96ce9e92e362e620289879362d0c38f53e1d0.nq.gz
    ├── 52e85a430af9da4dfb217d71b4d6f3a1d4a4b571.nq.gz
    ├── 531b54441c28771917023f4025c4f9070146fef4.nq.gz
    ├── 5323361d753618d3d394f75d4e1c2da16fa5775f.nq.gz
    ├── 534eb06877f729c148ccc23443c3751f3a3639e5.nq.gz
    ├── 5386b11e56bf24240f7f1b61c341f28617cdecb2.nq.gz
    ├── 5479edeb3d4258054c017fdb4d34bce9ab07eb6e.nq.gz
    ├── 54b572d1f62216507205738dbde6fbf77b3f2efc.nq.gz
    ├── 54fd8b7293c7e38f4a33d02d06c56e6cf8eb3dcb.nq.gz
    ├── 551216d50c1ab82d851c41f6f36c5c099877d2c5.nq.gz
    ├── 553dfcc0985e6120245e5b645a5aa8aa12449d4b.nq.gz
    ├── 5562db8476c6289e3b4197ef833fee605e285694.nq.gz
    ├── 55875726bd8f98a431cdaf290b099d434940ce0d.nq.gz
    ├── 59819ae4def6ad4fcdabb208c9963d8c6bb9cd68.nq.gz
    ├── 5aa214aa5e3cd97e7451a12cff0686544e979904.nq.gz
    ├── 5adfb44179947dfdb0de432d68e5c6bd134ef49e.nq.gz
    ├── 5b7514c0dbd0b5bf014cda24c9056719fc5602c7.nq.gz
    ├── 5be5225a925d1ed70a1b1a3bac89f6e215cf4713.nq.gz
    ├── 5c889b70b53f106951c42efbb05fae3937f55d3f.nq.gz
    ├── 5cad537854d66f5ec3cd1adc92850f79e013efd2.nq.gz
    ├── 5cc03fe28952bf2f7b4b16ff91bf04b1e853c5ed.nq.gz
    ├── 5ced210dbadf400fab36c7412a9dc73565127814.nq.gz
    ├── 5d0ec5218dd242d7a4f9e2e642beb7c99eaf9158.nq.gz
    ├── 5d2523165ff1e23ab5d9665d2c36016c3eabcf9e.nq.gz
    ├── 5e6047fb7c7743bf7e3ace65e961c3d621cc0ebb.nq.gz
    ├── 5f8bbd7ecf5e69f86ca1992a240dd3d554ddc931.nq.gz
    ├── 609337eb91464ddf773f25c182a092b72e0ab08e.nq.gz
    ├── 60d7966cfea79c77133f295a4e67ae9943d72c33.nq.gz
    ├── 61132ef2b01806f6122c31d173c98e01e499b9a0.nq.gz
    ├── 6132eab8ba0876f771320d8a7393d32d86b0ae86.nq.gz
    ├── 61748d179e324e56e15c8d15f91dc82000930eae.nq.gz
    ├── 626a88d1e7261e3a74922b0801d1f707fe5bcb70.nq.gz
    ├── 6332f4b078a0c1e7348cefd820dca84463b7667c.nq.gz
    ├── 63375af9a54b0c2b8f11e7e30b0031b2a1d4d4f2.nq.gz
    ├── 6343003bd4da8f9b40c23eb5912f93da4a78bd9a.nq.gz
    └── 63aad8fd92b531f98aab72a65f152add8367b435.nq.gz

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

[apache/avro](https://github.com/apache/avro)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
