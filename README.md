# Repolex Knowledge Graph of executablebooks/sphinx-design

RDF knowledge graph data for [executablebooks/sphinx-design](https://github.com/executablebooks/sphinx-design), parsed by [repolex](https://repolex.ai).

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
rlex download executablebooks/sphinx-design
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4f66f32e160f16d73dee5eed52cd91984935763f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4f66f32e160f16d73dee5eed52cd91984935763f
│           └── chunk-001.nq.gz
├── blob
│   ├── 014b0085e693a094233064a2b6d57f42ce07b051.nq.gz
│   ├── 019a2a7bea37cdde6914ff15272cb14fac210480.nq.gz
│   ├── 056e6beb8c7eec0343d744a20ea0102d93aaf675.nq.gz
│   ├── 05827d09b5235712b88068a8765f1ac4adedf8a8.nq.gz
│   ├── 059bd62215f962509b9a591ba5af49885dafedea.nq.gz
│   ├── 05ed33499dee1546ee4eaab34f9c0c81e093106a.nq.gz
│   ├── 0778a88a44182c6acba52244efcd71812c52ed33.nq.gz
│   ├── 07cfdaf89738fb570e96898b478227ebadf8651d.nq.gz
│   ├── 099e3d1cc46298a30f2f87f6bc34399c7036ed5e.nq.gz
│   ├── 0ac7c24a2ca47f5d889297b4a8287a377168eac2.nq.gz
│   ├── 0d70b73cbdd30e41d31e598b9394e3125b635a42.nq.gz
│   ├── 10a2e3e7bea51b20c4a22dc76fec025129e80727.nq.gz
│   ├── 11dcd65718985de17ae348704893b3d668ee763b.nq.gz
│   ├── 159cf8c21b2499fde2eb820364735b43a757bea6.nq.gz
│   ├── 15fe68c6861796ca9d503812d5c9e1cf0a738935.nq.gz
│   ├── 163074d5b43ac314f9db311945cb4c19fd0c3d44.nq.gz
│   ├── 1663de7c35264eacc7d395be1aaaaa119dbcd097.nq.gz
│   ├── 167848d215b9661dbdb95963c3af2f70f831ab61.nq.gz
│   ├── 171a920ddf5f97e862352ac750f3fe8e49cf2b6c.nq.gz
│   ├── 1a54e8ecd8984b429e436af1180543804ab0836b.nq.gz
│   ├── 1a5c77a2beb18961568acb7d36037d8e6b18fc74.nq.gz
│   ├── 1b16c912fb30820c940a428c1ee0bb5f2385b1bf.nq.gz
│   ├── 1b63a17d30b79506d7dc91a75abee1300df4cf06.nq.gz
│   ├── 1dba1ddcf46fd88bb1aca505f3ebd13218729d24.nq.gz
│   ├── 1f31abd0d4b0afed2eba5fb6e5e8483a22703651.nq.gz
│   ├── 24318c3c2376b42ee38d2c87df8e3c0588cd03de.nq.gz
│   ├── 274dead22eb8b7acea1be05bb4d145e09ef518f6.nq.gz
│   ├── 27fbb3fd67c9c65323b180489648f27d91b777c3.nq.gz
│   ├── 289ff1e79eb86d33e9d252a2a1a005a569c238fc.nq.gz
│   ├── 29bab30851f3a1b7f24e8be21fdef93a36c23e7b.nq.gz
│   ├── 30a7eef0fd7621b4f9b4454d1043a633bff2b074.nq.gz
│   ├── 3177fd18c89da105acf8983cec726c281db38c0b.nq.gz
│   ├── 31c720f82a04f0d0bd16ed8aa40b91977ce46d62.nq.gz
│   ├── 3305a707503c2ccf0b3abeba7946a23bb11e5b2e.nq.gz
│   ├── 3557e9103ca22c41bd82a9b1e4d46d7976a0c9aa.nq.gz
│   ├── 364e2eccf4b98b9c6870b9d19483434728d98a97.nq.gz
│   ├── 368e9033568e303890ca259403b1dbbe99e62577.nq.gz
│   ├── 36a6b1d0ce4ef86361efd17a34bb6d86ae6315cd.nq.gz
│   ├── 370ddc7066c040747ad34125bd99a644c2177e35.nq.gz
│   ├── 3a9b504e9c1dc36358750b60f42d9d0d62402d3a.nq.gz
│   ├── 3aa8545d2ab76fed7da1d2f246923c1923579376.nq.gz
│   ├── 3abfbafbf6deb04c96fea5cc3e6d4e0a311f0a7b.nq.gz
│   ├── 3c12742a92fa89453b2f580ed7b4dfed58961de6.nq.gz
│   ├── 3ce74f198ad455919534274cdb956c76e99fbb41.nq.gz
│   ├── 3d26f9cefaeb1ba20e4a5e4945dae2e691540c5d.nq.gz
│   ├── 3d74e127514722ea338c03cb1795734bf994be0d.nq.gz
│   ├── 3efe34bb08834ca2255e92a2b90ba0f9f8f90360.nq.gz
│   ├── 3f19b8869f88e87a24082e0909482e1c80ba6528.nq.gz
│   ├── 405595e8dfa7cdd795082b5dd2fbd979672b15b1.nq.gz
│   ├── 447e1a71c4c8d6dff91bb11eb335d927ea774334.nq.gz
│   ├── 454ad687ed6f662fe57025124905ef31276cd3e6.nq.gz
│   ├── 456baded41e36be9b260341b6d024de82c8d9c15.nq.gz
│   ├── 47d33b31b4017886dfe9e6fc7019c40c3f8aae3f.nq.gz
│   ├── 493b0374b80892f64ced8ce18ae471750226ae69.nq.gz
│   ├── 4f484196348e79fd654ad0d17c35602344d59319.nq.gz
│   ├── 4fb7c3347bf41479bdf8f32dd6026669953cc9ed.nq.gz
│   ├── 520901f80accb38632511cbbcb893ee90fb3951b.nq.gz
│   ├── 57d505a73071de0118e73af14179eb4acb91ab9d.nq.gz
│   ├── 57f6dd35305ad5e0ec2b415cf9aa8873293bd860.nq.gz
│   ├── 589b7bbace08b55a10cc5599802574f736813b80.nq.gz
│   ├── 5bd02be6033f9ed5e97925eff4116fae2d918168.nq.gz
│   ├── 5c1fe1bb7322168c3cfde478953fa47b50963291.nq.gz
│   ├── 5de87e1e225dc85d3437b87803a8c18c686605f6.nq.gz
│   ├── 5fbffbff016a7a026194010ddba2f70988f5bf70.nq.gz
│   ├── 601c58809003b2851f7cb494c7bb9e7df7beed71.nq.gz
│   ├── 60c209253ed5a2f9db64d8bfd136669c7ed190fd.nq.gz
│   ├── 643492ec27b152022748b4c75d5d38fd8c192a73.nq.gz
│   ├── 64dbfdcb95cae9addb94961453cd7a1ccffb8f71.nq.gz
│   ├── 65b1604a981038ec8ea6eedc640aadba8bb194d7.nq.gz
│   ├── 6658f08b8ade6db65b8e626b9a4b2d504d52f9c3.nq.gz
│   ├── 6659563f8e19f6aebc408991667b0437bd1ccd4d.nq.gz
│   ├── 66a966529a8f3ef8bd8cea5ad287bfe668446f43.nq.gz
│   ├── 66ba37be4880c961be5adce6b8e5c265d2b53835.nq.gz
│   ├── 66efc0fecd1554e6e4681fcb149692591f388bf2.nq.gz
│   ├── 6a3432082ba0952b24d2a9f2d60e8726c81b3b06.nq.gz
│   ├── 6b292afbf26c2f66dc3745c56076f68780358333.nq.gz
│   ├── 6c76f99d03a8cb7352b85ff076bd07ce246a9b04.nq.gz
│   ├── 6d25fbe0942e47cbafa26c2549adb1a30012c6e9.nq.gz
│   ├── 6dce53bc4597ff35ab2964207480572f25103eb6.nq.gz
│   ├── 6e35135b191b190cd6681c773309232aaeb8b1fa.nq.gz
│   ├── 6f6cfac8fb98d12d4d80d21726f1ac2990011b5c.nq.gz
│   ├── 723390c606affbe0b041a31ccc9b3f94666c3690.nq.gz
│   ├── 73be1242faea98f63721d1bd330d8b98b865c7df.nq.gz
│   ├── 74b6eab302a6c5752ac1cf886dfd6f5c69a87077.nq.gz
│   ├── 7522104c9867c2ef724e6cf83991c08c294a6260.nq.gz
│   ├── 7632ecf77545c5e5501cb3fc5719df0761104ca2.nq.gz
│   ├── 77846a6ba1319661a8b8f9e79d79b6f7c0291c25.nq.gz
│   ├── 7951d0af5701dcedbc4a5f051681e8d80611f52d.nq.gz
│   ├── 7c9f7522e464c1413ec50479b75ff65b67f488f8.nq.gz
│   ├── 7d263e195bcce5eee8133a253d530dd936715218.nq.gz
│   ├── 7e0f5a1e95ddf8f44a1d4765c8c2a33f737c8463.nq.gz
│   ├── 7f543b1d597887f23d3112a1e6e98b0f024646d3.nq.gz
│   ├── 7f7da5164c31841d50b7280453cb0b28970d23cf.nq.gz
│   ├── 83373856a8647f472c66f5f019ab4d0385d37c87.nq.gz
│   ├── 8353f88f09113907f8c50026f00bc33ea206d909.nq.gz
│   ├── 84b39a02afb4d405ff9e2ae07cfcb7fd9c36d83e.nq.gz
│   ├── 850caf35607398020480bef0a9bfdbe418e3a40c.nq.gz
│   ├── 86461813ca939e84961b5cbd7d3cbd2e96131df0.nq.gz
│   ├── 8679cf74d1f42998053e9a9ddc6ee2872051d938.nq.gz
│   ├── 878cc210effed1c005519323f3b05ddd83fd03b8.nq.gz
│   ├── 884264c8a97ea55533ff3e9dee794359ce7eebf8.nq.gz
│   ├── 89929ec4ac4935c79f4a61009160da42cec35502.nq.gz
│   ├── 8cb34e5aa37dbd4bd0ff3bff56998c986b51bf0c.nq.gz
│   ├── 8de29773ffedf2df9328cc43e18432a6b37fb86c.nq.gz
│   ├── 8f976e72d5f81fab7bdaa27aed6ee9bdd9511fb8.nq.gz
│   ├── 8fcf9a671e1cbe96a03c031c63ce35bd8ee6716f.nq.gz
│   ├── 933097832e37b547319e9be6d6c70af7d4c801f9.nq.gz
│   ├── 94512fbbd2f69e7eb6456598b47848432d38f56b.nq.gz
│   ├── 9564ddaff96f8d168e30e128f612844b6897d468.nq.gz
│   ├── 95a4ce6bacdf62725b4b8bb1679b5a12f58330e1.nq.gz
│   ├── 95eb8ba0b92f7ff6c7329475753a9a03e5af6991.nq.gz
│   ├── 9a2327a23eab69d38ef222602248378b43937ede.nq.gz
│   ├── 9aaa1c29faa6cf241e0427748d72c9db9a86152e.nq.gz
│   ├── 9d90a6a9030a6f9852194863170ebf3fc66505d4.nq.gz
│   ├── 9e37db361076568c132603c63886a79344ba29d8.nq.gz
│   ├── a18dfcc85f63946be46c4fb4841111f05f7bbc0c.nq.gz
│   ├── a4f35f78ffa700263ed35ce9ccfc38cb0db9a9d3.nq.gz
│   ├── a55ae978aad98eaec1e469cd7bcdd2e969382231.nq.gz
│   ├── a7442efcc0ce6e42027752a127c8ce23cac932a1.nq.gz
│   ├── a9792997a95bf4095f23623ff1479763898661f6.nq.gz
│   ├── a99e24eab2761e7e52833c75b246b1bfabeae108.nq.gz
│   ├── abc2bd5c6fa737e9f02ec11f56c33ac0202166fd.nq.gz
│   ├── abf278ef984beea8f08a5229d7199b5d7bf27c29.nq.gz
│   ├── adadad8694887aa2c36fd63f48a85c21e3ffe49c.nq.gz
│   ├── afc59a51486fde3f2474aace2c5506932f964ec9.nq.gz
│   ├── b01a458c9d8a22531da328d01a12e75bbc0d383e.nq.gz
│   ├── b11772ffd0dc986e5afc2994b4683f9bcff2c757.nq.gz
│   ├── b42bb2835005d405a28f24baa0eb43b8f88f0671.nq.gz
│   ├── b4cce89fa7632b6f53129b1b8e182bdd067b0b99.nq.gz
│   ├── b513a5e79f56096c18f3585db5e15c0054320dd6.nq.gz
│   ├── b5bcf4ebc375813573ed068269f3a6729c1411bf.nq.gz
│   ├── b6609f0b842f97b87be2097954e87b291b2bf85f.nq.gz
│   ├── b936007e9b607a7329f93ca0b501e3e5d41a5afa.nq.gz
│   ├── b9991c1e3ee525e09dc4696a45d0096931eb2101.nq.gz
│   ├── be11c8cded19b152cf66a0ac004e7f0b2ba26411.nq.gz
│   ├── be91b58341500fed40963f1ba39b7f47e18ff5ac.nq.gz
│   ├── bed0566194323bef1fc007966f407257515cc6ad.nq.gz
│   ├── bfaa2382082a766c39c8552d76377b8c80c6398c.nq.gz
│   ├── c0325c0ceeda4f6a4b36d953a7e71398737793eb.nq.gz
│   ├── c0372a08ccc6415755d78944972e7e6d16c09875.nq.gz
│   ├── c15a6f2bbddc3a37b76ae6260c0567a8350b7f4b.nq.gz
│   ├── c275fbd17853da6a33cc079a738422cb0636fd4f.nq.gz
│   ├── c3b2cfa04c6d83de5a98ea0efed785b765eb6dec.nq.gz
│   ├── c3e719260847a7120bec3fed57e49db0c8f5ce1b.nq.gz
│   ├── c406bfea71c005e138ec0b44a26228fc5e8c9440.nq.gz
│   ├── c7cb98b71f5ad50585c2344847ef9889680e619c.nq.gz
│   ├── c8b7f4d4ee173b6644d79afcdba091a5c22516c4.nq.gz
│   ├── c9842bcc97f3f304ad4c8d914fe6298895c9ab0d.nq.gz
│   ├── c9a49971ad34426c1fef48e4efd27fbf67527adc.nq.gz
│   ├── c9f3376516131bde3fe06909047ca0768ff454bd.nq.gz
│   ├── ca8849fa4fa921d5d7c128c91c63e13cd1bbd6e5.nq.gz
│   ├── cc4b114f3ddb09340082fbf98a95dfc8f5fbff7f.nq.gz
│   ├── ceb2e67a63cc5414050b303a0b039b506954aa80.nq.gz
│   ├── ced4d810c6aad979354fdc8d25803261b9b20160.nq.gz
│   ├── d13928d46ad63013be537564aec3a1740b48e3ff.nq.gz
│   ├── d18b7b065601b3a8c7c8d999c7f9886ce4b041d4.nq.gz
│   ├── d2fbe12eb21b8ce3644ddcf8701d980845aa2144.nq.gz
│   ├── d33018d22bca4186b6acd33094c11bba89c4d379.nq.gz
│   ├── d5292731e5d01d7e0afe2447f5b6ef66724af3d2.nq.gz
│   ├── d6bd96e0b8fb7970e9507a689490f1c2f0286efb.nq.gz
│   ├── d8d7c5f258873cc2b78c5f4ee2f89d51793b76f2.nq.gz
│   ├── dc651e50ea16a10ef50cd96d07b8812605e49933.nq.gz
│   ├── dd9c3d8018f1dbe50081cf6a717b57b99bbd646b.nq.gz
│   ├── ddb2d745283b15adbe23d20d88cfdbc8c1e7fc71.nq.gz
│   ├── dde1d148b4ad1a03c3b3b29e6c0ece2a874a5f6a.nq.gz
│   ├── deb17d268a7975018ff1932844e9d7088067724e.nq.gz
│   ├── debff0307f00b3fd0794af0471a9ae7aa9ab296f.nq.gz
│   ├── e370b162f2d362ff20e1bfe85833267d3bbe3408.nq.gz
│   ├── e539e56f8dffb71500d8a297ff555f638288554b.nq.gz
│   ├── e5a6b639ca55d6c4f264770cef8af7a8e6cfd2bf.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e715cf480ba2f5fc138a9dcb3ac59f155506c8f0.nq.gz
│   ├── e721db06cd12acdbd777a01f04890a332385468d.nq.gz
│   ├── e7980ba13a39cf49c83ea046189520066e145f8c.nq.gz
│   ├── e8b8579550e09c54a17bb2b772344007f9683c74.nq.gz
│   ├── e8f6b6af1d004da067358275a74258d1d7c200cb.nq.gz
│   ├── e9133ea44de154f1f033efeaac7f6053af5330cf.nq.gz
│   ├── ec51cfb84e8f56130ed470cdf3c0c5fcbc28c262.nq.gz
│   ├── ed6c29d3db8d442db8dc9958dc768b89fe59d4df.nq.gz
│   ├── ef378eb8833603561770c73333eb917d6979d16f.nq.gz
│   ├── f28d7c3e790ae434b3eabda24404e114ba0dc9db.nq.gz
│   ├── f635158f7d14e5db93b1a5af575a557300b2e170.nq.gz
│   ├── f6f1b32f42d0d78f9acf33661ce0b7ad2768d2c7.nq.gz
│   ├── fb620fb1ab81a71584dfb46bc9ad189ab482606d.nq.gz
│   ├── fdd6ff695a9afa7dcfe9d31977b0b7dfd7ce0c13.nq.gz
│   ├── fee6d980e7f5ef6442d474325614006a37371974.nq.gz
│   └── ffb0724427fe0f5dea4bfea6f398bf7ff7d37f0d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4f66f32e160f16d73dee5eed52cd91984935763f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 195 files
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

[executablebooks/sphinx-design](https://github.com/executablebooks/sphinx-design)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
