# Repolex Knowledge Graph of cuthbertLab/music21

RDF knowledge graph data for [cuthbertLab/music21](https://github.com/cuthbertLab/music21), parsed by [repolex](https://repolex.ai).

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
rlex download cuthbertLab/music21
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fd9a14d30db266c83ed4b940b3d38775341423eb
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fd9a14d30db266c83ed4b940b3d38775341423eb
│           └── chunk-001.nq.gz
└── blob
    ├── 0026b77406af18f99dedd7cd39ae5a4f72a79f06.nq.gz
    ├── 00aa2a1b48d19e6277af3295fd70d93d4c570b83.nq.gz
    ├── 00e68756d939f8993f6875686dd52dfa90d8b0c8.nq.gz
    ├── 00eed5564102a0f975753897ec074b5fac07baa7.nq.gz
    ├── 00f183c8331ab2453d38937570b113f4200811d7.nq.gz
    ├── 025588b098dc01f5d13ff827242362c6f9b39a68.nq.gz
    ├── 03776a1eac7c6bcac5ae919782895ad2e07edf9d.nq.gz
    ├── 05156051fc1ae59786e3b17691749e1da8a12c3c.nq.gz
    ├── 056d7eab6b30585892c003c6b8bf93b8a2c670a5.nq.gz
    ├── 059c933e5af530681d1b06016a3307d7eb6a47e8.nq.gz
    ├── 05bdc466e6fc1405f87670f6455ff02c9463e331.nq.gz
    ├── 05be2730353b022d66f4359c17998eae5786b186.nq.gz
    ├── 05cf7aafdcc931a178b4e338e10aeeadf536c981.nq.gz
    ├── 0617a3c258769c06e7df899154dca9f70c978146.nq.gz
    ├── 07f0fe980a5e803caece3c505b21c6627f89c7c6.nq.gz
    ├── 0865945dcc3251abfbeba04a9d6d09d2e4a14497.nq.gz
    ├── 08c33980492ba9b1a06da48c40348f18ba5b6618.nq.gz
    ├── 09a9f71e54ea12fc235d444ebdec4cc2400981e5.nq.gz
    ├── 09f9b9e7c3d36ff1699704851b7a3e6589f7abcf.nq.gz
    ├── 0a34e9241d5c8796053fdf882d4ce2f99d6a0714.nq.gz
    ├── 0a8afe15869e02db2c7b7133d4a9d50c1b9fa568.nq.gz
    ├── 0abecb76b35b3571ec0b760e4995bbfd024c361e.nq.gz
    ├── 0bd9afee34e6acf8713ddea00b08ae72146a2ed0.nq.gz
    ├── 0c09964090d7e19d102ec79ff264f00d8fb6f3b4.nq.gz
    ├── 0c168fbbb34f8f22cfe1ff06b27d1a23a7829f61.nq.gz
    ├── 0c28e34fac54594cf4d48a5d50ba7a62323d8983.nq.gz
    ├── 0c408cf2af8a459f4c9a6563b4c2627751b0c206.nq.gz
    ├── 0c8b65e6f1ca5459ae57ac2dc4b8bb3cfa941c16.nq.gz
    ├── 0cf2572c533c5e68cb3b0df80fde68e0f0d13384.nq.gz
    ├── 0d0423506da0c7f5899e7726ccf88ce1e8a1dd16.nq.gz
    ├── 0d2307a8de9a0a22de2aed28e372efe131730f4b.nq.gz
    ├── 0eea0280ab34a5f22ed43f04a539c9acac4eb7c8.nq.gz
    ├── 0f6e344e317dd95cf9df5635b3034246df4adfe4.nq.gz
    ├── 1067d8dfd6fb38e5c767d5bbb92c6d1fb53cbe66.nq.gz
    ├── 10e41cec540242aead7a36d6e8429dd6d6fb7482.nq.gz
    ├── 113151e32cc898597cd6813f6e3efce8a1ec7e3c.nq.gz
    ├── 11428eeedbcfe7cbfcff85a425d9ad364659f88d.nq.gz
    ├── 1304461cf7ff7a910a42ba8eeb8d8f88707667ae.nq.gz
    ├── 138bec6a00b3c62758771728c7693270732e4f33.nq.gz
    ├── 1432bbd8f767955994c79030cf2f665de71c30aa.nq.gz
    ├── 14dea67e3d92ea75a97417f7ee4c1d86189e2351.nq.gz
    ├── 15132ed3c17204ad2629cf490c6c1384ff0eb9c3.nq.gz
    ├── 171976bf4930016c990a72ac232182074fb188db.nq.gz
    ├── 177801baf31aea91f9ee76864e2d9b64df983cb2.nq.gz
    ├── 17aa3d4b4cfc9a00125413e7e41d5ace46eeacaf.nq.gz
    ├── 1800a9d19df2003bede05704bd89493b229a1695.nq.gz
    ├── 18294f35291a6e8f1572800e926460bb5c71f8a8.nq.gz
    ├── 18c0fdaff6dd361a4cc9cda9a75f936555822e86.nq.gz
    ├── 18f0b82e00afd974d24b02548228ad310c2e6912.nq.gz
    ├── 1914116c8f381195ac1632684a2db0467b754aa5.nq.gz
    ├── 1a12026a6430c1e6e62e468f09de3229d008f11e.nq.gz
    ├── 1acabcedbcdc6c38cb5bbb43cc0c4d5187b35009.nq.gz
    ├── 1ae269eb5ccc8d3ae0d16732dc15b0cbb995f1b0.nq.gz
    ├── 1badb64a207c84e3ac83313d68ba8280b1645352.nq.gz
    ├── 1bd200356f46b782c5afd39284d05fa18015cb9b.nq.gz
    ├── 1bec4dab286b35b1864f20bd01c3cc9af32e41a4.nq.gz
    ├── 1c1daea81b73cf0a14dfffdcea799e9e9aa9a539.nq.gz
    ├── 1c9226759472ba598aa3193e43aabbb864fb54cb.nq.gz
    ├── 1dc63c85acef897b0bcfef8bb6d633e524d72d34.nq.gz
    ├── 1ddcc1781b7cad5afb109a9084b3e69a361efa4e.nq.gz
    ├── 1de7e82b4d38159e71657b1528fb6e67e807e749.nq.gz
    ├── 1ef0be5a37c44b1d9cdbc867ee587594ca25ea45.nq.gz
    ├── 21375d52d99c0497514a5c10b020a4741fdceaa0.nq.gz
    ├── 2283b1d4b9082c6f1b9c305ef355dc67419db0a3.nq.gz
    ├── 229b25bc44ef446b46432e74b31f09ada15ce217.nq.gz
    ├── 23043c11131b3938a4b35dda64d47dc91f3103bd.nq.gz
    ├── 233fb67e918aab95843428f76fdfe137b0fbe715.nq.gz
    ├── 23e019450f636647454a0c7f55ae9d7dd8730dee.nq.gz
    ├── 2410f15cf74b0a6ce56f88f4ca739afe9650b92c.nq.gz
    ├── 271173741871330af1917af40e7c4b0785346c65.nq.gz
    ├── 277a2eacb47820f72b77c3a61285788581ba3ac8.nq.gz
    ├── 2806ff046ae081bc3042fdde6f0eaa455a3958c3.nq.gz
    ├── 283afd1204f5280e605f3489362c55f55fcc7428.nq.gz
    ├── 283fbd6575667cb212d2e958fd707d37c7fad6e0.nq.gz
    ├── 28f4a720468dabc58850d9a8191cdd6db3be9041.nq.gz
    ├── 28f91362bf7f724c529b10a450e3448672df0fdf.nq.gz
    ├── 292ca46a98044c9977c2d01e5044ec82494549a0.nq.gz
    ├── 29b3fdcfc46dd351b831a216b79a0c8be7994e31.nq.gz
    ├── 2a109fb35a3ad05520f69ae20a43620fa24a6f2d.nq.gz
    ├── 2ac491a1c3ba0216092b92db4608c8096cc536c1.nq.gz
    ├── 2b8842d65c04ba257efe3ad4870fd313dd07cf19.nq.gz
    ├── 2d007c137101a240b4651f86befb70791c82dd04.nq.gz
    ├── 2ec4d100fee8680f32d6ece546bce92c15019223.nq.gz
    ├── 2ef8f5d6ba56c058d29051a1556e36efd331ee15.nq.gz
    ├── 2ef9c6136e106906a6379b403b2a22932098e277.nq.gz
    ├── 2f4188f6dc4aa8dd8860470635821737c5364aeb.nq.gz
    ├── 2f43fe3736e12d98932aeb6e6bc12e47e06c6b6b.nq.gz
    ├── 2f56501274c3b0bea212a9bc8a9c06ed5a896ceb.nq.gz
    ├── 2fd87141ea94c72a19a09f8704e1a9b9a93ec5ea.nq.gz
    ├── 315b340ce189286a1f70b54b5dbf0c62bf05a4e5.nq.gz
    ├── 31d87e70038f6e0268d2d4e65d5ad43bb3ba89c1.nq.gz
    ├── 330b9713bb101f76c6e34644725640f43419165c.nq.gz
    ├── 34000546c2df88af86ca958e51485b280c0a355e.nq.gz
    ├── 34c65ba5bd5df33f95ad307832abca450f968910.nq.gz
    ├── 35ac0a287995ad2fce3ec96a1a43092460c59b53.nq.gz
    ├── 36ab23545126ab8ed0cbb81499d8c9535f3d66a4.nq.gz
    ├── 36de5b156d69e2905c1998ce884f19976109a426.nq.gz
    ├── 36e4fb5688e0b6e358c23a3c1d6d0eb5035305fa.nq.gz
    ├── 3749941dc10e2afa33c1e7bc1a15347f9dd3c21e.nq.gz
    ├── 37747e86511001ec8f1df7b5df7bd39cef0781c5.nq.gz
    ├── 377748ae7e8b55f8053adc6219bcb39fe1899dad.nq.gz
    ├── 37f1a7ac71d7bd07b47b9db940596a4a5b12064f.nq.gz
    ├── 390a33063bbcf65186278431e9e411654954960e.nq.gz
    ├── 3a54615937df7bc7632f3f9c88e4fbd7ed3f7540.nq.gz
    ├── 3af8f3c635ef9b9c0448ac90aed7508d050501e8.nq.gz
    ├── 3b25b98b197647146792ea501b43dfc6c22f204a.nq.gz
    ├── 3b82ac96eec3ed5e4c099838611806e86906c54a.nq.gz
    ├── 3bc062ff78accbdabc4456aa5ce5332ef3dd7a84.nq.gz
    ├── 3c2e576a29cd183283ccfa297f1fce3cefdb4f90.nq.gz
    ├── 3c7c1bdd04aa7c9b09b32a790e28b9e3ac2032d0.nq.gz
    ├── 3cbb2450312591d5265f67fa55171de8218ed457.nq.gz
    ├── 3cce7b8b3460b62ca98ca749e412fa59075f229d.nq.gz
    ├── 3d215d2dd6f01abd553e8b8ab103a620969cd789.nq.gz
    ├── 3d98f6c3ec6ea8d31db3cc159e40491c11bd7d7e.nq.gz
    ├── 3df9f0cf6f4f4a6cd18638b1ffe03d86c6e3e43e.nq.gz
    ├── 3e2a74a43c4d33c8f4aaa13ce170b2b39beded75.nq.gz
    ├── 3ed9664b0a2b17d02d4a276797f57b061ae9cecc.nq.gz
    ├── 3edf5b0f5ac761b60092a43117d2eb4b764a5f5e.nq.gz
    ├── 3f84d4e61dee320e4dab6579e45690a9af9f0e61.nq.gz
    ├── 40bbbc64b3490e770c0a961516598089de447d69.nq.gz
    ├── 41372206c09a0ca0a4181cd7b75d53815602841e.nq.gz
    ├── 418b7e7e690998f235e5030f37bb2f0eb74858bb.nq.gz
    ├── 41c30d8ea09be6900e53da387e9f6311d22e9de5.nq.gz
    ├── 41ddca6d38110b5260d27a636c7a651e869e9e8b.nq.gz
    ├── 43155730aee90b0ad7f32f9e7d0a202c77648750.nq.gz
    ├── 44a198ad262676e508fb7de7c2d2ba32b29b1e58.nq.gz
    ├── 466ccca6d0ea7bb70c9d674450f7ed224d524bb9.nq.gz
    ├── 468273a3cd4b1ef886f8c80d26e9747164d70560.nq.gz
    ├── 468d6809d3b46991762964a5c7006c8af012c5d6.nq.gz
    ├── 46ae101b3e01e6d1a2a5e79f6a289b97375b11e7.nq.gz
    ├── 474226e321a68a10c2edf874ab6a335ac230d338.nq.gz
    ├── 47508b775b38178b8ded6f566a2a5b5faa57a188.nq.gz
    ├── 4783f7eabaf5c350fabf74f8343fa4886e3cabdb.nq.gz
    ├── 47c8acc59b815478a7701d9885ab1973ec784004.nq.gz
    ├── 48a027f6465f875c10d1c5afb5b7bd2ed26c7150.nq.gz
    ├── 49550bf5358b6d475062b18b3080988b29388159.nq.gz
    ├── 49f91fe2f7acde3b119d831ad1fbecaffb87da67.nq.gz
    ├── 4ac928a4e41d3596190d52e47aff15d644b0d86f.nq.gz
    ├── 4b8458d9a0ad482549e932571c62ac883b333e1c.nq.gz
    ├── 4b9553fdb8277ab69d3df306ce621acd7b07a11f.nq.gz
    ├── 4c75eb64e5da893e95e85f5b5d26557b17eabd1d.nq.gz
    ├── 4e618e3461127011ad13d912b1294b3368691dec.nq.gz
    ├── 4f033e7af22f86646eae7f60306bb657047342c9.nq.gz
    ├── 4f944bf8ad39943bccb505e0cfa4dd7b1b866377.nq.gz
    ├── 4fa6552411762ce72cf8e973fe9be06a9852e17c.nq.gz
    ├── 504260af84f9d11e00da16e9f3e0452c21c0a97e.nq.gz
    ├── 504fc47db7835a2bba36b975a3edd5ea54997c27.nq.gz
    ├── 50a9a86e6a01dcb517bdd24d91ae0bc13ad2bbe7.nq.gz
    ├── 50b65214a54b8c2703295cb7e4390173642f22d6.nq.gz
    ├── 51884bd79a9518cc9da99e8f45555c1bdc972709.nq.gz
    ├── 52b2c14d668dffaa56d12adddf4e5f9aea2381fd.nq.gz
    ├── 533f18f99ebabc512d35b31e206812a5c8316da6.nq.gz
    ├── 53b72893cdd43796d7333add22755f684dcbe92f.nq.gz
    ├── 53dda5f8d3438d315707a3ff98404019fadd49ec.nq.gz
    ├── 549105a8782988b5d4142387866855c0e8bf5596.nq.gz
    ├── 54e773ffd12e363eac11b877780805bde6aa2650.nq.gz
    ├── 5510caa9829469ecfdad402796ca6a27da3246f1.nq.gz
    ├── 55b73ca1b2a3c466017dcde8361a86e52e63856f.nq.gz
    ├── 55e420224fc78a7723b363b695704d1ce55dd0e0.nq.gz
    ├── 56a4310a36ed38ed60ffd1fd88f5ac8ff4c00acd.nq.gz
    ├── 57c19b36fb370fec1fa14ad7bf11f9c183e90c5f.nq.gz
    ├── 57c5ad25458ca73d702caf5a5267659cb402b7a3.nq.gz
    ├── 57da2f87e94f12bfc9a21fbcdfbe089eccfdbbd7.nq.gz
    ├── 5849a792b675ecb8ccb2c3cd7a118d75927f0be2.nq.gz
    ├── 58868f94c8f81daa9b76ed81e21c2de635912c98.nq.gz
    ├── 5b24629a5dfb1722929f5bdf417f70a65bb5bd02.nq.gz
    ├── 5b8caedd7c79864a0fac65ee11f99a657855ecb6.nq.gz
    ├── 5dd5edb384cf170d13c3f782bb274922ba04c249.nq.gz
    ├── 5de13e635800051554c69093b9925ff3173420e3.nq.gz
    ├── 5e24f8e866c1ad66d2dab5b4833c735cf95b1b5f.nq.gz
    ├── 5e462d4e8666b952db339129ea43264f0886e382.nq.gz
    ├── 5f7be1716674e991339a726295b1c8278ba0c5fb.nq.gz
    ├── 5f8dd20293c2c8227209e7a476a53f7da1548dc5.nq.gz
    ├── 5f8dd95858058c9fd5d2a57a5b51b3bdbd1500ea.nq.gz
    ├── 605c5fa8b58384c9d901a53a9b3022bf02a70101.nq.gz
    ├── 6083cf83d08cbdadfecc0ab213aee6dff7238b57.nq.gz
    ├── 608fc7d98bc14c4934464cb6901631f27c735fd4.nq.gz
    ├── 60de9e7f5430aecfc4a50c8d8a1ef71be69461f1.nq.gz
    ├── 60f5fb5a5a2505ae3ed3e0a6b08147fb714fb207.nq.gz
    ├── 632f0d0020b1faede43b5d206a3ca24f3dd3aa37.nq.gz
    ├── 6332a0300ae941b6b6010af7b9a1fc4675e6f903.nq.gz
    ├── 6367f19190bb534c0e31d43b2f818bff120e426c.nq.gz
    ├── 6416e02076bb6d3acd991598a49357043ac28e6c.nq.gz
    ├── 65591b6da13f162268a51d782bd90c20528ea9c9.nq.gz
    ├── 65d21e1862c297deaea51e18b1a8b9bce212ef89.nq.gz
    ├── 667d07f0a56281dda72d4aed3289120786caca0f.nq.gz
    ├── 67185675c842dfbb7033e8f61d0600c4bd745138.nq.gz
    ├── 67e752622570a82450e35600468b38a635dc22dd.nq.gz
    ├── 6a856c0a172cab36f106dc2cd3de8d22aa64bd1b.nq.gz
    ├── 6ad09a4e34d30ec765abb99705c82cdba77986de.nq.gz
    ├── 6ad69218f17ff0db08aeb97ea7f25eb71a18a73f.nq.gz
    ├── 6bb4c1e18050c8487049cad397aab6d33787570f.nq.gz
    ├── 6e353edc562a682ca74922d2a8b16783cf3c225a.nq.gz
    ├── 6f967c2c94f2b27af0f11f1008a604e49d224384.nq.gz
    ├── 70469cc6517788906ae2f2d8017569573ac58df4.nq.gz
    ├── 70557aff62e3eec9b1c31c936f6499f74d4c8196.nq.gz
    ├── 71234a3ea68fc8eda8730ecaef8b89f7229c6007.nq.gz
    └── 71540b913e44892b7f1b477beb30e429c19f2127.nq.gz

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

[cuthbertLab/music21](https://github.com/cuthbertLab/music21)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
