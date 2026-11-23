# Repolex Knowledge Graph of huggingface/optimum-onnx

RDF knowledge graph data for [huggingface/optimum-onnx](https://github.com/huggingface/optimum-onnx), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/optimum-onnx
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 46533fb66570021f52a39d77112b703762fdaada
│   │   │   └── chunk-001.nq.gz
│   │   └── d2328e386a81b0970a458a7570a38b131414edc6
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── d2328e386a81b0970a458a7570a38b131414edc6.nq.gz
│   └── repolex
│       ├── 46533fb66570021f52a39d77112b703762fdaada
│       │   └── chunk-001.nq.gz
│       └── d2328e386a81b0970a458a7570a38b131414edc6
│           └── chunk-001.nq.gz
├── blob
│   ├── 002ca37f186ab4405878a6b76ace5e6e84e6457d.nq.gz
│   ├── 0182f581ed8ae13737ff7fdb24bfd0a526d6c48c.nq.gz
│   ├── 023f64a154bd60f2d16738de106f5f5faeb577e4.nq.gz
│   ├── 04f8b748a50eb49e35bba2fc436d380168a68c2c.nq.gz
│   ├── 059463f9cf0047d6c82b3da037bfac9d49a56233.nq.gz
│   ├── 08d860de758bec007f160a37c548a6773330ca31.nq.gz
│   ├── 0a2087dff7c5a135c0d4a278f573ace989bff1b8.nq.gz
│   ├── 0a2b7229e883babac8849d5ab6d12395469a645b.nq.gz
│   ├── 0b5aab6b0c29b7c62a193d80a6fcae1d617dc8bd.nq.gz
│   ├── 0bfd56a5ddaef6c7ca883a75daf9f16ca6bafb25.nq.gz
│   ├── 0d37d573e5ff5ebd93d08039196cd7a4339cc840.nq.gz
│   ├── 102e85f2b248f342c6dc1ccdebc540c963020080.nq.gz
│   ├── 104f591a3e56f3669e75b770f6eec1ad9c9bb4aa.nq.gz
│   ├── 117f088e47c65a1f98c2e04e02bcc41df8ac7388.nq.gz
│   ├── 18e4b6d44077d03d1a440418d4e714821019a647.nq.gz
│   ├── 199d26f58b3d23fe502e2a171a95568f36eb5d44.nq.gz
│   ├── 1c8e9b1c8e8f4343bc099f9e4a5999daaea7abd7.nq.gz
│   ├── 1da33042cc7182a58981508976bd23130836cea3.nq.gz
│   ├── 1e28eb66453e9c060e4cc2dd6d29c29d1645caf7.nq.gz
│   ├── 1f316a8d1ca1f140b91d127c7cd86ca039767b39.nq.gz
│   ├── 21fc14fa19a969076ca445e74b10f17a6ad45dbb.nq.gz
│   ├── 2252e555ec8e80ac8c92429545f81eef414f2fce.nq.gz
│   ├── 23fd7e0ef71a0e5a78feeb2b2d958f4076947a6f.nq.gz
│   ├── 260d260d6109bb84ffe0411dd289dac023ced613.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 2633c0c7191b88648cdd63d3fd061c736cbedcf1.nq.gz
│   ├── 26b70e904ac2f31687ccef0c9ffa80f57c500558.nq.gz
│   ├── 27351933886f05f558d34d03eac20dd20429d4d7.nq.gz
│   ├── 278c0e9254ddb04f7c10e9b27c5942c0242e307b.nq.gz
│   ├── 28723334fedd10ca0c2d4f15c7ea430169848db0.nq.gz
│   ├── 2a14db420040339319ceefb7eb16ba5e655cd416.nq.gz
│   ├── 2a16ed226448ee78a67cfa1357bf7f0c1dfc1e9e.nq.gz
│   ├── 2da6776e157fe7a22b0a1a03e2b6f94b48000443.nq.gz
│   ├── 2dd088f8ed91c79b8bbb97bd102f9d45efd9541a.nq.gz
│   ├── 2e055a0e4230c6559e65e4a4d53dc3803e5e8799.nq.gz
│   ├── 2e30851618ca8e58caf00369eb2357850804f597.nq.gz
│   ├── 2f6181878720ba83fa8ff351bbd3ed67b1536d8e.nq.gz
│   ├── 308c1fd91c21b7d46e992178584196bae1d5cab3.nq.gz
│   ├── 30fba3c1a37a8eb0e355df4855d6b83bdebdb10c.nq.gz
│   ├── 3212f6bfee4c0406b5e1966442f68066f4d2d334.nq.gz
│   ├── 3438b9efd3867611ecd326f597bf3d2ff0d66ee0.nq.gz
│   ├── 34de9473b16f72f9193c04db39f08805cb184014.nq.gz
│   ├── 351803a36334f9eb7e919a01840bcf025634a92e.nq.gz
│   ├── 35bbab7da1a5e2c6f29be57d9859d2adefeae5d1.nq.gz
│   ├── 35e7094840358e68274fd184f44fc7c854addb67.nq.gz
│   ├── 36c07a0f67a3651575eb4bc070832dc2decb40c9.nq.gz
│   ├── 3a7dce2b59fdc96ee49945bab4ef2b168f0474bd.nq.gz
│   ├── 3c45a991611160825352ecd6cbd71865c6c27121.nq.gz
│   ├── 3df59199124348adee9166063b91d97440167814.nq.gz
│   ├── 3e01a2d60a517ad1cbea7ffe8006cf7a1377628f.nq.gz
│   ├── 3f8d7231555b356cfd1e5c3313965c7dbb141024.nq.gz
│   ├── 4135baee7866a41f94143771a5b3280b3caaca77.nq.gz
│   ├── 421bb995a948c44da1380d12c934741faca97a31.nq.gz
│   ├── 4282567508799e604906fdfbe9f59e67fcb83b52.nq.gz
│   ├── 432d6eae42004fc4f14b1dd00a28eecc67b39e97.nq.gz
│   ├── 440dc99804a80deabcf4fa0a95cd0451cfa73373.nq.gz
│   ├── 49b73c15c063da245ecc843a4d46f8b73b21f64b.nq.gz
│   ├── 4f060cd6089d10af2bfcba89106804a176534f1e.nq.gz
│   ├── 528b2c05a9cc368f7aaaf0c8d066c0a42e0d7521.nq.gz
│   ├── 540b3cbe2dd0133b35a544446a975f1d4f6c3507.nq.gz
│   ├── 5427e8dec350cb6908ef3149601e8304aa2d172e.nq.gz
│   ├── 54a0fd8abc200aa8200022f26955807f89d358a0.nq.gz
│   ├── 567fd0247711f8e8b0b0258329178ea9d19b389f.nq.gz
│   ├── 56d3c5a4db5a366f032cba17e389f07707ed7486.nq.gz
│   ├── 57942fd6540556010825deddd8d49ac9445a3426.nq.gz
│   ├── 579f2a4aabc96b14b3ee20d40ef68b2b87e667bb.nq.gz
│   ├── 58df8fff2e601b7702fee048fe5d378f1f3aeeac.nq.gz
│   ├── 5c39a6d52231fe11baaf9ab4faa75e2bc2ac8d7e.nq.gz
│   ├── 5dae9857976275bcbe908eca2be2c121dc874b6d.nq.gz
│   ├── 5dc6808d5d7d2921d583d39ac6bc32144428e7b1.nq.gz
│   ├── 626ff4178333b12c55f706272ff8e719ce58c937.nq.gz
│   ├── 673a18479a8f7e86bfcb9e93efe3195ea264cac0.nq.gz
│   ├── 698a51e13437db33cbd557711e5d4ebc92355446.nq.gz
│   ├── 69de8a7bafc4908b250a73806fdf2846b7c2768c.nq.gz
│   ├── 6b34aa1564a6beabed7ce3f278f25ae666fd3ec2.nq.gz
│   ├── 6e3f1788d5b389442a087a73e0416528b0b2e2df.nq.gz
│   ├── 713f3bfa8aa65dfcd0a66e559165fecbba76b9fb.nq.gz
│   ├── 72c0cd9c1b1c5384728ecc77e7e7bf51d019309e.nq.gz
│   ├── 73751b29df15ef0f71914c9274cbd9fc7325e1b1.nq.gz
│   ├── 75959418550ce82294f8ed81bba186ad33f9ba66.nq.gz
│   ├── 76285f83ce2d7c7f29f8b2ec37d563689c841cd4.nq.gz
│   ├── 765d472a57bfdf2a735123450dac7ea5f00847a5.nq.gz
│   ├── 7b004e51045ae62398e7e48ebb556ab5c9a7d319.nq.gz
│   ├── 7c20c13f154b66b7923def2d5de081edaa924bc5.nq.gz
│   ├── 7c4d52f6e5ffacf038ac5a1869653060843409cc.nq.gz
│   ├── 7cb029892dc9dbaa3448f1bc60fd4fda80115ae5.nq.gz
│   ├── 7cff6b42cbf0152adb6c1a3a9ccc20c370cc43a1.nq.gz
│   ├── 7ee2547229fe7a1d170daddc11ffb814a87f9c5b.nq.gz
│   ├── 7f7afb98ede245308915d8e4cb76c1c407a4f3fa.nq.gz
│   ├── 7f7c9275e75b8e485321c8867d6950e483e5f8cf.nq.gz
│   ├── 7ff81004134e831c98e9845f98fb8c2b7e8a9cc9.nq.gz
│   ├── 80b81afbcf686a24e36f3671003fa1f8af199868.nq.gz
│   ├── 8345ca8e4d09b892b562eee09915c745d4cf4370.nq.gz
│   ├── 839fd1170804d9da8908d816a74e168d38f22da1.nq.gz
│   ├── 83c8790daf01b22370fa42a9ce3c68ab4f368e9d.nq.gz
│   ├── 85648f267bee8960e2546cb8672cf4f2914a3c5c.nq.gz
│   ├── 85da4deeeec1e02c52765efea0b1fa23c2460545.nq.gz
│   ├── 8c29eabe64b3c591c5ffcf5529a1c9aa75ee2831.nq.gz
│   ├── 8cc90df8c5d6e6a52afdd2b95299a515bb9e76c1.nq.gz
│   ├── 8ffe16f3d6427f768f21d2bba383c2c206441728.nq.gz
│   ├── 95fd3335171f1d53ced2de4024350f6bdfd9b9a7.nq.gz
│   ├── 97816fc9897bcfeaa39a6d57e54ced1bdefeeb5c.nq.gz
│   ├── 980c61d9bd979c1a8adec487cd328c7c81c768fc.nq.gz
│   ├── 9cadcd6a2c312846f32129e59afcf64f1c01a8db.nq.gz
│   ├── a1ecf6cf24fe241907d4a2bf9fbba9a635496875.nq.gz
│   ├── a4228bcb5e737c15280cdf1373f08edbbd1e1281.nq.gz
│   ├── a52652e21471223be25ba75c3b89234f1f64cb2e.nq.gz
│   ├── a55605060e182b2a902b2990ea3726d6d653260e.nq.gz
│   ├── a64ff805fa5207691fa723452e55b4ab16063c5c.nq.gz
│   ├── a993575efac18c10d6cf848a900f26076f5f3b13.nq.gz
│   ├── a996bac53ef37c4713051a77c3928f968c5b7fff.nq.gz
│   ├── aadc0e9088f8684bceddeacfc16e972fdb79195d.nq.gz
│   ├── ad05729805accca813a8bc8314e02a9334909cb4.nq.gz
│   ├── ae0ee89eda398365b3c07e349386644bf4c1f176.nq.gz
│   ├── ae5ed8fb8a890147c19e9dd4f89f994deb9044f5.nq.gz
│   ├── b04ffbd79c3201939f193b4435d3d215f7d249d3.nq.gz
│   ├── b20c1ff19e33d4e2fa55811d672a46704b570141.nq.gz
│   ├── b21aa92da68bb39b6e4e8b5c6c167bddb94fdb20.nq.gz
│   ├── b2a9a2216f32bc6cde7f5353c0982569ea4617b0.nq.gz
│   ├── b2fd25569f7774717f9a21d8faa53d7b60ae9d57.nq.gz
│   ├── b40e1e56a1adddcd6ddf13503efcd61337cb7e3a.nq.gz
│   ├── b4b7e84dd42cfabbd51fdf17ccde5c1ced78064d.nq.gz
│   ├── b4b9e01629b178fb5bf5470b040446afa730d528.nq.gz
│   ├── b6a67be625e8a840e0fee82615baca754723810f.nq.gz
│   ├── b959e2c3eb25736ce2a7a503b5709cea3d5e6d4f.nq.gz
│   ├── bcab6edc05471d269d2979c9325feed7b24da1c5.nq.gz
│   ├── bdc517d7bb1eb9ebfb786901744f04cc37bc3800.nq.gz
│   ├── be3e515367a88cc3bca29642203b0321782e0053.nq.gz
│   ├── be68d8dc2accaaa896d1f386b3f812e50555dc83.nq.gz
│   ├── bfb93a29847e8c6affad2966a587da3d18a46269.nq.gz
│   ├── c07e3a532eb846c8609ac35d636e716c834ac80d.nq.gz
│   ├── c3263bf224d86629c03d62b9161ebd7fe41ceabc.nq.gz
│   ├── c4ac1c39c8b5ad20c8849741e52b3c9d947562e7.nq.gz
│   ├── c716b38adbe7cfebcfd29293816d247c56f4434b.nq.gz
│   ├── c7de5970d48c21defc92203bbe6a9321d40cf5ae.nq.gz
│   ├── c88cdeed1d6705655f9a1a9e993aac978fbfd1b8.nq.gz
│   ├── c9e219325366fba4509f9e0d3910e0672d6de935.nq.gz
│   ├── d080226dc50baf6c7bd7067e2b6091ca37fbe852.nq.gz
│   ├── d40f970f70ab9508240b53a3f27387a515ebf16a.nq.gz
│   ├── d86a378d05728579cf5b22422cf19dbd7d4e00cc.nq.gz
│   ├── d9bbbb9b4110e2895e1787034991e744c51586de.nq.gz
│   ├── dc9f28852dae1cc98970bc9afc3fdbac315a3223.nq.gz
│   ├── dcdffb75abbfbf132c2c82c348f7adb6f1e5eaa1.nq.gz
│   ├── dd768c2a68e7eda9afade2a76fdbd0a827f44b5e.nq.gz
│   ├── dde4d327ee571f120219956980336a97bfca0742.nq.gz
│   ├── de6963966ec82424ac69c478c25e0d7c448682d8.nq.gz
│   ├── df3c238dd5c50265e4e8a7fc35274a4743d3c8bf.nq.gz
│   ├── e11ebd16e63ca99a3681e18daf7f4aca503af11c.nq.gz
│   ├── e1e710f46e01a4a8fac491e99fd274f1342fbed4.nq.gz
│   ├── e2a62c0c0bba54c95fc810cc509e04c1985606e2.nq.gz
│   ├── e404d3db31d506786789450cde5bc9fe9d1d1839.nq.gz
│   ├── e42532873a8f9da55dbf6d71a606408d4af4600c.nq.gz
│   ├── ecb2286c3150e76c41a2fe691f7a2e1fbd1e872e.nq.gz
│   ├── eccc1de5c8657eddfeb5553008c0bb07814da037.nq.gz
│   ├── ed55a1eca0aba2f1c4c26f7b81d871bddefaba51.nq.gz
│   ├── efdf75b49af7954bae4171e32dcb0b5cc13d75d8.nq.gz
│   ├── f00c2907e28aa4b97632b191ff04f85902b7fd7e.nq.gz
│   ├── f17ebca51f042beafca5f7676ec526db2f022283.nq.gz
│   ├── f2d181d11e05a75ac4a4b9cad5c5fe86b7982556.nq.gz
│   ├── f3a8eac3dec5ffb29a1102b44a8d32caea726373.nq.gz
│   ├── f429aba994c0842b1145869426005f32708b3c47.nq.gz
│   ├── f51b2e169081feeaffdddf530bd5b3f3a284b454.nq.gz
│   ├── f6105d3dc314afada150f48681dd7330e910011b.nq.gz
│   ├── f6bb8103760cbcae6f736f347f9b5cb42134e612.nq.gz
│   ├── f80e8625606e426cd6682b1b8969896cdd620d30.nq.gz
│   ├── f8f7edd5438ab469def9735dcf3d4449a9cc1f14.nq.gz
│   ├── fb39c240403e4b40a06f32abc6b63da80ec40818.nq.gz
│   ├── fbe5b15f0a71b8563bfb11b68152a4676d4bf2e7.nq.gz
│   ├── fc085a62c0fd2de6b1ad8b7a7e9c6743e30e0307.nq.gz
│   ├── fd4a862071a7349efbda9b7b3303868734044a17.nq.gz
│   ├── ff665c3bfbec1a5b5d80ac6294dc772afbd0b378.nq.gz
│   └── ffae49fc520032132e7a3cd58330b00ece683055.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── d2328e386a81b0970a458a7570a38b131414edc6.nq.gz
├── filetree
│   ├── 46533fb66570021f52a39d77112b703762fdaada.nq.gz
│   └── d2328e386a81b0970a458a7570a38b131414edc6.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

17 directories, 185 files
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

[huggingface/optimum-onnx](https://github.com/huggingface/optimum-onnx)

---
*Parsed on 2026-11-23 by [repolex](https://repolex.ai)*
