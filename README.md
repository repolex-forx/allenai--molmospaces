# Repolex Knowledge Graph of allenai/molmospaces

RDF knowledge graph data for [allenai/molmospaces](https://github.com/allenai/molmospaces), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/molmospaces
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1c2d511e224c7baf38332fd20fd28f7e1d25ab08
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1c2d511e224c7baf38332fd20fd28f7e1d25ab08
│           └── chunk-001.nq.gz
└── blob
    ├── 000b8d7cafad4578b5bb75cf464a99b8101dc4f6.nq.gz
    ├── 001684e3402bcf95713e632a8be695e4ac4fdeb5.nq.gz
    ├── 00ea931637b179b170755c99b8a60abe2250b505.nq.gz
    ├── 024aabd56bc7a34cb8fe4999df405b4a2e5d5a92.nq.gz
    ├── 0280e8f8d6a3c044fb26c0cf6e89541e0150e69b.nq.gz
    ├── 02ae2ecb60aeae2f4eb68c0ca23aaf125a4628a9.nq.gz
    ├── 035fb615573e7da92a85f6064b934b3c25a6b6b8.nq.gz
    ├── 03d160c73e688e3e433e8e62f8a4675dc10a8240.nq.gz
    ├── 04673d1ab990bf152b96a38285f2a92b2a8f7f48.nq.gz
    ├── 054d57bb8a715e620157cc2b3d05bd8157fdc520.nq.gz
    ├── 0635960cb5d8be5f9fa3545129fb8f95951db51a.nq.gz
    ├── 06fac0ebb0af9d50a4d4f6fa60caa8db3da59f35.nq.gz
    ├── 07c17cfe996727439f3eff3e84580f308bf52c79.nq.gz
    ├── 07ca362cbf558b778eabb0e22f5ea1a52241e6d6.nq.gz
    ├── 0808dd97d19d11d425ebb1a296bcbb9c252e04f6.nq.gz
    ├── 08d18a9246397d245303987fb8ea217c0cf5c4f3.nq.gz
    ├── 0927b01946ff03291f20719f4994a88b59a9f04a.nq.gz
    ├── 0956e1e16beccab6d96d9096fa2f670748ca64da.nq.gz
    ├── 09bbce2f66efd7afc7c2f580aca6021ac7ab9a43.nq.gz
    ├── 0a02ee23259b5b76d26c739fc23067c9d9358125.nq.gz
    ├── 0b06d053593f254cc934c44845eaf8f2525e16da.nq.gz
    ├── 0b34a2a958561d9ef5f85203311e4605aa1361a8.nq.gz
    ├── 0b43fb2d2c9fbcd060f7c3d40ebfa592a721cecf.nq.gz
    ├── 0d26be5bcb68168881a5b191ad29bc7a44e536c0.nq.gz
    ├── 0dac9c849bbcd1aef77647a9ce5d761d75a189ba.nq.gz
    ├── 0e770a89acbca10a660161c4e6f6377175680ba1.nq.gz
    ├── 0f5182f7478c8f510a82a15079c2bfea53917233.nq.gz
    ├── 0fa341fc98bb86bb2058ee17a4f4017d0102b450.nq.gz
    ├── 0fc2f00cea3bf57e296f0ef06c3d41c163c85682.nq.gz
    ├── 1014819cd03585729c32b8224664a4009ee7b685.nq.gz
    ├── 11db8ab59746c5e4eb58c770bf4f0118d03b6b3b.nq.gz
    ├── 120365068e88dd6771cd72c0168435acacb3664d.nq.gz
    ├── 126020bda82fdda4e49aed28c77fccbcc9491c21.nq.gz
    ├── 134658a86c4ccf190169d8885dd4669a7320000b.nq.gz
    ├── 13e76787a5dccc2123f5b56d4e8f4eaf55f3665b.nq.gz
    ├── 14f4fba071faabf4a473a59c51252dca6d1db530.nq.gz
    ├── 165ef2ea163e7535b459d1f60a9d7580d181ec75.nq.gz
    ├── 18bc2f228220f31aa728dfabb83e01a05e9faede.nq.gz
    ├── 19fe8f51efb923b87a9ff1709a774a12fac9ed45.nq.gz
    ├── 1aaa8550b3b570b72f84f6c4e2b2f9a70e86ca40.nq.gz
    ├── 1aba23616cba0e66a0474f03d560a2fcb754fe92.nq.gz
    ├── 1b0d946eff4cacaefaf34a455cca7f17702f970d.nq.gz
    ├── 1b742b4b8b12c5eca9d083c1a9ee7b68de683df9.nq.gz
    ├── 1b82595e030d9086286ed0c3173c957760ac844a.nq.gz
    ├── 1b8df08d89a63521bcbe362b560508010f269168.nq.gz
    ├── 1bd33e571cf8143ed3851a3a1e2eac52cf85cc68.nq.gz
    ├── 1c01c00a9ff4f831f20b8d346eb4131f0adfda70.nq.gz
    ├── 1c325142497ef3990177bca0b9cfed3e601996ae.nq.gz
    ├── 1c7ffc32791b9bf96843e8e5890ea8ada5da6b2f.nq.gz
    ├── 1cc3238ae969c96fb06fd0d0f8a97fb74eed3488.nq.gz
    ├── 1d17944c9048ec5859d619ddcd41344a1d23b07f.nq.gz
    ├── 1d18b7847f5433205a66b79fe36f35d865f29686.nq.gz
    ├── 1d4870daccab5ae7668d7d578b73899a84c930b5.nq.gz
    ├── 1e59660bdce000e4389b8e2a916a209072f4444d.nq.gz
    ├── 200f1a4d7d12d410fa894b0e397e5d2b66983b54.nq.gz
    ├── 20abfc1dac27058d1b1820382807cc8992c2687c.nq.gz
    ├── 20e848fd708615901d0c0350c11e1e62b839536c.nq.gz
    ├── 2103f0d3ac997ec8dabc6817671c6d63728fcbdd.nq.gz
    ├── 214ea65ea4fa8d941580991b32469a5d0a3941a7.nq.gz
    ├── 2169c4edb7f83e51dfb30aa7deff87b8e8164d11.nq.gz
    ├── 2236f616a9c2d3c4671d44f73dd2330976523965.nq.gz
    ├── 23c38aba468fc30ad6bdb4b7c80edcaf36f90866.nq.gz
    ├── 2411bded12fba6cedc565bccaaeeef5a00ddedb2.nq.gz
    ├── 26019b886d870b698bb1fda55359009e4a6fe225.nq.gz
    ├── 26203722730b618622e3156442c29f2fbcc2ce91.nq.gz
    ├── 264501fb1106d105389689153e02cefd614a6c52.nq.gz
    ├── 2658527d8d0fd2074dbaebe6c69d04674c099ce1.nq.gz
    ├── 266637579c269c54fa3f0d0f8cbc34cf8867fa69.nq.gz
    ├── 272beedd3f1d3ba46fdc6f92b24d8d72930f536c.nq.gz
    ├── 274f5b0cfd5c6e2ded802e838036cbf2b7decee3.nq.gz
    ├── 2761fa543362fdba7afba846672abb6512f4c0fd.nq.gz
    ├── 28172eb12166d1c3684c43e210ffa0f08b34cf4a.nq.gz
    ├── 2846dc5c6c886f30891f102e8b0533e6b8150bd0.nq.gz
    ├── 28bed44e6d66b48d358ed0f8a05c0bdae53c8a6d.nq.gz
    ├── 28cfb4b76e7f9b755869d37902b355365271ef18.nq.gz
    ├── 296b3cb3e1b3dd88b93a57fe0c26bdcc558fc725.nq.gz
    ├── 29b37736f505eddfce2bb636493550d826082bb1.nq.gz
    ├── 29ea9383d44f06e78b08663c07e48ccfea2dca33.nq.gz
    ├── 2a8ad996c3b609c56c934927ebb4b0f7bee7cd2f.nq.gz
    ├── 2bf4ea8836f1866ced5fc731efebb2a12dcfc225.nq.gz
    ├── 2c1f508df1d525a66d2997208ec3656ed49696b0.nq.gz
    ├── 2c5d8ec6055c036fb53da4d03ec99a08248062d8.nq.gz
    ├── 2d0c6d7512ad1f2b175587bff5a1625e29378761.nq.gz
    ├── 2ddc334b550009823ad275f675a20b719d855cd9.nq.gz
    ├── 2fd45b72eca274bf4aae6223c623403c0d2c3d16.nq.gz
    ├── 2fe4d9c0ce7f6fd8e4d78688f73f2430fef2ec12.nq.gz
    ├── 303b39aa7c97c7b07bdbc4adde99a45ba7b3ec36.nq.gz
    ├── 305dbf6c09f642d07d7caac66ac87ed5ea513b97.nq.gz
    ├── 30709b6b6e5d5377f0308e9db2a17c4c23e5aed3.nq.gz
    ├── 308f6fac695b5ae4cda8a0ef0b52bbdbe447ee22.nq.gz
    ├── 30e3f0595dec0415463bd1da64d3c25d3157b25a.nq.gz
    ├── 311b491403d5c4fbb131951bc2ae6719437597c4.nq.gz
    ├── 313cf5a03056c751be70d2f28318a71d949f53c8.nq.gz
    ├── 319291a2dbbe184e4378a3e90ce060cea31c48d5.nq.gz
    ├── 31c03f29fba73b52ce0d64632ee73e1e442f8d2a.nq.gz
    ├── 3269138546085411d4236a672999e2302c83badf.nq.gz
    ├── 328a8a93ec28158dd977f0cd943473639da28e3f.nq.gz
    ├── 3298998edc73f61b269bfed610a3c130b526cff9.nq.gz
    ├── 329c4662493045f2a505df38f5a1701ca1cdb55d.nq.gz
    ├── 32fa02ed78b8ab437f23ccd32d5c3510a9448a8b.nq.gz
    ├── 34642462b74e97eff27d0012534b0d6428750a92.nq.gz
    ├── 3475f6d4a32e7f1a00f35f4a455fb9c02146bc72.nq.gz
    ├── 34e0d418dfd5514c1d8c1541a29e69f7e46ed953.nq.gz
    ├── 359c5590c43d9394a5a747a317e8eaf3cef8880c.nq.gz
    ├── 35acda2fa1196aad98c2adf4378a7611dd713aa3.nq.gz
    ├── 3675e268c4e2e760dc0c8d8d6ad7aeda8dca76ab.nq.gz
    ├── 378f5986948d299245ccb243e4243de9a9363860.nq.gz
    ├── 37a6b947508fca1706f36977491e9af4e5341a55.nq.gz
    ├── 3949bee1fa1158ff26c42d2ef19ce4b8029b3d82.nq.gz
    ├── 397979ed1a63f547be5bdbe00f5659dc1dc8d61d.nq.gz
    ├── 3a8383f1f113b307febac668856dfdcca81d789c.nq.gz
    ├── 3b8dbb13e2122090903188068ab8b69ae5f767c1.nq.gz
    ├── 3ba782ff7ec14059a0029a65620b93a3741908b8.nq.gz
    ├── 3c49932c17c2c59b39da11ca08aa1f0ac4a19c4a.nq.gz
    ├── 3c71aee6b20237b3b5760a66b37ef132ce09c7c3.nq.gz
    ├── 3c789cabcc4566e797f56d79b88b6e199590469b.nq.gz
    ├── 3c8e25846ffef98d92988dd70a6de12425bdb4ca.nq.gz
    ├── 3db10c09d46f48a1a2a5937413a2ad58de2dd425.nq.gz
    ├── 3e3700884b4c761ee839e4fcf145038f8ac2d15a.nq.gz
    ├── 3e61bfc23cd630f56812842a5d31abf517b1eddb.nq.gz
    ├── 3e8da6a9438995cc35a902cc512b49c2a2d61ede.nq.gz
    ├── 3ef276c90400680d81dcfe74c671e75ea64a560e.nq.gz
    ├── 3f21694eb91ddbef5c11258948e7a0284ef6bedd.nq.gz
    ├── 3f9c8845c80b4517efc3c00ee0ff5e3b22b7b695.nq.gz
    ├── 3fa1977f8d90543ab171d58c3302735ad9ceb701.nq.gz
    ├── 3faff5bceb88968a2730bc93ef065857ecc2f681.nq.gz
    ├── 3fc2464014834974562e749a868b2a2813a64313.nq.gz
    ├── 40d7e6ec552013221942fd001000544114a273ee.nq.gz
    ├── 412bbb1d42801d617f48818eb2bc102338e61a12.nq.gz
    ├── 420aeaf65741cacc3e4a6b32800c7272ae377e63.nq.gz
    ├── 4271d5df7b0cc6a77621f2183a6a6cae68575aa3.nq.gz
    ├── 42792f356b12626b6c0138742b009ded095c5f67.nq.gz
    ├── 428670094d67cdac864821853de54a1b3ad83016.nq.gz
    ├── 42a55f39786bf5c73f8b1a8c18133244b4e78bf0.nq.gz
    ├── 42bcbe606cddef4c4629b739ff507d872c70b5b7.nq.gz
    ├── 43a7510a2d2c9f18640b2717600c7409e98356a2.nq.gz
    ├── 4434e38356949a0e6180acdee20568db984139c6.nq.gz
    ├── 4470256fe6ba576d41a33cb16b1d8ffc985b7255.nq.gz
    ├── 447987ecfedc25024dc71de6c0c2695442d79370.nq.gz
    ├── 448a7cc19f0e0f4c4c98bd353daa76ebb35f345c.nq.gz
    ├── 44f8b65f33e77f88b5fb12a2453078f5f2ea7428.nq.gz
    ├── 450fe1f85578301a52817c6023f42c46b1a2f782.nq.gz
    ├── 45b442587de1931082dcef5acf706f2000120d07.nq.gz
    ├── 462600d89d8ac0f1671e036ce9b45a88a18537b4.nq.gz
    ├── 46505f80d49adb6582bffe6ac88cd25806a69dd9.nq.gz
    ├── 4798595c7ae705b5f855b07815dfc54b4da7774b.nq.gz
    ├── 47fdc891b444e5e7d799999b3a3538940d0092e3.nq.gz
    ├── 48103c79374fbe0221694f1beb0afebce0e69061.nq.gz
    ├── 483ff5964f7c5088fdac4565c3dae148899ebf02.nq.gz
    ├── 48c6c8bf9a57fc4e515ad07ff5eb47e79f86ea01.nq.gz
    ├── 4a2b8a457073f6745f89008bf26ce50e7987cf09.nq.gz
    ├── 4a2b8c5d376a7e53cd6173fb0edba49f2354611c.nq.gz
    ├── 4a96849bd5cba89ee4268383b33979c385381122.nq.gz
    ├── 4b6d4eb8ee11ab2874883b3672422324dc2d241a.nq.gz
    ├── 4bd0dc27f5e969994c4e5b24fea287cb69b798c5.nq.gz
    ├── 4c05ebed19c18ad5f352d12d30c80601cc04af21.nq.gz
    ├── 4cfe1f1a7651f9f9bcdb9adfd931fd2ab9cb6b5b.nq.gz
    ├── 4deffa37b770aab5e814953e9dce97ee956b1bb7.nq.gz
    ├── 4e093fca97f01cf368ccfa143b485a54eb9d1a92.nq.gz
    ├── 4eee9ada4393a0a9a387d3588c93cf151340303f.nq.gz
    ├── 507a0c91ffee14d735a62c8109ae5f6a2734d8db.nq.gz
    ├── 50c209fb3b1e53d19f10add053ff04fdedfad654.nq.gz
    ├── 50c46cddb4ad95c1462751ab90bb9904b0d77bd9.nq.gz
    ├── 50fee9c95b06fae0845edcbb241b8a32f1bb7416.nq.gz
    ├── 51a2a19827b94de78c7e6aa5029721235cba097b.nq.gz
    ├── 52a859c102b6c468973a860c246acb692b3b0342.nq.gz
    ├── 52b2ec5f2e0b5ff55968df2b1a2c0074535a3ad5.nq.gz
    ├── 535ace214a32dd998c7729f1c399cf5c181eadb4.nq.gz
    ├── 54e7d06711fee9fb091cbee42cc6fede7ca5e385.nq.gz
    ├── 5591a43b54cf779431b8a398713a7d3a014662c4.nq.gz
    ├── 55f873177e3152ca9efb0126824297d675c444ee.nq.gz
    ├── 573561f8da53b2b77c0b330397a74ca8259a2b55.nq.gz
    ├── 575db718c58be41c2263b60adcc1c37f2d59b1aa.nq.gz
    ├── 57a359abf0809456717e3de3aa019ab925ec9052.nq.gz
    ├── 5831304701cb34320258e23f11c1e5846553a9e7.nq.gz
    ├── 58c6a75e067e9747bd11af3c07061ad4c72274c7.nq.gz
    ├── 591543f64be1c91b5c5d959bfdd4b6ed8b54b895.nq.gz
    ├── 59bd18519ec478c57619b0c34299f55cb5ab61af.nq.gz
    ├── 5aace781a131bd75fa99f1b07c91d33a29b94f82.nq.gz
    ├── 5c8cc22b9ba390238fd2cba4f54a8dff25bd5ff4.nq.gz
    ├── 5ce5de86a2c921a8277815dce731772b597a9c7d.nq.gz
    ├── 5cf3ee0c1efeef1d3238bd1a856b6ecb8edf6b34.nq.gz
    ├── 5d2b78f7f13a44945aacd414b585bb4d685b08fd.nq.gz
    ├── 5d4f24fe4746c2b4b4d50d72bd870e36a6f0d0a2.nq.gz
    ├── 5dae97bac3646c0a8b9919d72c2a64e73a1046e9.nq.gz
    ├── 5dde8080fbde59df67ac7681740ac7a8f2b0d38a.nq.gz
    ├── 5de2e9844c81b9ae11fee077bdb2abd1e69bd6d4.nq.gz
    ├── 5e2453171af2a1b709deabb78abae89aa40a75ef.nq.gz
    ├── 5f53e6a73a5775eb582279ed60b466727bbbbf5d.nq.gz
    ├── 5fd2941bf5887f5a7b60bcd3aaa172becbe55d5b.nq.gz
    ├── 60e8ef65356eb490151b2c4b6555a61460bc6989.nq.gz
    ├── 614e182f40d7fb74485133a713ae90cb8dd07dd1.nq.gz
    ├── 616d061b869fc8de8c176fe4d5dcaf08018abe01.nq.gz
    ├── 617db3465f588b02819d4fc832d51ec441ea6bce.nq.gz
    ├── 61ac980d4bb7bacda5ea19d3ab26dacc5a7f80e3.nq.gz
    ├── 63791e00577d98f8a8736de644d0bbb126b6dd88.nq.gz
    ├── 637ba1c9e50edfa3b98da503779290d9294765d0.nq.gz
    └── 64ceda4f92c66acefd496902639f43701fcabdd1.nq.gz

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

[allenai/molmospaces](https://github.com/allenai/molmospaces)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
