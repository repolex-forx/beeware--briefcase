# Repolex Knowledge Graph of beeware/briefcase

RDF knowledge graph data for [beeware/briefcase](https://github.com/beeware/briefcase), parsed by [repolex](https://repolex.ai).

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
rlex download beeware/briefcase
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d94b1eb06d55d1cf01559f8818b1df0625a3ea3d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d94b1eb06d55d1cf01559f8818b1df0625a3ea3d
│           └── chunk-001.nq.gz
└── blob
    ├── 00a20891122d1f5dcbe2f9c9c23409dc563f7a06.nq.gz
    ├── 013ae27272c47e033db209eb88b5df6a5b3ba036.nq.gz
    ├── 01c9394916a17cca2c7b6c47b1183b4ca6ce9646.nq.gz
    ├── 0207fe2f3ff394980f07c132b1e44be4c6552b2c.nq.gz
    ├── 0219fac4642079769c1f7f67c207f597ebd4f360.nq.gz
    ├── 026ddf36434a8f35f84fbc15f46796f9da868221.nq.gz
    ├── 042859348c89004d9fa852715a6c0ca4e2b304f2.nq.gz
    ├── 042cc18e584c8d190c6e4a5252d20b1c5572c7f0.nq.gz
    ├── 047c8b9c9ef952f9fd8fc86e65f5fd6f8a37b955.nq.gz
    ├── 04a45720221866ee1bef7065d78853c802a0169f.nq.gz
    ├── 04b4603c9f90a65a2f18a2533262b8e4592fa334.nq.gz
    ├── 0518d102f59d60fd2ce45a133aa335f401363893.nq.gz
    ├── 05b8e795f5efb0d40f4e5675bb016c65ece32d4b.nq.gz
    ├── 05c6dbfba8e542d3083b513a4c02f88485d20350.nq.gz
    ├── 081227eb3861589114128085d1459f790bc3c238.nq.gz
    ├── 086b413b357af34da62dcccd67c1be41f640f55b.nq.gz
    ├── 09e5ecad120b3acc53aee081a40dae14714cc01e.nq.gz
    ├── 0a039c7a2c2b4cd0d540ae13a3894ce4f0193742.nq.gz
    ├── 0aa98466fbbba0defab20d4b76a1cf3d796f66e9.nq.gz
    ├── 0ac726187a88135bd2b4396e301c06acecdd4098.nq.gz
    ├── 0b1c6cfc215463ebe350a44db9533dc82b165ac6.nq.gz
    ├── 0b8657e41a26506268c7c6d4de54d03f17311808.nq.gz
    ├── 0bbb9fd6d2c709cbae0db109ad6aa414e3ab7331.nq.gz
    ├── 0c69a0449a9a560cda1259debad2c1385b5bc386.nq.gz
    ├── 0c7763459ad82e5643b22b51f3cbbeefe7c65b92.nq.gz
    ├── 0c8522c5d849afc884e585debc65ffeb7419771c.nq.gz
    ├── 0dca233d109f5d790c167081b2d4fa0f6589884c.nq.gz
    ├── 0e0955c687588b9ab65cc3623616fc34b61f03e0.nq.gz
    ├── 0e120440aed6d0660a59761cbaf71e0b2c93c669.nq.gz
    ├── 0ecfd7e60a2add4fb05c8d1d6dad3010bbdbfaee.nq.gz
    ├── 0ef64ec246e63ee2d9cdbe241b9e267d5ec2608c.nq.gz
    ├── 0f6197a3e262bb6c20a9f5195d2f4c205d24a8a4.nq.gz
    ├── 0fd4eb738603d1cde6ddbff060fc7b52e84ccf6b.nq.gz
    ├── 10acdbba678ce636c7c078bd42867636b4793ae5.nq.gz
    ├── 10d850bf26abb68bfcb5bf96c2c0420108aed843.nq.gz
    ├── 1101b80e1500a7b2102ed4757183a1fc3918c8be.nq.gz
    ├── 11343e62e0683959d366f038acf521c9f739dda9.nq.gz
    ├── 1152e030a3579b7ffa4efd355fe83f685fa1a2a1.nq.gz
    ├── 1159c064c66590c1ea884824377c258d4c521467.nq.gz
    ├── 11c9d77f6a8ac617bb27301c3f69d1c04f0d1b63.nq.gz
    ├── 13461855fe22f5af88cfdd3c80fe8c0b5c7b4552.nq.gz
    ├── 13688dea5bc996b3a9adaf3ad729846febccd2c3.nq.gz
    ├── 1498f4066e9e2681932c29a67952145e9314ab6f.nq.gz
    ├── 14eef273475c9ad9110f008d853d5b05930b51fb.nq.gz
    ├── 155c128dd90eecd7a41a4a9c11da5a42e5af25bb.nq.gz
    ├── 1619efbc06f54b57231d9cbbaa9e7ea7a60f3dab.nq.gz
    ├── 16e7c78a570fd17b087cc433c87313edd636bb8b.nq.gz
    ├── 188e206e90e2054e0b1ef9d267b3c7c587dff027.nq.gz
    ├── 19a1bd79a309157fabd607d6812090bae2a7d6bb.nq.gz
    ├── 1bd1bdd482e72ef5dee35bf58ec9289b0e77f2d0.nq.gz
    ├── 1c4551aee08d8dce567dee99628e78c4ee3f97fb.nq.gz
    ├── 1d5717a15edb7ad50e8a9ba0d2853c6985c33055.nq.gz
    ├── 1d8e7103abb1e4db443937ecb1d2f0844620e032.nq.gz
    ├── 1db3fbee263ee41255a5d1583248dadafd2298c2.nq.gz
    ├── 1dce78ddde588b01e0fb2138cb35ed7d8eeab08a.nq.gz
    ├── 1e6d94bd87e74fede1b41eb7aa5140a198552af9.nq.gz
    ├── 1eaf1cf425e517d797e0497e10207bcfae5c964a.nq.gz
    ├── 1ecbcddc30f09dca8dc43de7cddd0ad78999c82c.nq.gz
    ├── 1f79dbe8d30834aedb897a4ab0535d2bd4fd3706.nq.gz
    ├── 1fae15888f4d54898590b7b5a02f9d6601746b2f.nq.gz
    ├── 200c3719d4febcb20e85787dd8a53b981cf3da7d.nq.gz
    ├── 202e25f782352c5e0123ac585124b1cda3cb8c72.nq.gz
    ├── 210088fd5cea8edda78640b54337c9b7fa92b51c.nq.gz
    ├── 2163831c5e2cb0d9a31c4c2deca6a20115b713c7.nq.gz
    ├── 21797bc85de053ca7470255d7e3f4dea724231da.nq.gz
    ├── 21e481b11f26e45424a42916eaf9935899fbdb6d.nq.gz
    ├── 2222c33c3a22fd4ed2a016cf00281958d6b3c945.nq.gz
    ├── 22718a3f36fe0cec5a84589cc434518ad0e4799b.nq.gz
    ├── 22e69c8cb63d4b3bfd0e31966d90a5df763cdaad.nq.gz
    ├── 22eece0f0adb5f36831ded2e752075810e861808.nq.gz
    ├── 23c9c1e3e09e51a0feac0b1cd1a59d4469e8bd71.nq.gz
    ├── 23eef0ef467f78b166ea176f3e2bc609c5b7c7f0.nq.gz
    ├── 2416b62c9a834a50111add0fbcd095ba657568ea.nq.gz
    ├── 24e28bc1d5257e75fd62c14899a92fa9414c3132.nq.gz
    ├── 2516f6195312a0d0cb093f76a82bb4f30ca4e8c9.nq.gz
    ├── 252d728aff6d51d52600864d17a4494d90303d9f.nq.gz
    ├── 257621401e78bf5d5c9e21f48078d6419446102d.nq.gz
    ├── 259dfdb83bb652b5870050dc51717ddec1a9c18a.nq.gz
    ├── 25ff13b845540fe34cab27be18b08dd62ba35b35.nq.gz
    ├── 2669baf6163b60a8531db9000a3f18abcae6ff2b.nq.gz
    ├── 2741881193cffa1a34f53fbdd596aedb0c4b9c2b.nq.gz
    ├── 2749fbca142e209f6708feafa807bc5f6f183b72.nq.gz
    ├── 27b935dbe3e890920b22b60276adb2fb187b043b.nq.gz
    ├── 283fc09e3e2b03bfe3a69de1685e436bf0b37220.nq.gz
    ├── 28929c05d61c1606b8a5068e065d8ffa107c96e4.nq.gz
    ├── 28a50a861a3558a5bd867768e0159727e3d9fcdd.nq.gz
    ├── 28b7139f33d6c78db48a164660c3b86a7946771d.nq.gz
    ├── 28def00ceb938ee61e1c514fe075bcca560133de.nq.gz
    ├── 2977718e2baf572bdd12ec4188abf1c966128e07.nq.gz
    ├── 2a0bc0d9c2098c8fef27bae3bcda0b810eb87dae.nq.gz
    ├── 2a3a7fcdd4d255f72548879688217fe0d730a9d2.nq.gz
    ├── 2a64b39c6c255e6e056ec65f2931da9c3d79cf1d.nq.gz
    ├── 2bb7c1dcae92889aca11e94b16b96fe6c6db52a7.nq.gz
    ├── 2bf27465efc32593817757fa4ffb11cab9ab9e30.nq.gz
    ├── 2c60a0947870c0e6a857deed8e5f3a319cb04179.nq.gz
    ├── 2c854b268c4783a464bb39a9e5c8d9f94ae543f8.nq.gz
    ├── 2c8843a4a37e050b05908eb3a8c1b5f8a04fa305.nq.gz
    ├── 2c8d8885d1b2c0d9757b4b32aed45887e9bee836.nq.gz
    ├── 2c9fd71ab4bed8fb14616068999bb524eefce8bd.nq.gz
    ├── 2e8dfbc74601fb8afa33321c94f73739d77c057b.nq.gz
    ├── 2ef97e4828493fda31f2d4f9427245f0949540ca.nq.gz
    ├── 2f2392c13fd76ea8267abef4df771df167789069.nq.gz
    ├── 2f2e1067ddea64b29891f5dd4b1b6a6c1c1bc1be.nq.gz
    ├── 2f41fa9bcf40322d02eb31f15f837bb49566e37b.nq.gz
    ├── 2f68967702fa2871a84733fe411f2749ea8cb6c0.nq.gz
    ├── 2f74a8cb2e65b26c370e4d45bd315f159076bf10.nq.gz
    ├── 2f7871a1342c1d9424f35aae713629dd658682c0.nq.gz
    ├── 2f867c589b5c1b116808e948457bdc267e820798.nq.gz
    ├── 2fd0d19b1526f3ad97e3915716bf259a7b354bcb.nq.gz
    ├── 2ffeb959bf1c3c7d5a147baa7fb70b564d4ef375.nq.gz
    ├── 308344723de9a9c219150207ccbb24a5ceb45f95.nq.gz
    ├── 308d9da21f687b0df242b535c60fa9b35f5a4181.nq.gz
    ├── 30e8d2faf66511a389a0b8f84ad2503c989cb152.nq.gz
    ├── 30f3f0c0ba447d071035ebac4492e5d586f1735b.nq.gz
    ├── 30fc27e4c6dba07ba39eb97fab43fbd57afa4dbd.nq.gz
    ├── 3100271040ce29bf3e76c733e823313a178f1fb9.nq.gz
    ├── 3160eaff77ef7de3a3332a63206dcaecedb7739f.nq.gz
    ├── 316bfa0609619d4de1e6a2c2d110e36cf39933b3.nq.gz
    ├── 31dccfdf7adeeedc0f94b2183b5c709aacb22288.nq.gz
    ├── 31fb980fa877f613ec03995db33a740bc906b4e6.nq.gz
    ├── 32c62bb77148bf803b0b14e3fbd9702152d3d748.nq.gz
    ├── 3304f8e9e4d85d66fef219bf5b63c27699c34a90.nq.gz
    ├── 3326d84b04bd33c7a5340dca5e3d34700c6e6b26.nq.gz
    ├── 33478d6383cc42625065114d874ae24f4915cda6.nq.gz
    ├── 337b7e6270f264a108b58812d37facb8ba4dbc22.nq.gz
    ├── 3394cfdfc52635ff0ee9219fffb3319501a7885e.nq.gz
    ├── 33bc9024d4d9cc32ea9047860e5b8fd90a35b21f.nq.gz
    ├── 33cae2720609c17148f14af3c8a26304d2d1c79e.nq.gz
    ├── 3456bb7a063c2b66f059c2e8b8e1ebeb8c6fd429.nq.gz
    ├── 34a4ff4a9775d18e678a38aa14948773abc344f0.nq.gz
    ├── 379d816988029ca5274ae3b3cb59b3accf2e239a.nq.gz
    ├── 37c178aa975500f3c3631a3226b0992ae6597ca7.nq.gz
    ├── 3933638a3b10f553869ca04f9ed5294c10f4dfd2.nq.gz
    ├── 39f017726b07722732f9ac2668f7f3d45c7fb735.nq.gz
    ├── 3a0c5fda2a35d23699f39cafe98d60cc7dc4cd3d.nq.gz
    ├── 3a762fd885855fd44dba63d13ea77fb74f4f0dea.nq.gz
    ├── 3b78e8f455b7f560d7d0232035798f7df7e2e614.nq.gz
    ├── 3bfce682204c2ad4f5971096d1a0b1ea7679e3a0.nq.gz
    ├── 3c8562d42a9a5a75ff5f413b8e62ccd8478dcb6d.nq.gz
    ├── 3c8ff60bfccc2543edbbabaff2d95d343c61ee12.nq.gz
    ├── 3dd3837f1b02bbb2bdd5183593a1c5db987fec22.nq.gz
    ├── 3e6f8353c4240f729c60d91be489c5703a2ca230.nq.gz
    ├── 3f205d7d52ea717a2442b8016c0bc11b7dd8c49c.nq.gz
    ├── 3f46bca7fb3f463dbc64c5f049b947bce8e6d547.nq.gz
    ├── 3fe2a0dfc2df26fdddce90780e495b3361821759.nq.gz
    ├── 402d474acca726603b392d9e8552c80f0dff3781.nq.gz
    ├── 408b2becd667158a2a88638e72092ecade7d2199.nq.gz
    ├── 4170c350018e308efa627d657921be98c0078ebe.nq.gz
    ├── 421db587bb709bd0419c59cc2a9a3331b50262be.nq.gz
    ├── 4280182fed0d5f4519b69460bd3af77b5ba534c0.nq.gz
    ├── 428549e600cd7ff13c8a603c555bb04d6e95f946.nq.gz
    ├── 433586da49289be78945667ea4399da3f97db83e.nq.gz
    ├── 4461d81263f7502afe0890aecc9a40c7fd20640e.nq.gz
    ├── 4489a32eb74ac4dee71108eada8207f2aeed179d.nq.gz
    ├── 44a7772c7d582790ce580367a74b00454bd6a0f8.nq.gz
    ├── 44b1aead973aa5b2c03ece6bcab2d743f4088cba.nq.gz
    ├── 44f9cf025d442a91f9566822ef426513a268252b.nq.gz
    ├── 4545359b2acaa97a0fe3bad4de00e3885ed15db5.nq.gz
    ├── 45555f3b9ecbcea99d2c9d45782fda3656c67d7f.nq.gz
    ├── 455ba811f9bded150a1df52c7eee467e46229268.nq.gz
    ├── 45a18410d0d7fe12059b7ac9a771438a3fa78105.nq.gz
    ├── 46392edbfdfde0a7ffa05bbb5819de8de051823f.nq.gz
    ├── 46e750e934f5669ec92472e48ce91ed61226f6bd.nq.gz
    ├── 47865d135f00b8d1679f4feb763bfcd2e1f9022b.nq.gz
    ├── 48a4dd38602cac488365774c953fe0f68b958a2d.nq.gz
    ├── 48d0919a3d2926bc85c51627988ad3ec7ea43b0e.nq.gz
    ├── 4921b3a6f57708696f4a812f651c02afcc96b8e9.nq.gz
    ├── 4987b20340f7b7f1a58bd987455f4170aa6e6a82.nq.gz
    ├── 49e20c0b2ef6b0b70ba2037d0f6c0cbf1a91e923.nq.gz
    ├── 49e8ec11b8e7f29c4dcc547164fb9bbd5341bb13.nq.gz
    ├── 49fe63ea1bedb9690749ca7b8d7adac9c99b77d0.nq.gz
    ├── 4a72d2d7ae0999d12be795aaf203af8f2eadbf34.nq.gz
    ├── 4a86da637d1e798fc876265993d762e515950063.nq.gz
    ├── 4ae757cfdc33199cf2e3ed8bd6c8fba14a95c437.nq.gz
    ├── 4b5e158da1366f3b2f47452c7bfdc3bebbffbe41.nq.gz
    ├── 4b8963e54e7c36135e45ad09f6c6465dc8f615c6.nq.gz
    ├── 4cf34905d0432c28a85ccd85289a7783447e9f7b.nq.gz
    ├── 4d86d564f3268dcc5dd8ef247155ac0f258b5872.nq.gz
    ├── 4d91ce19fb10358831a18f7e54637be5814e5879.nq.gz
    ├── 4e033fa1c4f1bc945ade7cb9fdda36e882e25d8a.nq.gz
    ├── 50a174a35eb80d6d1991e366b275b50ac5385ebf.nq.gz
    ├── 50bc284369c4fb79a0c42a8bccf3bc56911ae435.nq.gz
    ├── 5148b5d5de40bdb21543e72041db2cb88c685bf1.nq.gz
    ├── 5164a0a1d28d2ce47bd42185e6484361522e2b05.nq.gz
    ├── 51b102ca1323e9f8a5cd6e232be69b3c6eb76a21.nq.gz
    ├── 53c648389d33a98b16feb82601dfd7ef0f319337.nq.gz
    ├── 53d309d411966d96f0f61df7dbd5e3b6d2d6b04a.nq.gz
    ├── 546c5ec2148ac678f15a8ca65430bf50585cb428.nq.gz
    ├── 5513af95ae3df732af1e42368a4a321f2fe1e0e0.nq.gz
    ├── 5581f9348a51420c2a62dbb0539587ec5c62195d.nq.gz
    ├── 55a863c0bb6adcc6e1a08958d3e20929d01e7683.nq.gz
    ├── 55abd58334e14b895845680c6009136c6d07edc9.nq.gz
    ├── 55c9f6bd369f11172fb7ab667ea696b6bbb5bf54.nq.gz
    ├── 55fa213f88d00698469cc1575b4bf0688ce80485.nq.gz
    ├── 560e6dee38d06f1069854922aad06fac174171d5.nq.gz
    ├── 585152759c4d16a9cd65955be25dca9e4fb7eb7f.nq.gz
    ├── 5937a49d051639b7de6489697100a46fa4be5545.nq.gz
    └── 5960c144580fb76f8eb8f8dc20402df951ba659e.nq.gz

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

[beeware/briefcase](https://github.com/beeware/briefcase)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
