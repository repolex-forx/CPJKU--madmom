# Repolex Knowledge Graph of CPJKU/madmom

RDF knowledge graph data for [CPJKU/madmom](https://github.com/CPJKU/madmom), parsed by [repolex](https://repolex.ai).

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
rlex download CPJKU/madmom
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 27f032e8947204902c675e5e341a3faf5dc86dae
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 27f032e8947204902c675e5e341a3faf5dc86dae
│           └── chunk-001.nq.gz
└── blob
    ├── 00533978608a640d8575741e6fd35b715edcbe84.nq.gz
    ├── 011445982b037385c3ce01a963a17207bab92851.nq.gz
    ├── 011c2dac1ec0e9ddd1fa01bd7e218475317509e8.nq.gz
    ├── 01c5c4ba57be7c274c49c99365fe8e091bfa37f1.nq.gz
    ├── 020099b951d0c382b0bddbdce59afd64c54aa8ef.nq.gz
    ├── 02d3a7c31262acadfc09649369c7acfb1ed7bd30.nq.gz
    ├── 03debcec64aa13993e1366ff424d323efcd7f806.nq.gz
    ├── 04181b36f4d1d524d2c3104ba774c0ba16baf824.nq.gz
    ├── 046e39e3b39839e585e85653c62caa024a59b92f.nq.gz
    ├── 04eafc4cf4d87c0bd1ee9f5d7837999669c68cf2.nq.gz
    ├── 04f67d19cb26c3d0c87c0e488a7878f84f034ddb.nq.gz
    ├── 052fef7080cf613dc498007ce0c6d5bb32e98d14.nq.gz
    ├── 0533d7c77ee16931bb21a4a1000fe56439eb55b4.nq.gz
    ├── 06d21b8d50fa16af10e3dc57b4c700320d5e380d.nq.gz
    ├── 08581c70bf47db3025c03316f3375c8d3d7469df.nq.gz
    ├── 08a5dcb61fb99d7d318435d153985634756ad019.nq.gz
    ├── 091f38a51f256ef41de73c293d6d4b3025d20dcf.nq.gz
    ├── 0a55ae5235e74e0911c6913deb9eb65816ae1ce3.nq.gz
    ├── 0a6efedda697bbcd5768aa7b6ec2814607780ace.nq.gz
    ├── 0bfa1cbe66c026649c3cfa28014ccbe56a8bc03f.nq.gz
    ├── 0c63ec5613f43671128a6d89cc146f88c1567b01.nq.gz
    ├── 0d63112bf4a537ad25b83283c45a3a8a104d1298.nq.gz
    ├── 0d84cd0ebb7d73168066991187c5303cecc814e9.nq.gz
    ├── 0e41a14fec6798334a26357768b281e76afcf34b.nq.gz
    ├── 0f40d62eb22863ff9d4cd6d9de4cd856d850d3ae.nq.gz
    ├── 10221878c4cfae4d3a39a05e0d31ba69b341acc7.nq.gz
    ├── 11cf498632d04335682b5b1f4fd8a36110ab4df0.nq.gz
    ├── 135208545ee12cb4f2c5a7e3afbb1f6d5c3e2f0e.nq.gz
    ├── 14ffccd947b53f6344c25091ae65d130245e9352.nq.gz
    ├── 1598bedff0ca9d08b3c6c661f014d5d7e1db3309.nq.gz
    ├── 16034e523c9c0a960fe28606b0beb1fd3da75ed5.nq.gz
    ├── 16ebc0cad33b731261bb456ba96527ff40ce0fc7.nq.gz
    ├── 17678d6c9b268c5eb2abb0c9f59eea9f89389d11.nq.gz
    ├── 189f652bff00bec2ae2217c19e5a2f5aa65bb73c.nq.gz
    ├── 1906f81819bf1cdf5569d0c8bfb38aa1e860186a.nq.gz
    ├── 19efdfa863324b351a8eb74031ac16b09528bb90.nq.gz
    ├── 1ac91df702e41babe1efab386e82f3650f95ab23.nq.gz
    ├── 1dcc0a7f6188171ec02b5fc55167798fb767d498.nq.gz
    ├── 1e314a9ef502aae78db6b3fda4dafe45cadc6be4.nq.gz
    ├── 1ebdad164884de8a025eddcbf56df13f3ffc6767.nq.gz
    ├── 1f3ef9a78c08efd79e338d7302473535377db758.nq.gz
    ├── 1faaa125e51a81bd94e6dab110ef67a639e2b14e.nq.gz
    ├── 2046fb3d5d3ee8dd325d98c1187dd50b96760b61.nq.gz
    ├── 20accee7708f144317fdda6331c0af43d0c477c5.nq.gz
    ├── 20ae8b76cbe1c0fb8838d7356ddba3e75cd486b6.nq.gz
    ├── 21f1b833788ece9675252453fea7461b2d0bbbe2.nq.gz
    ├── 237c39b7dad1137bacda3ae536e8f20f4896315e.nq.gz
    ├── 25bd4fbefffb4dcb361b3e5e10305b627ae35b75.nq.gz
    ├── 276918b17f4011a87a2c2d04df0b5421f1203f77.nq.gz
    ├── 284d25744039f75305004e034d954fe6ad1f8ebc.nq.gz
    ├── 2cb4b08cc93880bd91502c08668d91617be8197c.nq.gz
    ├── 2ce07377fb7821979d26bca57a34d70bd0d5c154.nq.gz
    ├── 2de60c7d2609f39f9753f1cd4c2e4c11bd6590fc.nq.gz
    ├── 2eb18f7c03cad0f9caa7f2388c2a0d2067d37545.nq.gz
    ├── 2f24df2fc13c19dc8f780f16aaec669e3a706363.nq.gz
    ├── 2fb9856e8f8108aee444b45db990adbfbf738975.nq.gz
    ├── 3085a0f979564eb49c703db8c4ff6cbfad74d875.nq.gz
    ├── 3089aee102fd7ff6bde9a09a32e9491aa32d8072.nq.gz
    ├── 31ba64e4d6872efb606b74fc5b9896b81568672a.nq.gz
    ├── 33151f01029c0b2930cc189bcacb2c249e05bb8a.nq.gz
    ├── 355983a01b24b59416d23328b2ee3389f8a4b865.nq.gz
    ├── 36e1b24d476d4a342b367707c9f6999fd7b51b86.nq.gz
    ├── 381bb139115edde296ff3893e8387dc4c555de41.nq.gz
    ├── 384d0df4c4c15d9d75b77181114d27e72e075d5a.nq.gz
    ├── 390e49a5089a1598510ddb8044b53ba8fdb1ce82.nq.gz
    ├── 3922677ff07710efff59f02d96a7b1772b88c898.nq.gz
    ├── 3a5999ddc80faa0ce6a54389562c9f092b40bb03.nq.gz
    ├── 3b69efa315ea2d36be240a7a5d9479759b717c52.nq.gz
    ├── 3c04ba34573c75202553f0ed646973408e14744b.nq.gz
    ├── 3e365d4e36e9972dc91cf75aa3c81f575ec6fbd8.nq.gz
    ├── 3e394667ae447a971c9a87c64f4a84f5bfb64591.nq.gz
    ├── 3e4e43f9c6a295d105e29f80dc9b0fe674189329.nq.gz
    ├── 3e90e8dd0c140d3469f350d98a9def027034bb30.nq.gz
    ├── 3ee3be6705e91c8a29e0029b08232675efb6d415.nq.gz
    ├── 407f1aeaf6afebc818f71141abf492dfbed0e59d.nq.gz
    ├── 423acddbc2a772ab12167374e91c88b190ef6a18.nq.gz
    ├── 424899365eb6ebb909a88d1333292aeb10834bdd.nq.gz
    ├── 435f5b59af4451d695f782fa3c83fdbc0dd402f2.nq.gz
    ├── 44a1dc8af6dc0cc750dd36fc672a77e354eacd15.nq.gz
    ├── 4646638123bfab8cd05b4216e6d2ccc408893883.nq.gz
    ├── 47677bfec1c3f19f05a91f36c5d5d2afafc8eb4e.nq.gz
    ├── 47821c1b9381a14acfc94a9dcdbdcada63d1cde7.nq.gz
    ├── 49249c1556be294764a9abfea6d3b51e6c0b89ca.nq.gz
    ├── 4b53a63bb17ad4b24e110dbbba1c40d745644ae3.nq.gz
    ├── 4b6326a0405d06cd6bb2da5fdb857058c2e2ce14.nq.gz
    ├── 4cbc6934a6f96a268545f51dfeb64054bf222e2c.nq.gz
    ├── 52554f54b3999c56f7ac56a3aff98ccacb99a734.nq.gz
    ├── 52cf6f3a377a1c1498da47de4b3439c91baebaa9.nq.gz
    ├── 5541bd29f61bd43b1e0d924a537cfa883b0a400c.nq.gz
    ├── 5575738074038a3eaaa4d64ef87bf8470e526ab0.nq.gz
    ├── 5623a0420adcf8a5bdb59ad33899a0f0144bfa41.nq.gz
    ├── 5680607720d4c0c0d458c680e81335d2de1bc28a.nq.gz
    ├── 57d515da0d9c48666f8217d574f82d78ec5d8c58.nq.gz
    ├── 5945ff34a1d0628e855dd4b81ace76d4ca085c0d.nq.gz
    ├── 59b00fb26287268cd9a18678ffd91500e3c1a59b.nq.gz
    ├── 59ef07768d032729ed34bf477dd5d36e502d3b65.nq.gz
    ├── 5a812646416aa50c85c4721372e8e8533c44120f.nq.gz
    ├── 5c08ac171a91f8a1ab55c97210c95707eabddfda.nq.gz
    ├── 5c2b86383733cbc52060fa546fe73e2c39647c85.nq.gz
    ├── 5d24b50ccea7c1200fa31d2c7e0a44ab71217527.nq.gz
    ├── 5dc6bde6b8e0150153d4da846e47c71ecb7fb927.nq.gz
    ├── 5f9d1b94f798c677837b19e7e2166211f5ffd62b.nq.gz
    ├── 603baee40a73ccb0aa87339d7b0bb9dff907796c.nq.gz
    ├── 606df6d52f2d369dddd20c944d9f48a8ed651b34.nq.gz
    ├── 6549214f206b17105965388af51c4e27349275bd.nq.gz
    ├── 654e33d58904dfcb5a1a440044c7ec38ec101308.nq.gz
    ├── 6610fbb92aab1ab7f99a515d6a3ca30838f629c6.nq.gz
    ├── 66eeaca42e8d96aaffe9f6460afab1bf44431600.nq.gz
    ├── 67189573c247c5b4f30ea8a9ee5e93486774f413.nq.gz
    ├── 68924525b962ade3596f9d80c84d4e3aeb343069.nq.gz
    ├── 69209d2066efd58cce24b0d2a91c8fc21d06f8a3.nq.gz
    ├── 695b35c480a71052df972622169323c137af780d.nq.gz
    ├── 69838ead0851c478bb9de9a3e51c76dab9b6f6dc.nq.gz
    ├── 69a7cd033d9e2f1a3591734b2c1f1a523e40bf34.nq.gz
    ├── 6b8c22bbe22af583a9d39ec43582862e6546a1de.nq.gz
    ├── 6c76503f88d8bf5ebe8cecbc7877336017abc43f.nq.gz
    ├── 6cd072cc57a3abe464ab270e001041de227521fe.nq.gz
    ├── 6dffb854f010b060c3a88c88a80b030d4090a1bb.nq.gz
    ├── 6f4cca1c51860d7fd67fbb643c16263a9bea7d8d.nq.gz
    ├── 70df50d0dcf409808563d7b83a17324afe17b10f.nq.gz
    ├── 725dde9ff96a430b21cd8721c7ce7003c08fee0b.nq.gz
    ├── 72ced925eb276e118f90b67ca8fe9064e79a877f.nq.gz
    ├── 73a332f7728b1de7856465b15a3d93812dd9ab5c.nq.gz
    ├── 74effd449712172cdb924c3b4e2ad524c833607b.nq.gz
    ├── 75689de772b72266087b368eae9a5ecefbd6fa14.nq.gz
    ├── 7622ce87d683d23c27eaf9794c0300beb4260c0e.nq.gz
    ├── 773f3e00b561119e4baf85d802083dba25bd94c4.nq.gz
    ├── 77a3ab5b691de9d00912bf5bbf941cb091a36735.nq.gz
    ├── 7938ad4c0637f5459366a0d3707ca7f81f51f03d.nq.gz
    ├── 7a326776f04efd0d1e89dcfc363e3b8f38f16611.nq.gz
    ├── 7a6396a946c164b2900d00a22e0b0f1a78fc9985.nq.gz
    ├── 7a9268344f67f5009ccc7ef6e74f85059282375d.nq.gz
    ├── 7b1b089891327779548e54e5df3f98bd55b3d234.nq.gz
    ├── 7c3bc95426678bbf0ec0dfd87bd2f78383d674b6.nq.gz
    ├── 7cd0562093f605ee825c2dc97369b2b1f7f139d9.nq.gz
    ├── 7d77a1370f2aa36d5e0554d6b6e56258cc4d8daf.nq.gz
    ├── 7f33950271af15b20a55e5e8cd93a687fb14927b.nq.gz
    ├── 7f7ed25df38d79ab87afe75ce7b930d70efbc28a.nq.gz
    ├── 7ffee8f48395af2bc2acd72fbf37d1bb8d08a085.nq.gz
    ├── 80484d3c3a07e9b69d51cec6c8ff0d808a4ca222.nq.gz
    ├── 80cef9dba4195c272f8a0832f0b99fba2d1c26ed.nq.gz
    ├── 82881e2c7063741b357cf6ca5157df03ace24aa8.nq.gz
    ├── 8315e8c81a7868d9856220f07161414c1d412556.nq.gz
    ├── 84a2d7afba2faa785a1c8543d0f2fd62efbf8cab.nq.gz
    ├── 892443d25258d2d2cbad541dd4d9df5cbc20a1ec.nq.gz
    ├── 89ba088a891a80d749d451a83708b62b6b9d137f.nq.gz
    ├── 8a0dbdd1154a8bea4e496a3fcdc3a43a760a4a12.nq.gz
    ├── 8aa53e7f0c27e44ea8d609d596389e1b5e965cb3.nq.gz
    ├── 8aeba9ffa0a9cbcf5a1b1e5ef464f4a8d29f7b88.nq.gz
    ├── 8c7812b8a87f9d46bf1f27daa251b548e7dd0d33.nq.gz
    ├── 8cb94736f27b86e9d4818a82ec5a8ed8f9bc2718.nq.gz
    ├── 8f4daaa10747b21345ca6b5f9bf040c0686445ef.nq.gz
    ├── 922c9dc32f5bb1b1128b786446c57af4559da01f.nq.gz
    ├── 953a473289923a1c265e189b917ad2c696ff88a7.nq.gz
    ├── 9690f4e24f7f4e7837a836201a35ffbcc4f7ff57.nq.gz
    ├── 971235bd5ff064ce2083819fbc7f83909356e5b5.nq.gz
    ├── 97b7585e1b9f7a335610c2657d998f91d58747f7.nq.gz
    ├── 99a36ed82b06998678fddf3f1dc62a832751d07a.nq.gz
    ├── 9e446c6ab394711752ca9095d296320ed4c1218e.nq.gz
    ├── 9f90a790c75e3998edf191b82d1ea5a1283dc41b.nq.gz
    ├── a0e2f5ebac01a61770d7777d7fab74c6fa59919f.nq.gz
    ├── a154064f6978b15bc0029b2a1a7ce6902b4175af.nq.gz
    ├── a16b2046e7cd7013368ed6f034a5cffd88cc6db5.nq.gz
    ├── a212a9c1895a4376f877a04fe2a9f39d521af971.nq.gz
    ├── a6ed2591b5ceeb4b55c6fb4d78414ac89ca9cac9.nq.gz
    ├── a711ba43e396f3ad7957d658139c0215a4304438.nq.gz
    ├── ae39cdb9f5bb26b86660cf05c6be6ef4e191844d.nq.gz
    ├── ae9168cc4268532c0630b4a115ae462229ac9c45.nq.gz
    ├── afbca0cae4848916d99afc56fa06b02ae400d2f7.nq.gz
    ├── affffe234ed144c43c4875ecec79ea4de8cfa71d.nq.gz
    ├── b218434593ec6ad6ff612841d952c575bb1c7f14.nq.gz
    ├── b3a6bf7216d43fc865493946e595d1bdbeaa5e83.nq.gz
    ├── b459bcf69ed5dc2cb11d4cda7b30402f695fac36.nq.gz
    ├── b5a44d06d8572c9c053e1acb9d4ead6d3e32992f.nq.gz
    ├── b5f661bfa365cbe614bf89286b28c45dc318021c.nq.gz
    ├── b6489caacd379f16a53bd0eedf7240658114ec06.nq.gz
    ├── b66347b1a3584376b0a25f288eb3374d0ae7c3b3.nq.gz
    ├── b7b62fc554b730b0ebf25408d50f81715c449f90.nq.gz
    ├── b7d18632276ce8e34036cf86aecaba29cc452c99.nq.gz
    ├── b9451ac52327cd0b1dd23f19aa4b219768cb8f9f.nq.gz
    ├── b95ef8f647effe5f37c22b497ecb70fa8638a24d.nq.gz
    ├── b9c459152a341c8e9c1f099d1d7e14ba0494db1e.nq.gz
    ├── bd0b1aeaa3b2540da7493f9158fdd0ae09c0be03.nq.gz
    ├── bd44ef27b8b65dd35fe22463d9cc8456152595db.nq.gz
    ├── be68de61fd6f141b56c7646be6fd3ef678e6b4d3.nq.gz
    ├── bf2b953404dc1b15681403dea32855bba96158da.nq.gz
    ├── bfbdd5170ca05019ba461fcdaeda2d028cf4f493.nq.gz
    ├── c20e73f2859e41593025585ec29a1bd1f8fb0be3.nq.gz
    ├── c32d6606f623737fc5891cd3bcd22d1ecc4c53ac.nq.gz
    ├── c6c80c35552b2d184af4c5819574051b4d5be572.nq.gz
    ├── c6c828fc8e183b4dd0cff285e79ba4d95f623204.nq.gz
    ├── c79f2df02d5de2096a18de5d41127880bed76706.nq.gz
    ├── c7a128e9f781f2f73c63a8bb5c6a55412f4fc488.nq.gz
    ├── c822b0fc45f482ae3241838877b681044a83e0ab.nq.gz
    ├── c90729e1dadd3cebd0a08d107d0125fa4329851f.nq.gz
    ├── ca1900a49c25af1ccfecfc4bc49140a19a007610.nq.gz
    ├── cb8c323d82db8bca05ba72d28330f4eaa8367c3d.nq.gz
    └── cbe5fc148779677e657cdb094c760a53e2f3eaf8.nq.gz

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

[CPJKU/madmom](https://github.com/CPJKU/madmom)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
