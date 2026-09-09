# Repolex Knowledge Graph of jquery/jquery

RDF knowledge graph data for [jquery/jquery](https://github.com/jquery/jquery), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download jquery/jquery
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 0cc1ad64ab0f482c13d6edd2a5226f309dd00006
│   │   │   └── chunk-001.nq.gz
│   │   ├── 1552b93ed57f1c0ca3ac813d63165f3e53aea20d
│   │   │   └── chunk-001.nq.gz
│   │   ├── 18c9efdafae6ec6f959e9bfa3537b83706e4aaa2
│   │   │   └── chunk-001.nq.gz
│   │   ├── 2f0ac8237db2923ac9171e4d6f00a0361ab829a2
│   │   │   └── chunk-001.nq.gz
│   │   ├── 32b00373b3f42e5cdcb709df53f3b08b7184a944
│   │   │   └── chunk-001.nq.gz
│   │   ├── 33b548c8e3d43b2ebdfb129fd8086a3b0c905919
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3ebfa938d4ca68523b41f2a30bd23c1592319637
│   │   │   └── chunk-001.nq.gz
│   │   ├── 49b55127e2bb6cf6fcfcc32cba8173ad4c1b6012
│   │   │   └── chunk-001.nq.gz
│   │   ├── 4dec426aa2a6cbabb1b064319ba7c272d594a688
│   │   │   └── chunk-001.nq.gz
│   │   ├── 51fffe9f7395f86fb24c59115c9b98855c39fc07
│   │   │   └── chunk-001.nq.gz
│   │   ├── 586182f35e818c318046dac1cbaa31ee7a07ee21
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6786a17edf982c50fd236ffa84cbde1a5723430e
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6ad26fc72ddbc9d3f3886f98164efabc112d6c78
│   │   │   └── chunk-001.nq.gz
│   │   ├── 73c6a233e64c9669c24aa195ee37bddeeb8d568e
│   │   │   └── chunk-001.nq.gz
│   │   ├── 742610f10e071865fb56907027f9d62bc646562b
│   │   │   └── chunk-001.nq.gz
│   │   ├── 75f7e963708b60f37a42b777f35825d33c4f8e7a
│   │   │   └── chunk-001.nq.gz
│   │   ├── 7751e69b615c6eca6f783a81e292a55725af6b85
│   │   │   └── chunk-001.nq.gz
│   │   ├── 7a0a850f3d41c0412609c1d32b1e602d4afe2f4e
│   │   │   └── chunk-001.nq.gz
│   │   ├── 81b34284a3d5e7dda0a2aff82dbee0e0ffca41b4
│   │   │   └── chunk-001.nq.gz
│   │   ├── 8f2a9d9272d6ed7f32d3a484740ab342c02541e0
│   │   │   └── chunk-001.nq.gz
│   │   ├── 97525193735ed32c332f0dbaf2f782df8b1b949b
│   │   │   └── chunk-001.nq.gz
│   │   ├── a04f5ff9795fd6292117563623db44cf3f875868
│   │   │   └── chunk-001.nq.gz
│   │   ├── b7fc909edda2d8cf63d0eaffe9bd12f33e492ad3
│   │   │   └── chunk-001.nq.gz
│   │   ├── c25cd3c4ba60daf166dfcee729f0bc69fd52a565
│   │   │   └── chunk-001.nq.gz
│   │   ├── d0d2d9b9b004cf0c6763c871646e01ca67579253
│   │   │   └── chunk-001.nq.gz
│   │   ├── e1cffdef277fcf543833a20d28cbadcd000ebece
│   │   │   └── chunk-001.nq.gz
│   │   ├── ef18fe9af5db5088657d42fde07bb23b19d0c494
│   │   │   └── chunk-001.nq.gz
│   │   ├── ef64d82ec3d1717478979cba986d896aa0dda617
│   │   │   └── chunk-001.nq.gz
│   │   ├── f5416725afefb0c8ff3beb4ed4ff4b8ab3d22f0d
│   │   │   └── chunk-001.nq.gz
│   │   ├── f71eeda0fac4ec1442e631e90ff0703a0fb4ac96
│   │   │   └── chunk-001.nq.gz
│   │   ├── f79d5f1a337528940ab7029d4f8bbba72326f269
│   │   │   └── chunk-001.nq.gz
│   │   ├── f9846aec1dadc4bc80ca2df47d3ecc1b9f7a4f84
│   │   │   └── chunk-001.nq.gz
│   │   └── fed61fb5b4d622908d033d2ec8ebc0bf7901eda4
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 0cc1ad64ab0f482c13d6edd2a5226f309dd00006.nq.gz
│   │   ├── 1552b93ed57f1c0ca3ac813d63165f3e53aea20d.nq.gz
│   │   ├── 18c9efdafae6ec6f959e9bfa3537b83706e4aaa2.nq.gz
│   │   ├── 2f0ac8237db2923ac9171e4d6f00a0361ab829a2.nq.gz
│   │   ├── 32b00373b3f42e5cdcb709df53f3b08b7184a944.nq.gz
│   │   ├── 33b548c8e3d43b2ebdfb129fd8086a3b0c905919.nq.gz
│   │   ├── 3ebfa938d4ca68523b41f2a30bd23c1592319637.nq.gz
│   │   ├── 49b55127e2bb6cf6fcfcc32cba8173ad4c1b6012.nq.gz
│   │   ├── 4dec426aa2a6cbabb1b064319ba7c272d594a688.nq.gz
│   │   ├── 51fffe9f7395f86fb24c59115c9b98855c39fc07.nq.gz
│   │   ├── 586182f35e818c318046dac1cbaa31ee7a07ee21.nq.gz
│   │   ├── 6786a17edf982c50fd236ffa84cbde1a5723430e.nq.gz
│   │   ├── 6ad26fc72ddbc9d3f3886f98164efabc112d6c78.nq.gz
│   │   ├── 73c6a233e64c9669c24aa195ee37bddeeb8d568e.nq.gz
│   │   ├── 742610f10e071865fb56907027f9d62bc646562b.nq.gz
│   │   ├── 75f7e963708b60f37a42b777f35825d33c4f8e7a.nq.gz
│   │   ├── 7751e69b615c6eca6f783a81e292a55725af6b85.nq.gz
│   │   ├── 7a0a850f3d41c0412609c1d32b1e602d4afe2f4e.nq.gz
│   │   ├── 81b34284a3d5e7dda0a2aff82dbee0e0ffca41b4.nq.gz
│   │   ├── 8f2a9d9272d6ed7f32d3a484740ab342c02541e0.nq.gz
│   │   ├── 97525193735ed32c332f0dbaf2f782df8b1b949b.nq.gz
│   │   ├── a04f5ff9795fd6292117563623db44cf3f875868.nq.gz
│   │   ├── b7fc909edda2d8cf63d0eaffe9bd12f33e492ad3.nq.gz
│   │   ├── c25cd3c4ba60daf166dfcee729f0bc69fd52a565.nq.gz
│   │   ├── d0d2d9b9b004cf0c6763c871646e01ca67579253.nq.gz
│   │   ├── e1cffdef277fcf543833a20d28cbadcd000ebece.nq.gz
│   │   ├── ef18fe9af5db5088657d42fde07bb23b19d0c494.nq.gz
│   │   ├── ef64d82ec3d1717478979cba986d896aa0dda617.nq.gz
│   │   ├── f5416725afefb0c8ff3beb4ed4ff4b8ab3d22f0d.nq.gz
│   │   ├── f79d5f1a337528940ab7029d4f8bbba72326f269.nq.gz
│   │   ├── f9846aec1dadc4bc80ca2df47d3ecc1b9f7a4f84.nq.gz
│   │   └── fed61fb5b4d622908d033d2ec8ebc0bf7901eda4.nq.gz
│   └── repolex
│       └── 4dec426aa2a6cbabb1b064319ba7c272d594a688
│           └── chunk-001.nq.gz
└── blob
    ├── 0039b95b02ac02222d4f8bdf57c384bf7a0a40be.nq.gz
    ├── 004ecb2046b8a224963f4c46fcb94433ee674fcc.nq.gz
    ├── 00b08489dbf3803becf5246117dff9b11d87ef17.nq.gz
    ├── 00cdc8659bbd50e37b56553bcdded042be924850.nq.gz
    ├── 01111e1102c92fc79fd88c16fb8efb03774ebadb.nq.gz
    ├── 0112264a47bc9a0f5b5231da1e27a96a48fce857.nq.gz
    ├── 0130f31757f014af5c77ed8965c5a6d678c74c28.nq.gz
    ├── 013189521d29585f73b59beed8efa6bd27620af7.nq.gz
    ├── 0132a0129c0e6cfbfa0e35ef8a190c9576d511f6.nq.gz
    ├── 013fd77949190710f0c4890c5c5e1fc933bb79fd.nq.gz
    ├── 014672b87746c6220316679d6a472b96299870a5.nq.gz
    ├── 01583637c2716ae0c4f99d9ac0c5aa816c475355.nq.gz
    ├── 0177f4ba2a34cc6797abf6ac932a7378175dfc12.nq.gz
    ├── 01ccad3aec52301258ea6717802e2c53c2adb6d4.nq.gz
    ├── 01e0d4b5600189c3fab8e951576cb9737ebd969c.nq.gz
    ├── 01e86868884c86ab1a32b759da77a269f5f0bc9c.nq.gz
    ├── 01e9733b8503ae3c49dd11504d77c18837ac149d.nq.gz
    ├── 02994bafaeaaf97029d62a5686b782e5974d6752.nq.gz
    ├── 02a4b8194ee9d03e47c923b99e1c7be533fd1182.nq.gz
    ├── 02a69318aa92629eecd046dbaf257de182dcdc44.nq.gz
    ├── 02aad5e361c14b436dffef15437b8729c3fbd0e0.nq.gz
    ├── 0340fb6e0d1e44652ae474e997799998493f84d4.nq.gz
    ├── 034ba89f4d47422801cb3667de30f1736400a874.nq.gz
    ├── 037ef0998e345dc9e50f05cc22902226577ff2dd.nq.gz
    ├── 0386b00548aea381b301752726c54247cd1552a1.nq.gz
    ├── 03bdbde1eedb3401ddea3a4db3eb731bfac8e38e.nq.gz
    ├── 03eefa73a808849c77f8bf61eff22b6c82bd342a.nq.gz
    ├── 0425d3631ff01ed2fbd1c682a652118e19e46bb9.nq.gz
    ├── 044dc09ddec6f9064edbf044e801bcf77bfeffe5.nq.gz
    ├── 044e23823acac0efa12f2811bbb85d56e2bcfc7e.nq.gz
    ├── 046ae91b9128f95f2f40cc0e9c81ce99da0d3f25.nq.gz
    ├── 04810494a75980debed3d0a9becd540112d7bc8f.nq.gz
    ├── 04bf13edf57b8b0585d16f6862b6a3e363f61961.nq.gz
    ├── 04ca615eb0778abc999ed164754c065d94d1c869.nq.gz
    ├── 04d44443d274b33cea25a59f0659ae7b457c288b.nq.gz
    ├── 04e16b03e7c5a1dea0bc0d587584dd894211712e.nq.gz
    ├── 04e8a2f7ad005144c54354d952d8e21c0a09566a.nq.gz
    ├── 04ee403d5d8e52958432ebe217edf7204dc109f4.nq.gz
    ├── 0502146ca806bc11f2a9a26a0143d87e31c504de.nq.gz
    ├── 0569013d4f53c60b6c3edb04da0849124d0097e6.nq.gz
    ├── 056cda7add66c907d258c1cdc1fd2dd641e55722.nq.gz
    ├── 057ddd56d287a906dcc9a86ecc8dada6660ee161.nq.gz
    ├── 05c1d9e7612acf07af78b65978245361e0704d39.nq.gz
    ├── 05cd8eaeb731f520e2cd43306ec4dae47e8cd4a1.nq.gz
    ├── 05d6aad294ca000666d0111f04b4dd0da2a76651.nq.gz
    ├── 05fddd15b0bc00b1c420534dfdb73a02e77f4b8e.nq.gz
    ├── 0609a700b689856c621d3b132cde40c8e4479ff8.nq.gz
    ├── 062bad02b310e8ef7c9ed69398e53c02eef70a85.nq.gz
    ├── 067516a7515a63677a247b3a95912712e911a454.nq.gz
    ├── 0689d4548864f1b48c30b78331086c497dc1e62e.nq.gz
    ├── 06dbe065b122d8bcd61168de8aa4024c68618fc5.nq.gz
    ├── 06de4acd9f64f597dc66e603f8a0aa7ce978ab97.nq.gz
    ├── 06fc37439caa95ed9bb20bbc9ee3bdb1145e02fb.nq.gz
    ├── 071deb6458c403a019564429f80a92a020710210.nq.gz
    ├── 07285a56d66b834f94caea265ef06752d75b5028.nq.gz
    ├── 07576738a10dacee124bfa524a7ffa66b1b9b73e.nq.gz
    ├── 0768b6f708398d6985a2c4666c93ec597ac59c39.nq.gz
    ├── 0783e1774b3b4787a4683281a14e1af1e793360f.nq.gz
    ├── 0784ae0a82431c8432879209e67a6b4dfc48986a.nq.gz
    ├── 084f8c7bde35862034eb252bc02014840c0aaacd.nq.gz
    ├── 085d19a931ff2a2d7f486b235411514898c5c321.nq.gz
    ├── 0871aae881074b442e0cea950421201f50ad9a35.nq.gz
    ├── 087ce4eb72b3cdf8c9d34f81bacce4334dc570d7.nq.gz
    ├── 08a4543e43cee5e64afa80a206115898929377cd.nq.gz
    ├── 08b384a7e353024017b71accce13f92a8387de6b.nq.gz
    ├── 08bf60ee00a4ca8066047b217ad04bf4129941f7.nq.gz
    ├── 0901c6bfe6c38b503fef9c57c6632f38185db93e.nq.gz
    ├── 0933a1d3387f72c2254becc054d6a6da25cab4af.nq.gz
    ├── 094d0aece05d56c1491e0a2c941f04e4e17dd844.nq.gz
    ├── 095b463812a0af30f7c6b5e30235457c9fbb95de.nq.gz
    ├── 095c12214df863ec2fcc7d66c0a836631d3ef74d.nq.gz
    ├── 096370a4f2433bcea449e450207fc09e2ce6edf0.nq.gz
    ├── 096f8568380fcc4373608f0b9d6c52ac1b34c085.nq.gz
    ├── 09814bdedb2e42e9b907d521309cd3f236844eb7.nq.gz
    ├── 098b7da85006c0a4c892ff015a9f05ccc5990094.nq.gz
    ├── 09da35152eb2386fd2e014332f5ecf8362c703f7.nq.gz
    ├── 09fe0da4c6136ba5135b5652a7b74424339998ff.nq.gz
    ├── 0a575841169493c2c9d5b7188e2b19bdc63b6bee.nq.gz
    ├── 0a5ec6756538f1704f5e44acb4c3d3df8cdf57e0.nq.gz
    ├── 0a6862d6bd3e5bf51d7ed277a1deaa54bcbfc2fc.nq.gz
    ├── 0ab610e29412651837703cdc176513105430c382.nq.gz
    ├── 0af1f4964435caf3a38649b7660fbf4df1aa248d.nq.gz
    ├── 0b0d385b7a63ee8805b63d5eefccbeb14c864c78.nq.gz
    ├── 0b513f04272b217b3fa9fc8d80d78acf01b9878d.nq.gz
    ├── 0b893acf0b2a2736979cbf0d11d0dbf44497a65c.nq.gz
    ├── 0b960dbc427c35b8f56d9a6ee700760984783780.nq.gz
    ├── 0bae02a876a29be85306e97d3bc219a2474c57c3.nq.gz
    ├── 0bce9dee3bfa4a0f418975e5778755ac34208da4.nq.gz
    ├── 0bee7a8e8f98f4c5fd0110b4471a8df9bc54dbd5.nq.gz
    ├── 0bfe5f073dbb394929c51ce3c4a621c38ff21980.nq.gz
    ├── 0c057bae8732c6ac053a82c1e5c9905c2b800b0a.nq.gz
    ├── 0c104b77756335e85e291fd26f63a7e8ec655dde.nq.gz
    ├── 0c144c19481dba244558c291e27151c384305580.nq.gz
    ├── 0c379d051d3ff1356c5c1a4767fdd887747016b9.nq.gz
    ├── 0c3bda624bc78aa710eee8f2ab4a4779b6f4622f.nq.gz
    ├── 0c4418bc6de18ef344b4c5b740390da1a84fe414.nq.gz
    ├── 0c77c8a5833d43fe0530aba7c6800e4a814940cb.nq.gz
    ├── 0c80cd53a795d57c541211873ce51c2cb1e24162.nq.gz
    ├── 0c90a8dffdb95ec4678f18e07623f9d111c32540.nq.gz
    ├── 0cbea4a7a5da6c0793d30bafade31c2b6dde74e2.nq.gz
    ├── 0d10219621d0b9b73d0724afb94e1777bcd72fbb.nq.gz
    ├── 0d1d554d18607327f462224dc78232cf896d5a6f.nq.gz
    ├── 0d44990fc30e425f8a475dfd6794a82b4e0b286a.nq.gz
    ├── 0d4c1c4c36cb47f1988f5812b7bb740c73974148.nq.gz
    ├── 0d6dfec6ddbba35af2292825cf8d08e27fe398f3.nq.gz
    ├── 0d9bf0f2ed646c1c2379afea502bcd6289e9a65a.nq.gz
    ├── 0e026a6c1c7ac4c15d8cb02a75b698677e927ef2.nq.gz
    ├── 0e0b377f1c3732a77dd651f9403a8c5d22ea3fe0.nq.gz
    ├── 0e22886ad335934c627257125c34aacf0eb7f56f.nq.gz
    ├── 0e279fde17024c0a14bf2e7abd8de90c29746f1f.nq.gz
    ├── 0e29c1fc63bb7093f54226099bf4f3cf5ea695ef.nq.gz
    ├── 0e3f8b48c8a42b82a50476c320bb0db6206a4be3.nq.gz
    ├── 0e483fc5e1775c4a37572097e2fae2e084971d6a.nq.gz
    ├── 0e4e3b225383d5e3969aefd623780676ccbc4241.nq.gz
    ├── 0e6d49cfa2d66b65b9258dd2885ef9cbff8346c0.nq.gz
    ├── 0e95274cf48da5b7fd9bbd9bd6d2ab66cfc1b999.nq.gz
    ├── 0eb1d5149163a97d9dcdea4ac09dafc81c4072e9.nq.gz
    ├── 0ec45161f83328fd228ac78dfbc40eec36f1159e.nq.gz
    ├── 0edaa0c79e36929ba7d3389e9a0c0048c6d2443a.nq.gz
    ├── 0f032be57d0427053c5426d8554840c05144c080.nq.gz
    ├── 0f55b0843965636200408ff931e27092ca304c77.nq.gz
    ├── 0f6a3f78b20c16f1ad5f07c4192368d4f7a55b8d.nq.gz
    ├── 0f6de46961a483de281d3cb515bece3230c2ed93.nq.gz
    ├── 0fbfbd8530ee4bc4a8e88f940a8a98e785dc928d.nq.gz
    ├── 0fe2cbbba5b02489c890fce39946f688d46a98ed.nq.gz
    ├── 101138415f874ad1b82f018680976f39e91a1762.nq.gz
    ├── 10186dea7103830c7f5a1421b859c4e4093b7160.nq.gz
    ├── 103cf11970e76b89505c3c5455ac1f6e3cd9e49a.nq.gz
    ├── 1058dbf52009d0d35ea8fa317cea310324c61dd4.nq.gz
    ├── 10cef4a65f06da3ac86e9e89d89ecb9d1804796b.nq.gz
    ├── 10e8245613dcddd637a521c409060b7ca9bc4fd2.nq.gz
    ├── 10f4e89d28b3cca002b4b80b2ec957221de7c4e6.nq.gz
    ├── 118895916eee67c32ce0c3f873257e1eedaeb3c7.nq.gz
    └── 11918b06d6817bc7b258d96e94bf361b98fe70b4.nq.gz

40 directories, 200 files
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

## Source repository

[jquery/jquery](https://github.com/jquery/jquery)

---
*Parsed on 2026-09-09 by [repolex](https://repolex.ai)*
