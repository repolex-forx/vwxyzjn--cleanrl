# Repolex Knowledge Graph of vwxyzjn/cleanrl

RDF knowledge graph data for [vwxyzjn/cleanrl](https://github.com/vwxyzjn/cleanrl), parsed by [repolex](https://repolex.ai).

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
rlex download vwxyzjn/cleanrl
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fe8d8a03c41a7ef5b523e2e354bd01c363e786bb
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fe8d8a03c41a7ef5b523e2e354bd01c363e786bb
│           └── chunk-001.nq.gz
└── blob
    ├── 001293055f76b859b70b4eb7d37c2da91029ba55.nq.gz
    ├── 0277e1f85a274d7e1912fd48cdfbc59d78513d28.nq.gz
    ├── 03d53cd0bff28f6a61f28ec4f9fb56138b19125e.nq.gz
    ├── 042a223f7bb29659496aeb0575af53271f3657eb.nq.gz
    ├── 04cefd32294a8ac131c26419519c3ca7d4b51314.nq.gz
    ├── 04e1af491fd1f7d847f984e28aded32b3c60efd6.nq.gz
    ├── 05091f567fd1256b19b44eedfb353a6c02ffdcc8.nq.gz
    ├── 05761ac57f6bcedf28c34c3867849df97ef89a8b.nq.gz
    ├── 079df7642da07149cde64873120cd711eefa03c2.nq.gz
    ├── 07fa4506cdf071dcdf4c7fd8fd213f46af58d4e6.nq.gz
    ├── 086f8008c312c0aa8652425f901b4e78cd933c28.nq.gz
    ├── 09fe628f0cb6bf51121bee29f123a118e6c4dbeb.nq.gz
    ├── 0a13317da85801a653b02427d27bda705f642fd3.nq.gz
    ├── 0a186b20276c36a251e0c13240cc01b42712df4c.nq.gz
    ├── 0aabb7ecc8706f46ebad52df5f901690f62e7f7e.nq.gz
    ├── 0b2498f31c6c7b7be3e6ea0f8d23c3e3b7401488.nq.gz
    ├── 0bc0e13b3063bdc00c0d11c4128f9263ce10952f.nq.gz
    ├── 0bc66cf637de9f0c0f957437a4c8423cea2d16f1.nq.gz
    ├── 0be6f0f7b400caa57626a991cf6376241f11780a.nq.gz
    ├── 0c1758274e6b7c47c94dd54818ddf6798506d6fb.nq.gz
    ├── 0ebcb150b4df2e07819d940d100f9581ef15452d.nq.gz
    ├── 0fa65481a5977003519a7269baa19f1a058637fd.nq.gz
    ├── 1001d17e48770a2afd2bf1934d0b0761ddbaab20.nq.gz
    ├── 103a5f0a0d4d13380ddda4298dda1a0fa0408794.nq.gz
    ├── 109427f99fcaad614e991719cc202fa4850dd444.nq.gz
    ├── 10d0de4e547981ed44b4784e4c2acf996a090bd5.nq.gz
    ├── 11ba44399308618d505280db63a8c61c51da6ea6.nq.gz
    ├── 130538604ff41c96cb7238ea77228ca7ef07bb35.nq.gz
    ├── 134021af8eea3fd35d12503f1657b7661c805f70.nq.gz
    ├── 14ef434532fbf9f02a3106b3abee85eac630a91c.nq.gz
    ├── 16d4eac743a7dd7e5d9790faa6d5bbd7b8d35971.nq.gz
    ├── 16f793c681e675d96ec27b95b3fd3e779472725e.nq.gz
    ├── 17a6d3c29d758a6fbe281dd0c3bd5fbd792ea5b3.nq.gz
    ├── 19761dd389b11764c01a373ef3c093a75a6f830c.nq.gz
    ├── 1a4966628a51b2934fcbe9b0afb8a56a99400d64.nq.gz
    ├── 1be166fba98d5a3ad3cb2a793f682f6dfa172354.nq.gz
    ├── 1c6d9ec536e3e0c7fb8d76371818956d24ed75c4.nq.gz
    ├── 1d4cfa0e419e06ec597c3c0f8d8154a3c5ace50d.nq.gz
    ├── 1dc922230fde3c771fe833b0866d78208c8b1e79.nq.gz
    ├── 1e5249ca2772482b3a1b9f462141d397187b8e62.nq.gz
    ├── 1f099c9010b699ecffad1efb08560ca072c5b70a.nq.gz
    ├── 22626cc491f23e400f34cc96c415b0ce29f32068.nq.gz
    ├── 238690af0b0f2beb17cd59a1440eff1f81de90cb.nq.gz
    ├── 23964f04c5de4771802dd4320001cccb6fdbea42.nq.gz
    ├── 2558284130deffe335b7fffabc4b87c31e9b63db.nq.gz
    ├── 25687c0976eed27792a41b8e459875197b43f963.nq.gz
    ├── 258faa4736568378fa4ba8f96562d8876bf071b7.nq.gz
    ├── 26b3fb8647800c534379dfff35a66be3e2dac9a9.nq.gz
    ├── 2752119238b64da9e3088f4de80b8b35f743da1f.nq.gz
    ├── 275db4db8da93f7626aa2c1b8a94ca4d61d1c7d2.nq.gz
    ├── 27bb202d162f96602516ca0c81194bdc6b0c2063.nq.gz
    ├── 27e4f3de7225cf995b21f3c763af49304635e084.nq.gz
    ├── 2808d386c408af36972d2c27300d603ef0d9f621.nq.gz
    ├── 29c590051be63135e6d33a405ad3851ea6610e61.nq.gz
    ├── 2a2236fca646d8fd2cd75d6808e46c3317df8203.nq.gz
    ├── 2a923348bead0ed1c4c57e4a0ecd6f010e7f95b7.nq.gz
    ├── 2a9ab2f5d1154ac0862eb1910c51ae2010eacf24.nq.gz
    ├── 2bde496cfd67b7dd032b752b18ee7db63a44e3bf.nq.gz
    ├── 2d189947e6eeee1f862fc88a45fcee0019e331f0.nq.gz
    ├── 2f3a7d24f47a952f54f2ed76460cfefe25d8ed6f.nq.gz
    ├── 2f4e059ebeacc7df1118e8ca458ce2b7ae337e93.nq.gz
    ├── 301b8bdaa10efcb6bb6d0b8437dc4866a2d628e8.nq.gz
    ├── 316b5df9587f1c3bee978a96243ecb502cbcef90.nq.gz
    ├── 33fc1065af730e6d2f9d61e2b63f4c2bcb56d6bb.nq.gz
    ├── 3416e2c02adaf56d18fcabc5f1cd9a0afa97f9b0.nq.gz
    ├── 345f1230e22eb9149bfa27cec694a7183580ce53.nq.gz
    ├── 35ae55e61a54fdf8b86f191b57c24d860e043d6f.nq.gz
    ├── 35e20f59a430431ad931d073f0cb1c424d512dcf.nq.gz
    ├── 3676b563cf9aa29f35d1764969b0a4a4b734e060.nq.gz
    ├── 3699c9b2da018d53642be397bc65dcf878f94786.nq.gz
    ├── 36b5a5b914a390bce59705935c15462373f0a07e.nq.gz
    ├── 36d94874c63d4cb1fafab26fab5c43c94f8b3e54.nq.gz
    ├── 37b98e426f5467211769ef86fe120f2918e21a54.nq.gz
    ├── 37ef959b785897ffece0658a0003fdadaa244922.nq.gz
    ├── 383b08a0c5cfb0fe7ffec3dec2dc00d00536018b.nq.gz
    ├── 3888aaf7db18c6b580a510d58bef4936cc6efbb1.nq.gz
    ├── 39162592bde61fc3e5fa3c16ec8cc7f4fe0dbd20.nq.gz
    ├── 39a92ccda5654c82e4365ca73fab0dd55ed2d1a0.nq.gz
    ├── 3b08bc89192ad94c689f0e02edfe2c96fcbcd37c.nq.gz
    ├── 3be1cb7ae626421b8db5a99e20c024f02407a50f.nq.gz
    ├── 3c285a35a4df7dc8095e8d8d0dc8560b8bad6f35.nq.gz
    ├── 3d75b8618559ff21ebcef30d733c03d121999e5e.nq.gz
    ├── 3e9b002832d96fabff1bc216d69f13aa120588cf.nq.gz
    ├── 3fad61873698412410a78d01dd7347ed3287351f.nq.gz
    ├── 3fbd694eefdbb3c3980b69f5eac3d748edaeb189.nq.gz
    ├── 406c00897c8d80ac78499a79e76085d9d7e7aff6.nq.gz
    ├── 40e86015d657d5b2f36d70ca8432e632ea850a7c.nq.gz
    ├── 411aaed448be0f8fb405de836bd51023337c840a.nq.gz
    ├── 4125e4b421e03ffebe253ce8343cf588a9151689.nq.gz
    ├── 41b322b916eac0346c4b9dd1712d296a4f342791.nq.gz
    ├── 41c82271ddd4cd0daefa80541574df0221b644a1.nq.gz
    ├── 4349e5967dc8753eb6682f2b6e5f6a4ebaa479b2.nq.gz
    ├── 43ca1e2dbec875e78a7c7ee810f53a84b43c441e.nq.gz
    ├── 4637380768e5644ce797189a75cc576015b2e6f5.nq.gz
    ├── 487ebf5ce8414a3f9bdee5e3df4201e072aeb7e0.nq.gz
    ├── 48e434588e2ad9092ce42b9d3405082f212f98af.nq.gz
    ├── 49db86d7fed52beec7f5246e54eb097331a5d367.nq.gz
    ├── 4a418271e1ac1257f06c454df1d53e44366b6190.nq.gz
    ├── 4ba09cb2169dc2c53f53e5ece47881a67ea83350.nq.gz
    ├── 4bda819200ae23344881f84fb86c5a3ff07df1a1.nq.gz
    ├── 4c4936de36ed25a4591e5adf27eaa1bf6d234459.nq.gz
    ├── 4c5b6402432d04ca5f763ae5df6982c43e8656ef.nq.gz
    ├── 4cb022ec3808dab0657911db74e782f8fbc9571f.nq.gz
    ├── 4cc7b824cc6acd62cb596c9c171edb0d7bdf81e1.nq.gz
    ├── 4da2dd1bf6f56f5d78b81f4412ed6088bc405566.nq.gz
    ├── 4ec13334809c1b15fdeed4d97f006f76fd4d9b87.nq.gz
    ├── 4f5c67a5a0e3aafdd8887ddb6504e2c4b2fc4849.nq.gz
    ├── 4f6f20afcbea238edf874ff290f4e64fc9192944.nq.gz
    ├── 4ffc2e28d3e8e461c85b9ef9c93a0fbee27b2e39.nq.gz
    ├── 500d8c3fbe26172253b0e22b336f191c477b909c.nq.gz
    ├── 50f393a99ce0afeda88fcf6d0d986e6f0e89daf2.nq.gz
    ├── 5170814c9302ad7439a8e22933ce04662cde4650.nq.gz
    ├── 52a0aa5b47e0dc7bd3f066c40980bb0a1b9c26e6.nq.gz
    ├── 544faaf478831e528fd90b1ea02005be9befcdea.nq.gz
    ├── 5588577c9d4a749917f067f7c0ebbaf53d025b45.nq.gz
    ├── 57de960ce499049c6a55945e474166ab4819848a.nq.gz
    ├── 5922db8cf67150547aa01f446cbee5e39b1b7f69.nq.gz
    ├── 59f8450a9d11cb36d06cb90b259fced558644099.nq.gz
    ├── 5b956125e896ebb11d6fe9346ed835ff1de919a3.nq.gz
    ├── 5c385e26c47dc0ecacc93484811350d4e76c1a56.nq.gz
    ├── 5c3e06a49f1130ea3e82d191e15c9a9c7ef7adbd.nq.gz
    ├── 5cad77474a8b667f80e925c9cbbb74115545d838.nq.gz
    ├── 5db4b2f9e0c275a6c347b9cdd0d5a62e031e7f75.nq.gz
    ├── 5e62b163bc316de37ea65c8392e1a5a0dc1bf9c4.nq.gz
    ├── 5ee53a0a31ccd5e72344b2b131e3b93a533dc018.nq.gz
    ├── 5f5154301e96f5a14981bef9ad31266822869d5a.nq.gz
    ├── 6018ad11489e170b2ab4c41cdeca6aa1fea35335.nq.gz
    ├── 60b18bad393e60d0d9ff4471af30156ff345a2f5.nq.gz
    ├── 6247b4ddb23fd36973cf10274155ef3ba8f421ad.nq.gz
    ├── 633a56c8bddc2f853cd89d86e40a2ac2498e3b9e.nq.gz
    ├── 6379ff6037324ff994a27938d80b92a126ec6ebd.nq.gz
    ├── 638bb22159c23a156f9a8360c032daa02c95502c.nq.gz
    ├── 63c180543bc1cd668accd8fbeb9c75c7a6370df6.nq.gz
    ├── 64876e054dbcad06658f73457409061569390e54.nq.gz
    ├── 648c245a52d6740b34643b99ccbe24f787a5ce9c.nq.gz
    ├── 65d7e690466594ae58c99d07eca3ad1ce28f34e3.nq.gz
    ├── 69e11a312495056141936e5fc4e9d322d7499c1e.nq.gz
    ├── 6a0feff88833c03bb4b084d0d0afb710eafb76ba.nq.gz
    ├── 6a261443bb441914ebc58dbdb0b7667217fd3924.nq.gz
    ├── 6acfae97b03da76b080bd19467d90fba08b5241a.nq.gz
    ├── 6ad0219ede0923f5ab94d96af3d3e6981a40c0bf.nq.gz
    ├── 6ad5b7cc9c812689040e660c2b3f6bb61354c7eb.nq.gz
    ├── 6ba3c71a2d53f2a6ba0586bbe546993d57f6976c.nq.gz
    ├── 6baea8c2ffb39dd626cf759b57820b1a4fff13a7.nq.gz
    ├── 6c0310abe1a526f140f28844ee2e21cdfb2afa61.nq.gz
    ├── 6c426b2e55d48734ea59a44caa80abb6b01e46a8.nq.gz
    ├── 6db3d696bb3886e2b517796c0cf0781cc7e8ef63.nq.gz
    ├── 6dc682ebcaf09a79b7590746e57871a54c4c9ecc.nq.gz
    ├── 6dccf2e28f2899e73be356890245c8424b58467b.nq.gz
    ├── 6dd591a8d3ca5eb85a722d9e59a3b19229b2dbc8.nq.gz
    ├── 6f384a6f04a603d9be5cab4cc84b1cc81935243a.nq.gz
    ├── 6f3a806d229a1d54d0fbe884bfa2556d7a8cc46a.nq.gz
    ├── 6f3c1f8bb465aced62c2d549414c9a2ac540d85d.nq.gz
    ├── 71521eb5db8d184c0851b6358fd214ef791e8949.nq.gz
    ├── 71e5a15e083d089a97024a8a1dd3581e150a48de.nq.gz
    ├── 723e58afd89b2b4d7ff792b789a339ef223f013d.nq.gz
    ├── 72518ad469e854f76c1f61208d614563d2598241.nq.gz
    ├── 730bdb059c411d6501643ce235df554e255b4286.nq.gz
    ├── 74ca6974b44860d5bb6a230967ac7a6110d640d2.nq.gz
    ├── 7529546b0843e120d995b95dcc4069267dcc671f.nq.gz
    ├── 7645066d06f14260456d3be15c64d4f9c19fabca.nq.gz
    ├── 76451881e8c3199370562f6476c0cb706f889b8c.nq.gz
    ├── 774d41b17e17c2da3b65de594765baa781d0c5f1.nq.gz
    ├── 77792b2da04b15aa791a000260095113ffa21fcf.nq.gz
    ├── 77d7dcdc8fb9759274c441b4d7bb898e0c9e0c5d.nq.gz
    ├── 783b1448f8bca8d197f1fab918c0b7a50223be0b.nq.gz
    ├── 784a786180d3e64f8b9d1c4ccbd378558acf8f56.nq.gz
    ├── 790e5b081c2118dd2bbc1adb429e6c924dd6e5e2.nq.gz
    ├── 7970132b61f4a0e3cd372593dba8fa4bb92d65a6.nq.gz
    ├── 797b648b6968285f292d9e507b23d4e720ba00ba.nq.gz
    ├── 798adb7a3e29bcfae0c66939e40eec3872af9b47.nq.gz
    ├── 799ae9f646cb323f99e7c44f2867873e9a8d0489.nq.gz
    ├── 7b53b807770ce1c9631d9144dfeef2536842adfa.nq.gz
    ├── 7b671073d2176560e890e76ae007903e5d0525b3.nq.gz
    ├── 7c77fc4209de3f106d3189254fc6c28a473388ff.nq.gz
    ├── 7cec5206e4f41e14e0998625f0c4ee722e4e6200.nq.gz
    ├── 7d3503e492b8669c419a83c60a6150dfaa66d159.nq.gz
    ├── 7d82406fa0ab4078c67fe04df25d553ae3e5b2ed.nq.gz
    ├── 7eb7f3439975b0c48e7de2bbe189919d73281303.nq.gz
    ├── 7f3a4ac47a5a9c92b8bc7c2e6fdc19289777b137.nq.gz
    ├── 7fca897b78ecbaea161b26de5bfc7b16e4085cac.nq.gz
    ├── 7fe1b7de4ff4bd16dc5cb1a2be225093e6d9bc0c.nq.gz
    ├── 80d0984373cbab91fda7649e8c36e985b9152a2d.nq.gz
    ├── 8119810e8cf2644b20e094efd1df5cd9319767b0.nq.gz
    ├── 817036dd92d0395faf1f671a3602f4eea9e51989.nq.gz
    ├── 8253d169be58130a84982f35111102c30a0af8b1.nq.gz
    ├── 82a59d184c43664b934cd88bc0e075edfbdbbbf7.nq.gz
    ├── 845fe17268301b5772ffd9d9f817af1b8b7a73c9.nq.gz
    ├── 85d5a5936afb3ee28be9bf009a441d2bd3f80c60.nq.gz
    ├── 86228c86347fcb40b6147933ad098ccbbdf9b1ee.nq.gz
    ├── 862d45f1f335dbdbf1e69fbf1f71bf10c02c6460.nq.gz
    ├── 864ee89c44a19f84b294667e26231fa4c6746d58.nq.gz
    ├── 87b2b31236d75a3cd2c3146e8c99638b84b23100.nq.gz
    ├── 886e4f9cfa157606d3b5877604d24fe8cd8e5bdd.nq.gz
    ├── 88e5221b0c5eb82820d0e57da7dfb537ed785d60.nq.gz
    ├── 89c1e96f706c157f493c6ea8508f0cbeb9395600.nq.gz
    ├── 8a8510fb7a497c552b6e8455b7cf9ee1017b3547.nq.gz
    └── 8ad935c1658a19dc9f291fa8d67a6970ca77838e.nq.gz

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

[vwxyzjn/cleanrl](https://github.com/vwxyzjn/cleanrl)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
