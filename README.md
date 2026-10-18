# Repolex Knowledge Graph of pyannote/pyannote-audio

RDF knowledge graph data for [pyannote/pyannote-audio](https://github.com/pyannote/pyannote-audio), parsed by [repolex](https://repolex.ai).

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
rlex download pyannote/pyannote-audio
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b749285c5cdd4636b2edc7f766f1352c8dde9369
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b749285c5cdd4636b2edc7f766f1352c8dde9369
│           └── chunk-001.nq.gz
├── blob
│   ├── 0006ad6125d910abeecc4198bc2e5fedd6b464d6.nq.gz
│   ├── 0014bed93a745b01465477fe4d9aef241bd0b98a.nq.gz
│   ├── 007900b3d3d4400b1ca18b6f4a22b4b9ee708efe.nq.gz
│   ├── 00b5b883fe59d6e6cff40cdc555cabfba619ef21.nq.gz
│   ├── 01264558b2fb03131b3be3111e202624e7104705.nq.gz
│   ├── 01358f8a4edede16a4dc6976d2ec520d26c9f358.nq.gz
│   ├── 0443863105f79d512fa1233d9f47e040f458fbf5.nq.gz
│   ├── 06cc1148e92b489ebf2c0fa950a0bef92f8e077a.nq.gz
│   ├── 078522434f671968d156e1e8135c123b68e8b0dd.nq.gz
│   ├── 0add0d701af5b7ef69a2d533b8ee64846dfae0b0.nq.gz
│   ├── 1025867245fd55ea0ec2ca8d44710cbb4aea00ad.nq.gz
│   ├── 10d3fb084e0f61788cc13b10d88c50f701866328.nq.gz
│   ├── 1364920062d6125b6561cc0925671b8398a0dad0.nq.gz
│   ├── 150d49a69dc2da2310fbb526759ff26638595bdc.nq.gz
│   ├── 195684132b04c72cd7ac86d340e102836f7a457e.nq.gz
│   ├── 19e7b6d692f86b2a6ebb705fce8c204a0955401b.nq.gz
│   ├── 1a2573f39bd2e3ed8b9c758fb10976b3afeab030.nq.gz
│   ├── 1ad8045c569182ffbf58a80121752aedf266bbd2.nq.gz
│   ├── 1af254995a0270d0d3729c01f1c63c2d4f26e5af.nq.gz
│   ├── 1dae0fb52092fb807ac5d37b56a30730e57d9344.nq.gz
│   ├── 1edcd0d599f715ffb64d859b2a46dfdd39d3507f.nq.gz
│   ├── 216f74f4a06b3f5be21b52cf9f2af7521b4c00b8.nq.gz
│   ├── 22475cf532eb556570f9f3c10c535063c7e63e2d.nq.gz
│   ├── 2273edefa605a6cb19aab5ef9eb85e8ce7c94c99.nq.gz
│   ├── 23317f51e1e9a224331d3e6423758627820add5e.nq.gz
│   ├── 239f402b2b7d28ea6db3fe7723a246ad5c0d3b76.nq.gz
│   ├── 24401f75253036405426388ebe4b72a1747ecac9.nq.gz
│   ├── 24516eace2b491f3200fb4d439a3fed35c657b91.nq.gz
│   ├── 269d3772a76fd712fe921fa109161909ef64a120.nq.gz
│   ├── 270dcb5ed0072fa17065e401b1aaf90555f13bce.nq.gz
│   ├── 2808f0af3cb6945a797b01eb070237c4c174bcd3.nq.gz
│   ├── 2819096c2944bb27acd850d2eaa682f202a59c16.nq.gz
│   ├── 288da319680ecabe5ed423e72b210e8bc44ee3be.nq.gz
│   ├── 2a085201c034a4c2ed151fab4fc04db28f32fa94.nq.gz
│   ├── 2ecd93024a62c4956d59231bc171b520d9fe4905.nq.gz
│   ├── 2f81b393cae3db6f85221305abd8f2e2a7347155.nq.gz
│   ├── 2f9ba3eac24fb789f0434693e13b337f150b63a3.nq.gz
│   ├── 2fdfcdcca48ff49e99fec0bb0593c8d991620bc6.nq.gz
│   ├── 3161876e38cdef55456cc377867446446cf7cfd8.nq.gz
│   ├── 343495f749b22ecc7925cb1c4600b8774639b749.nq.gz
│   ├── 3556a22f72b7aef0f2be7cc5b10b25eb502f09c4.nq.gz
│   ├── 35904d61a819ea97833d1d0d7670b2b49a559d1f.nq.gz
│   ├── 3886a0eeb08da0147583661145c92a993fd83060.nq.gz
│   ├── 3aa4ad45608548afba7992727dd007d3b2429863.nq.gz
│   ├── 3b59990671b76524715f9fc225a6c0ea6622f7ef.nq.gz
│   ├── 3b7da4665e7a1a4958d0cc64b5d7fc0b204a96e4.nq.gz
│   ├── 3c542befa6272dbe78e4dabe5055b0bb2e201c7f.nq.gz
│   ├── 3cb76e8841b15a81e04f8b9e1e4e495d6707800e.nq.gz
│   ├── 3db60c928d2899685973cb64ee5f6bc55f1d7a37.nq.gz
│   ├── 3f8d3ccf908e23053bbeab58771ba06ca1a47512.nq.gz
│   ├── 420a62de0787f125000ef02ddb38057f5bb2827f.nq.gz
│   ├── 43230d7a18062e391447f63c56090bba8bb938bf.nq.gz
│   ├── 4574c1c3339137a2a918ebea7c8861cdc320071e.nq.gz
│   ├── 471bf03d45cef5508a753f08b6e9602eee9f6cb4.nq.gz
│   ├── 472ce7ac0947b04e618a37f77421827c3a481089.nq.gz
│   ├── 48793258814f534b9c5cffee8f117cf98659db5b.nq.gz
│   ├── 4ae38aeb1b9fbd2aa19890478453d6fe1a73722f.nq.gz
│   ├── 4baeec97c661c73e64c5ab80fdc0c91c28284565.nq.gz
│   ├── 4c9d5a5f0f337e74ea878bd4eeb58d92d288b53a.nq.gz
│   ├── 5122ebfac13caca6fc6149b5fac2d9530966b4d4.nq.gz
│   ├── 534faeb34600784febceabb47e588f49214bc65a.nq.gz
│   ├── 535da47de4b10b6d81ada119eadd877adcdc1a84.nq.gz
│   ├── 55121a6780dd90f49d30c6b49c3d49b5f3bfef55.nq.gz
│   ├── 56a82af07ee47d7f308dbc4e2ae82e661f27d768.nq.gz
│   ├── 58c1df142ace9e20ab11ba6786fcac2750a40cc9.nq.gz
│   ├── 5945873d71ba5ddb2fd91a8826c046c85940b784.nq.gz
│   ├── 59857b3a1dc93e3eadc5a93ff9f0642933b4e2d0.nq.gz
│   ├── 5997b7bd5cdd3a37530f78d699646cda4c561a6a.nq.gz
│   ├── 5b6dc0cb7873e0fabb71249dfb7cdee228c36c7a.nq.gz
│   ├── 5ba6b4fa33e45401956b3925d5fa1c21ca890cc0.nq.gz
│   ├── 5f544ad77ba8c8369ac1f01c06008cdb37652389.nq.gz
│   ├── 5fab89a8d2241905b989bbca45b9c19f1e58565c.nq.gz
│   ├── 607d547b2568a50c6abb185e987de283d6c1d4b2.nq.gz
│   ├── 608d710921a2d3e002bd80eb5b114f4d6bba4833.nq.gz
│   ├── 61af590a188173b97bd9c9928a1d3568fe378b91.nq.gz
│   ├── 631d29812fe9196089d7af7cbed9abc73f046f44.nq.gz
│   ├── 640b06327b80abb04463d464d0072b6abbfff0d8.nq.gz
│   ├── 656eae4a757b0476fb6a59f7706976a29706d685.nq.gz
│   ├── 67a84f841d0143d030a574eef4f40a50c53a7b0f.nq.gz
│   ├── 67b544284d8e3cb52f8c5db2679b7708163fbd77.nq.gz
│   ├── 6bfbca13189496adfbe11626001f751fc34817fa.nq.gz
│   ├── 6c4789fd06676961a2d4d7e31089614353060089.nq.gz
│   ├── 6c49e7589de5cd9a5e7b0887081bb88325ddda8b.nq.gz
│   ├── 6f024c73b57473ddba6a08751c5d25883894edd5.nq.gz
│   ├── 6f0ed9b2eaab125b88c9399cb27715b8b74957b2.nq.gz
│   ├── 712b6f0d45604416a6742bd77dfbedd016a7e11b.nq.gz
│   ├── 716526d773f283a583cc99528dd853aa13110ecb.nq.gz
│   ├── 7504e5bb28842e1f06bfdc89af1ab376bc89d37b.nq.gz
│   ├── 759cf1321f0ec860cceb5adc934e2ef71abb3ce1.nq.gz
│   ├── 761cf21c37511aec6c76395d8c9d5d0de8d664ae.nq.gz
│   ├── 7688992700d0d28b403ab44530c362699516a768.nq.gz
│   ├── 795666887bf38de2c301186fe261f8a5d4e31c34.nq.gz
│   ├── 7a57dbd1053955c09b2790a4f63f3175249e455b.nq.gz
│   ├── 7bc9a3d4c6d794a10aeebac425bd75eaa60010cf.nq.gz
│   ├── 7c6b378febff6a4a0bbd4578669b62c2028ad0a2.nq.gz
│   ├── 7cdd27eaa7702958aa199723988e935dc1623bbd.nq.gz
│   ├── 7f1594f0b3f86306e9a0fddc41774c4b0d8c88d5.nq.gz
│   ├── 8105001789c0aa89717770873a41400ca3419636.nq.gz
│   ├── 84b840ac98cf1a348f1ff5344047f029d7d19024.nq.gz
│   ├── 84f6ea55a0a8a163bffa33bc01ae61723418f04d.nq.gz
│   ├── 85e920cccb7fd2dfb4c6863cbadbc2793ce09092.nq.gz
│   ├── 863811086cbd77c59a90fe00ad3287282b921b82.nq.gz
│   ├── 885dd76cd15e71f400bf67456ddfdc557c4fe7d4.nq.gz
│   ├── 8973751a7a9b5e4612f98978b979b9a9ed58ff00.nq.gz
│   ├── 8a11ed0d17699bd2bd7ecbf85665d658b52ebcb5.nq.gz
│   ├── 8c0edd878d01c68781fcb6550a247b52931220ae.nq.gz
│   ├── 8d64ca7ed05f2a4d20f73f707e1bc7288e41d6ee.nq.gz
│   ├── 8d8775a4ac1b255d9bf6aadc3603b281046b81d8.nq.gz
│   ├── 8f08ebc3bce903d9a2f54a175510fbfef66a5a1a.nq.gz
│   ├── 8f3b162e713996eb1b126cb799b5b8af11678d2b.nq.gz
│   ├── 8fc5335ffabf562f63be808df090be298dbaead4.nq.gz
│   ├── 918282b1fc63d51481a9677322bce1f612015a36.nq.gz
│   ├── 92c952bdc6f0c80365c7854f68fb7bf9c626ee6a.nq.gz
│   ├── 9336b47b1da0e6ae7aa1556d713a9576cbbdfc9f.nq.gz
│   ├── 935580fde38632e0f9d1ba43daea1258edb3093a.nq.gz
│   ├── 9712e8a75f3b007849124dfb5653863925fdaaf9.nq.gz
│   ├── 97e19054e4ebe54396e9ec245ec28c4d2c8de0d7.nq.gz
│   ├── 98f2692d8b5edeef2cefc645dd7aa1601a8798e7.nq.gz
│   ├── 9f6f5f6e3384b4e9eb777b99c3bf12df53e8f571.nq.gz
│   ├── a18cded8aeac3bdeb5448add107f842338040d95.nq.gz
│   ├── a263193a813ec67bbdf09e6d1b6b972eafc55f50.nq.gz
│   ├── a3c16376c35764f1b5bf2bfc3a23917aa523fda6.nq.gz
│   ├── a48e489e1405b628cbcf5f893ea3b2c4e74b2467.nq.gz
│   ├── a51ef855b831e8feaf822a15abe88cca7d6bd2ee.nq.gz
│   ├── a6b79c461508fbe5668169149ef1308936f9c462.nq.gz
│   ├── a795392e91f6801f46834011e9abbfed9bcf9ad1.nq.gz
│   ├── a99295a1640fe95a5ffc6e90a2b8954c18bdf9d3.nq.gz
│   ├── ab0540b41a6687d0f68d29ae9960018f69d9f7f7.nq.gz
│   ├── ad099ba09a4f854f0111020df957b7959cf6d77e.nq.gz
│   ├── b092839080d43bbe9881847717abf920f88663ad.nq.gz
│   ├── b15ec465065caa8fd3d6c6995a7f9b54647801a8.nq.gz
│   ├── b33e6428229ddddd774a08c0512271daa140aabb.nq.gz
│   ├── b3e2d4edbb58a9fc3c25220859c12def849efc7b.nq.gz
│   ├── b53ae3b44701a74fb1107231beef1e5e5a121152.nq.gz
│   ├── b572e3d28c75e5a7be41430668a378278761dae9.nq.gz
│   ├── b7760cd48525412175ad4dabac8b43dc1c7cdb3a.nq.gz
│   ├── b907be4ac5c1a49694ab8b99a9a5fc4f9d80a28c.nq.gz
│   ├── ba9c2e2c34dd4c6eaf991de8b48ba245512a457d.nq.gz
│   ├── be51196c1fe9a9bfbce9429f9cb63ff7790d28e8.nq.gz
│   ├── be89e2a4c8be841a4e9664abcec7d1a945e8151d.nq.gz
│   ├── c004daee0dba6c34f5261f610e608684d2a5cc1f.nq.gz
│   ├── c1c23284293c628cd8739fca3acc8bcc7b1507f4.nq.gz
│   ├── c366dc091143746134f29db35ce180646bc2a440.nq.gz
│   ├── c3ff8d83309f51bdbc4a7a0bc13692f894ea5ef4.nq.gz
│   ├── c401b70ddca62c4cb679d2c038821feae095c498.nq.gz
│   ├── c4a09ffef5b32a0a8bdf51274b14af09b4eda8dd.nq.gz
│   ├── c8cfe3959183f8e9a50f83f54cd723f2dc9c252d.nq.gz
│   ├── c9e4d44a0b4d3830ae574cbe8e5fdaef42039795.nq.gz
│   ├── c9fe5136444891954c316c5900d48a03fa6fcacb.nq.gz
│   ├── ccb4b67824776f275d8b732c42a12e45801e6cff.nq.gz
│   ├── cee945664ea0bc46a604fd6b849deb77f295c998.nq.gz
│   ├── d14308bb12cebccb634bfd4fdf16614d462c33d6.nq.gz
│   ├── d3b5495a4e17fad6692339e79e08c0e6ab079e73.nq.gz
│   ├── d447a90809d8049b2f28d1883f9ed67809bdcffb.nq.gz
│   ├── d47dc9613324b144adca36dcc98c3f16c9a54467.nq.gz
│   ├── d598a73a6c952906d8d9df71f4ebd5cb73989db9.nq.gz
│   ├── d9036deaa70d3595b11803db61aa950058558e0b.nq.gz
│   ├── e044807535fbb8fdaa5ebbe93e84c73d4634025e.nq.gz
│   ├── e197d0312c449f941dce4d5910bc4fc27bd4b4f0.nq.gz
│   ├── e1d843854c5b8dd8fb5ea4c8bf3d5a89eadb03e2.nq.gz
│   ├── e2bc13f93f41d8dc866709f75aaafb2b8ae6ad67.nq.gz
│   ├── e30262eda034f30f43721ad73ab8e05845584e19.nq.gz
│   ├── e47398e51f3019c08819f2a547ce0e163b1234b8.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e733072f6d9c47188b37a074e58121c567ff92e7.nq.gz
│   ├── eec3d849c8fb3022bf1eb589be4281734cad5daf.nq.gz
│   ├── ef803e86b0b688026a4fc484958c7059440f7fc6.nq.gz
│   ├── ef8ecd69df9a3493db1685623cf1ea157722e5a6.nq.gz
│   ├── f0d5898418a984dda1983a617826b768846fbe8f.nq.gz
│   ├── f1daf0c108f09c69c7ca8b1b1a64c00e670f47c6.nq.gz
│   ├── f46872f8024b9c0e585f7bf39cfcbd3e4ead7432.nq.gz
│   ├── f473198d546d04323785caeaeda7707c04f1b61d.nq.gz
│   ├── f4ed42bcc31b4a5c70b1567511d5d387b15f1d90.nq.gz
│   ├── f5fb7ac57ba9b4a98dd296598e2b5659547597f3.nq.gz
│   ├── f6f59b1eebfb81609ee66192a789eb5f827a622f.nq.gz
│   ├── f8fb8b2faaad31065f7ecf40f9f5b3ce3b8142c7.nq.gz
│   ├── f99f1c12ce197a6d335c4f6c6540a34ef0b67e4a.nq.gz
│   ├── fa86eaee68840171e541fc3ae28053a3a4b29a80.nq.gz
│   ├── faba74db9d8996ecec4309deac539f0e5ff4b2b2.nq.gz
│   ├── fca558add3032080fc8bc935cd99d55b3cc41ae8.nq.gz
│   ├── fcada57a3d650322ca1fd92cc7bf8cdae7982a72.nq.gz
│   └── fe2a00e122680934c4e85379cb7f6197a3c184ea.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b749285c5cdd4636b2edc7f766f1352c8dde9369.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 190 files
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

[pyannote/pyannote-audio](https://github.com/pyannote/pyannote-audio)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
