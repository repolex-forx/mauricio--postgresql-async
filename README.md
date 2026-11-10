# Repolex Knowledge Graph of mauricio/postgresql-async

RDF knowledge graph data for [mauricio/postgresql-async](https://github.com/mauricio/postgresql-async), parsed by [repolex](https://repolex.ai).

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
rlex download mauricio/postgresql-async
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5716ac43818b6be0dc4fcc2b2655dde3411cdbe0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5716ac43818b6be0dc4fcc2b2655dde3411cdbe0
│           └── chunk-001.nq.gz
└── blob
    ├── 00cc712b5b4b7d7fa33c5421627c7c32d57b252a.nq.gz
    ├── 0184b2c44fd03bde453432e0a2ceecc29b71c681.nq.gz
    ├── 03703f21e4a8d19e8bedfe952f6286e4548f3457.nq.gz
    ├── 03c35fda755f58201612f7c9308a00b171e2c336.nq.gz
    ├── 043ea1180811e47874e1599cacbc34e620bfcafa.nq.gz
    ├── 04c9edb417ce1d93d39d53af73a34600008a7686.nq.gz
    ├── 054cf485a5d986f4371b166db4b9dce8320fec07.nq.gz
    ├── 05feca1218980870b514069da7a1f5673762d1a3.nq.gz
    ├── 068ab389e038c33b413706daa03487c59a14dec2.nq.gz
    ├── 06b3b549c234303b53d22c596ad1cbc3ba057f9f.nq.gz
    ├── 088da761efaa313e468686f5e62b8194d9d1ea5b.nq.gz
    ├── 08fb0d9f9f71399eefd704abe0d4573c289e018c.nq.gz
    ├── 0988b05288aed69c9f527636969aebd5dc6c2a93.nq.gz
    ├── 09bbec4f16ab7deca602b18bfee731920b7e39d6.nq.gz
    ├── 09d2efe237e9a6b7925b879939ac59534727568b.nq.gz
    ├── 09ff916a4e628c984fff8e6d59fc242c655fd6cb.nq.gz
    ├── 0a5c165e6f7c1ada4e2ce268be1d41ce27f43ee6.nq.gz
    ├── 0ac567f2e2f95b88c4f5dc145b509c441bbc4328.nq.gz
    ├── 0b5ca28905e2a245cb1c9415ce2ab6a3c647c7c9.nq.gz
    ├── 0c4e7972419e85bd579769514a79360f164e7a31.nq.gz
    ├── 0c6d85b428e62245313f77f0a8ca0e3ba019fa4f.nq.gz
    ├── 0d2799df434261133b46522d896e42200632ac56.nq.gz
    ├── 0e050477d0cf615707c046336eea15e65edd1734.nq.gz
    ├── 0e2264293c761d69702e47315aa10bac1ad6e874.nq.gz
    ├── 0e9ec63205859a32e1709054c26d6503d796f334.nq.gz
    ├── 0f64866e1f0d3b1b7996d8316ce9165ecf30f495.nq.gz
    ├── 0fdc790a41a31d416204e93f94ade78c8f409da0.nq.gz
    ├── 1086af78b2f06739a6304f504d5f95c6dfd167e0.nq.gz
    ├── 10c25df729a895dda2c4087ea4e1092b9398a7a7.nq.gz
    ├── 110a2ba7b7e08c491b145e38ffaa7bce2fec2f14.nq.gz
    ├── 119878355490c8f55c4292181fd3e77ad1f2ff8e.nq.gz
    ├── 13e2e8fd9283fc5ac40aaa645048b65177099ed9.nq.gz
    ├── 145c5422ea32159a06cc2e2fe712716e1d8b780e.nq.gz
    ├── 14dfdc6d49ff9f50e5df1122580676c6af0f4eba.nq.gz
    ├── 1531e5414471994c8ceb428133f5f8d876fea398.nq.gz
    ├── 15bab08574f13f4043f79187bdaa059d8987640c.nq.gz
    ├── 173bc4ba3e2840bb2051a1a596c7085395e6ae91.nq.gz
    ├── 176c3f4dc1968e67615cff02e6f4bbcc858d314d.nq.gz
    ├── 18c2adb5b76d77302c35056067337c5b207be021.nq.gz
    ├── 1975edcbbe8b88991a1c9238d10718eccef97ec6.nq.gz
    ├── 199c0d1b0423db32d01dc543444b5f98f89b51aa.nq.gz
    ├── 1a2a9fbd666cdad0e2afbbe0b89158c33670a336.nq.gz
    ├── 1b41f44701b5bbbbf015f0a9540dd52f459f3c65.nq.gz
    ├── 1b4add0726e4a2abf287fff436b793538aa80811.nq.gz
    ├── 1b58bdcce1875a5dbdcbee32315cd4c90289cf79.nq.gz
    ├── 1cd73dce42622a8831a0b1ea0b2acdcce9877e75.nq.gz
    ├── 1d167e5f09c2fc376b2a2b4c1a46bcec95aa708c.nq.gz
    ├── 1d9913247ac94a0d1b6ef4670db3d0295b71c246.nq.gz
    ├── 1dfa615f2631898d8e7d37837ca929c98a8cb22a.nq.gz
    ├── 1f2e8bf800c9855c45c45f82d0643e8ae3a6cde2.nq.gz
    ├── 1fa5b9a259d6bb3e06d9d3108f66ccb18f7edcbd.nq.gz
    ├── 206fd2d33f6043c479b5a32d659aa9f731dab20c.nq.gz
    ├── 2074bbd68ddab48a61903cc4c97e95961f30624d.nq.gz
    ├── 219916844f71967b3155a33e98b022de28db185d.nq.gz
    ├── 228c5e659a09e7a7a3c953ce653d0c6deeff4fce.nq.gz
    ├── 22c6cee5b42751cf8ccd81a9b4dca828db740d16.nq.gz
    ├── 246b29ab8f867d321feb8664e49d6cfd6aa38d5a.nq.gz
    ├── 2560b8ead46294615e986d7fb6cbaf7ff4d58827.nq.gz
    ├── 258f23ee3a6ed32dea0f22801e77b9f6c7bbcc97.nq.gz
    ├── 25d002960cd098ac11513d3d7c6e73df3d405d10.nq.gz
    ├── 260aaa7c0e333aee059011a0bfe658d79e4c6a2b.nq.gz
    ├── 260f22a48f5704f19e370a1f3e276708b698e949.nq.gz
    ├── 2659d3725e7ac58b1c29aac74f4f2e4f5a9c4ff2.nq.gz
    ├── 273e76af42f23245175ae3b9d23c2b50c99f703f.nq.gz
    ├── 27aa977759feee05ef882c3e0387a3b2bd921d4c.nq.gz
    ├── 2839564ae5628300e28c9e74e6a45b1d09b1bea8.nq.gz
    ├── 29b1953fd45695e4c0502f9a2724b80c82a2a9fa.nq.gz
    ├── 2a2a1b1f4ca501db61e4aece002cbf96b86bbe4e.nq.gz
    ├── 2a3add4b7bef6b6f26ffa4b46ea9d2f714c4196b.nq.gz
    ├── 2a5d08453b558f3e23d75e964ca73777e1453aee.nq.gz
    ├── 2ae1e7a4580a7750965efca857601f1821fd429c.nq.gz
    ├── 2b6bfe8a89e6f83c8d3ee944e130afc359670aee.nq.gz
    ├── 2d66e792f057642b7d87d7648a58a64a6cad35bb.nq.gz
    ├── 2e38adbbe706377f721194c098d2493f84a840ad.nq.gz
    ├── 2f40154cb8e9fe11be1dc40bff78e78da50b7d14.nq.gz
    ├── 2f689b07297b37c67092b17a7de431462c528721.nq.gz
    ├── 30195a11ea66f9fa64f9f93dd00170bed1b7c3f9.nq.gz
    ├── 318d71c17c8a036e703fb9f73f5629190c44df91.nq.gz
    ├── 31ef5f45dcd3aa07706156ade393560378224f04.nq.gz
    ├── 32280db28ecf6ec2f7265f7c5cc24885933f27e8.nq.gz
    ├── 328e872fa33ff5f3fba6e568012c8d83ab825cf2.nq.gz
    ├── 329709adaffd6932deb573af0a0a751cbcff4222.nq.gz
    ├── 33472753bf1ae02686eccfe7851a83e41c89dfe3.nq.gz
    ├── 35d09a1fef771d3225abc3ae7139520500111031.nq.gz
    ├── 37e9e57520ea1b6daeecc6efb832d4511591ee18.nq.gz
    ├── 385eb011ab89779a5b24fcbf4d942de66fac3629.nq.gz
    ├── 3883c1999ccf1de612b868aa67879c10b85b0195.nq.gz
    ├── 3a1522863ff6fce082a3de6f6471acd84975b013.nq.gz
    ├── 3a515a03b610bd7ae4638dc8fa024d98cce88c21.nq.gz
    ├── 3a8f4c5b95bf7a6672561731f364dc19aa8b52b5.nq.gz
    ├── 3b2181e7b7cf49916d111384e6011751b30e8c5b.nq.gz
    ├── 3b540e8077f1da12684ca08a12a1e99358d376cc.nq.gz
    ├── 3b56ecc0bb0852f06fdb883c4e107d6948667023.nq.gz
    ├── 3b9a6d2679dc7467537735b99b64ec2ec3b96574.nq.gz
    ├── 3c9d657985a7bbb8191317d07d10df087d8146d5.nq.gz
    ├── 3ddb151830868b6881e3476edb9dc9f48e691a4f.nq.gz
    ├── 3e2b8b1d1e4c0ca13264f3bff87f464a18fa404a.nq.gz
    ├── 3e334f1ad270abd869a86fcf9c0e5aebd23d4544.nq.gz
    ├── 3e4345a8ea9095a8593e817e81271c5533a7e54d.nq.gz
    ├── 3f25ad76d5a1cefb99027e3622648397345b0a3f.nq.gz
    ├── 3f2788fccc8e60ee6583d7986cf620edaf548078.nq.gz
    ├── 3f9bdef2e2c231b37dcc6cd448ad66445e1dd607.nq.gz
    ├── 41263bb1e89fc9641785d686caef1f398bfee272.nq.gz
    ├── 41a347cfb88e241a1eebe71edf6808bb09fb8ec6.nq.gz
    ├── 427dde172c789744408734c43270c99a9e8e2029.nq.gz
    ├── 438b0daf4cc10602639db5ad1cb419646e69ab54.nq.gz
    ├── 4446e06d25c53ca6ed076d3df7eb077fe426c1dc.nq.gz
    ├── 451d77cf194cb0e906b6108433e150c55bffed29.nq.gz
    ├── 4578a11896373606806b5c6837216d41e68e8a83.nq.gz
    ├── 457c98696c96d58644cf184b79cc2e255eb0fdb2.nq.gz
    ├── 470700c4e1beea3bce246a0aac52c0ff49a3083c.nq.gz
    ├── 4799c8dad56a4d48746213d4d94375e6ce2d7443.nq.gz
    ├── 488af40a6384a55ab2a1fdf90f1bf8eacf95273b.nq.gz
    ├── 48b1f6c67053d1e29981028dcf34796c8d98125f.nq.gz
    ├── 48b39cece0d6afbb5add5805c0eaf020c6c5e6ea.nq.gz
    ├── 491e2403e9929c170c5fb82ab6903580dc76fa56.nq.gz
    ├── 4b1f2df90f89724fbca6844656d02503dfcb973d.nq.gz
    ├── 4bf334538ad75c791c121053bcd5db56bbcfe215.nq.gz
    ├── 4cc36c275ace94b3dd5809f7a7d8f358a19235f6.nq.gz
    ├── 4e249387ff09b82883965c204f9e607fc145d79f.nq.gz
    ├── 4f0716b9b25fff20191550786c000c40c40ad689.nq.gz
    ├── 4feac705768daf67f01fd3a05b8e6be591ad1352.nq.gz
    ├── 50940cf6afa32c0712e6d24c0c75ecd72d1319a7.nq.gz
    ├── 50b7e839643fa4f129b47e1cf03c680e3e7afd47.nq.gz
    ├── 50cf1073c1288af58c3290b8b8c50a486a0cd516.nq.gz
    ├── 51d58fb01d6a13dae3013e6cdb4145d6df44b6a8.nq.gz
    ├── 520c931cd7afa3ad506086706cc3b4754f2241be.nq.gz
    ├── 52e7481f62dba058a088a11eb01c7e4fab08364e.nq.gz
    ├── 5391588cde71629137a8762ee343d7ee1cfbd795.nq.gz
    ├── 53c2f2ddb730d37825b5387de4f907fba109ed2d.nq.gz
    ├── 56098c3c22bd82cfa72cdf71a7e94ea9fedd3642.nq.gz
    ├── 5670000901578a272c82a88a26a661fec2ac76b3.nq.gz
    ├── 56c05a15983c2744b7646bbe682318091ed41fa0.nq.gz
    ├── 56f71931720d978b6afe55e07ea645f30e6077a0.nq.gz
    ├── 576773dbe9f15354f4799eb18675c73b627973b1.nq.gz
    ├── 58500c1f7aec2dfbabce2af137472af9b182aa73.nq.gz
    ├── 5a0f7a4bc6bd5071b10cf4c7f6f6bf79592bd5ef.nq.gz
    ├── 5a9ea9141e559de2e5c9c4ad8c50b2ea3973529d.nq.gz
    ├── 5b4a47a7dd1aa95a24ef02c91f4492098a6b546a.nq.gz
    ├── 5b74d27f48cb2637469aa98d2578c62beabb48c0.nq.gz
    ├── 5d321170fd0817753b7d3f98bbd2ba8a3a0c7f41.nq.gz
    ├── 5e5500faa2e1f277ec67c980451a35543ce65358.nq.gz
    ├── 5f210f7291f7ad1f0e116a794877682d8c8d62d5.nq.gz
    ├── 5f31d67718d1fd4a34f5935947267e8e60e6d292.nq.gz
    ├── 5f3af8ab8b8099d471763f1eb1dbbaa491d965a6.nq.gz
    ├── 61be30aca9cd21000f34474d1484a52d78701032.nq.gz
    ├── 6246dae7bb39c373bae97055db402bdc1190b160.nq.gz
    ├── 62b6256019cb33e55737173e6dd873409a1d73da.nq.gz
    ├── 65710db5c6614509141e126f7db953402f1ead5b.nq.gz
    ├── 6582743232767e985aa5e86124ac3e3fd86b760a.nq.gz
    ├── 660c1411f4adf2f5a270b859e57f760a7e0e27dc.nq.gz
    ├── 67ad7d31b0c96f7d39ebd7c1f3fa105de72d66bb.nq.gz
    ├── 68e68eeb24eb6f4e6097c757420350f8822a43fd.nq.gz
    ├── 6935259e393dff39de5d101b406a639db9602919.nq.gz
    ├── 693d1e198b4f71574f2d54f3a578e13676ab8480.nq.gz
    ├── 698534f5222992e5298ca00f6649bedfab5fecfb.nq.gz
    ├── 6af7d7eaafae06845de3df04704444c40e1345d4.nq.gz
    ├── 6b6d70e0484343475231b39e87419c7c82d345b7.nq.gz
    ├── 6c7c13135ab1f64d1797e068bf3af4992bd8e59b.nq.gz
    ├── 6cae6f684963cf9c39d2cbcbef078232a3dd7e89.nq.gz
    ├── 6cb67ad90f0353ed54396b6d2e524a480b826981.nq.gz
    ├── 6d7a0e7c32cea005b106b255f6a711cddb00a7c5.nq.gz
    ├── 70357bac2ded35040a5496072f75f5a15250b299.nq.gz
    ├── 70836d42cce6708d1587fba37f5fd95a5919d599.nq.gz
    ├── 70fc3f0147ac997916bf9d22c42f7fb346fa205d.nq.gz
    ├── 72a4e4e128430abfdab9966cb438bd6f37480b8e.nq.gz
    ├── 733cc5d18f191b77d6994c7e43e47cee482ab516.nq.gz
    ├── 75166e80974c1b7328ce208faf40675002025269.nq.gz
    ├── 75da1ebd04dacaf763d5682a4d20b535c606b56f.nq.gz
    ├── 7702e907d09b509139dc12d7f3c3f6ce8be11e25.nq.gz
    ├── 77071746e641c52a1f466208e5c4ad65a78fb659.nq.gz
    ├── 772b69d3dcaf16129a8943cc5bba7d72fec2e6a3.nq.gz
    ├── 78d360469908b6c603814c7c4770882dc6d6fbb1.nq.gz
    ├── 78ed8b4b48a0f04b876147ab44ab0df3a0090dae.nq.gz
    ├── 792aff77c994b6c56d835cc474867e2645e48f97.nq.gz
    ├── 7959789c7341b70a7ac5c305b0288bff2971467d.nq.gz
    ├── 798f923134c989af36ef8dd3c26b7007b42a39ad.nq.gz
    ├── 79f4b057be998ee16c70bef000aa1bec9820cd54.nq.gz
    ├── 7a9054ee277881907c2095da4a416e122369f52f.nq.gz
    ├── 7aa9a4d39bebf3a9efc84156c17fab2387128b62.nq.gz
    ├── 7c6c426d0b78879d70a14991a4e84a4a007a8f11.nq.gz
    ├── 7c8bfdc44155b164e7964db81522ed8914997fcf.nq.gz
    ├── 7e02c17c91a850338924368365c887fa24e56459.nq.gz
    ├── 809590836bfe18a7af59ac89e134937cd6b4d11c.nq.gz
    ├── 812612e5beb4e77049fb013f6c84ecd7085e8bda.nq.gz
    ├── 8183851fa60af0371e9aed2da9d8671d81e07130.nq.gz
    ├── 83548c9b2ee3859615142b22af8ca24e34265bf2.nq.gz
    ├── 8561ed546153b0f007d8ceca4e63347163719e17.nq.gz
    ├── 85a6905c3c0720e52419bf93ea7d23f8c1beb6a4.nq.gz
    ├── 8626eb3948432234198765e67dd35048a3525621.nq.gz
    ├── 86cbbc66c45abe96693f61f02cc988261b0d0cf6.nq.gz
    ├── 8ace95e75663359a7002ea8a8fb7cc2f7c083ecd.nq.gz
    ├── 8b7f1ac6638a49cc923f00387800ee251dd8d8da.nq.gz
    ├── 8c17f9af8bd1a614a11625ce29836bde80e98f4b.nq.gz
    ├── 8c3655d6ef0465bf0ecfa44c96d343246b833808.nq.gz
    ├── 8d8790e5de535650ebb65a34daff53a3ff2a3d3b.nq.gz
    ├── 8dc30a6736e1941cfc5b2a26072683fe1fdfa141.nq.gz
    └── 905ab688239d49223daea09526c6adaa4721908e.nq.gz

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

[mauricio/postgresql-async](https://github.com/mauricio/postgresql-async)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
