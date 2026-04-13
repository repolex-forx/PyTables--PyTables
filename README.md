# Repolex Knowledge Graph of PyTables/PyTables

RDF knowledge graph data for [PyTables/PyTables](https://github.com/PyTables/PyTables), parsed by [repolex](https://repolex.ai).

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
lexq download PyTables/PyTables
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7361a059d92d3cbe8a45850dbe4452208af120f7
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 7361a059d92d3cbe8a45850dbe4452208af120f7.nq.gz
│   └── repolex
│       └── 7361a059d92d3cbe8a45850dbe4452208af120f7
│           └── chunk-001.nq.gz
└── blob
    ├── 003e197917c2c2a8e18bb32c9c4ba753e1f64659.nq.gz
    ├── 005577f5375e44426951859872705236fef377b3.nq.gz
    ├── 010aed032d80c636bf2fe76263d92bf8e98ba787.nq.gz
    ├── 020412e6fbe19da98445632be83de009d4b5e6fb.nq.gz
    ├── 021139dbe0c763309850c09fa80ca7cac59c3e0d.nq.gz
    ├── 02e48a1ed5ca487efbdf8ac213ab4323bc43482c.nq.gz
    ├── 030b0bcfc44f91229c70d2d183e6bdf20195ad20.nq.gz
    ├── 033d4b83ae96bde35cce8f5ad597a628f76cc483.nq.gz
    ├── 03bf789843b6a514f2fdf7d50ad401128ad92276.nq.gz
    ├── 03d827ff3109d6065ffc9d94dd717890f53d58c2.nq.gz
    ├── 04aac7b29453725a40b66b042181f493f4bba91a.nq.gz
    ├── 04bdb6d3c2a8d79c4617cf0d899cbc43a28d7404.nq.gz
    ├── 04cee3dec34ba2bef41320b46c9ce41c67eed847.nq.gz
    ├── 04d926cfaa17717f86f2ff6fe349bb1d12f6401c.nq.gz
    ├── 072ade1c2e359e457bb165629e7de3c73a6d65b4.nq.gz
    ├── 0754e548d2830d618684f32b323ea812c803046a.nq.gz
    ├── 076957fce25245ae837fde3b015c789daa099293.nq.gz
    ├── 0892e7c0f4060152c3249c660a35385551889a97.nq.gz
    ├── 089423cf2f369282cae2a866f6457526545ea45b.nq.gz
    ├── 0a1d795f33c1213528220a18d20a21dc9ac15997.nq.gz
    ├── 0a8e99b369fa56afd9dbfb8a810129b0ccf7ab03.nq.gz
    ├── 0ad46169c2fddf222bd669d8c27061059f7283de.nq.gz
    ├── 0c3218f3e381d67c7b8d4e97feb00bee34ba3b48.nq.gz
    ├── 0c3519af55481a2659f4dd94080220da66e52ee9.nq.gz
    ├── 0da84e75c103bcac026a6409d9396a85acf0ed2e.nq.gz
    ├── 0ec9ca3465e2cc6a637d69c04fb24d00800c321f.nq.gz
    ├── 0ed390169163afe6b1387d030d747023947dcf7f.nq.gz
    ├── 0eeab8d09bf5ead146f688a3a90ff4d13ffc1768.nq.gz
    ├── 100f25b235869435c8f6a634cbb79abd6cefb0db.nq.gz
    ├── 10107e4d1e67aed3e18061edbdf806c63a986f9c.nq.gz
    ├── 10630ff6796a8d4d80c51c1100d1e4ffffa70b57.nq.gz
    ├── 1129f34a7fde5bc368dca09b4d0fa79d31e867f3.nq.gz
    ├── 113e3ef411d9ac35d06f2c6a3f9285ac26b5f9dc.nq.gz
    ├── 11b3acc82c635b492efdc3c003d12ab7020426a9.nq.gz
    ├── 11d168d1c0a0f2b8dfc9579dda2e6f9c41580378.nq.gz
    ├── 12762045779fd44c7b2d8c46dd3deb29f0465dbd.nq.gz
    ├── 12fc730a5e7934d2a0c06f3c5a627a78c992f06b.nq.gz
    ├── 139885a6e2f1edbfe13527c5ebffe195b541312b.nq.gz
    ├── 1446d342a267e0bf28dc926efd514a2b19de3a45.nq.gz
    ├── 146f5d59e9294a806684f0090c54abb9e6ff4849.nq.gz
    ├── 147a3e865b69b92c6df5ac9468d4a308857361a1.nq.gz
    ├── 14907e78e623d9b7db71f724f903575976d874bd.nq.gz
    ├── 14f7380f827b6bf2bffb9e74a668278526a0bc6d.nq.gz
    ├── 1657286edb315a4122153b7f2c19b9715f06c39f.nq.gz
    ├── 166f45f8438acd0fb13a3f886bb743782dfa97b1.nq.gz
    ├── 17a20f803efa7f9cc7cb78a44a21d6f338c64e71.nq.gz
    ├── 17c33edced32e7ff67d59e1075382a27a40e198d.nq.gz
    ├── 17dcf26399420008aeea0aba8a0d84f2827db714.nq.gz
    ├── 19cd400760d405d91e0158350aca5a9b3b9a3c0e.nq.gz
    ├── 1a25bfac8e1142a599cecb1ad51bb2057ab9fdc1.nq.gz
    ├── 1abef2867ff236ffad3f01570fbf890fce3019c6.nq.gz
    ├── 1b432a812ddcc162d796ea0108106f984e8bd925.nq.gz
    ├── 1b7353188efb20893b4b5b3a20add6c4de85e845.nq.gz
    ├── 1bb23db5949ee4cd4ddf35d9b1ab7488c3016be4.nq.gz
    ├── 1bcff0e823e3ba2f30fffe0348340e4063901299.nq.gz
    ├── 1cd1d33692371a9d53b400c6b90cd15597d9d504.nq.gz
    ├── 1cf02f76c87e3fc7a0864aa1b11282476e0b33e0.nq.gz
    ├── 1d3e66fd7ee474a114faaca1b408a3aa8650f25e.nq.gz
    ├── 1d4caec2741005f915dfd0f101d0c25e9c6562b9.nq.gz
    ├── 1d63691abc576ba6369e9c69adf262ba9c274d99.nq.gz
    ├── 1d6748c5bcddebc00515857ba81acb1b37c8d3bf.nq.gz
    ├── 1de849dcf10cbaef86f7e23065df06cb66740551.nq.gz
    ├── 1def0a53647eee283ac59a3059be696108a46de2.nq.gz
    ├── 1def780cc5b1ce5c2bda9a681ba642578c0c0eb1.nq.gz
    ├── 1e207ac9e79ecb599c9e11582b63a823240faa3b.nq.gz
    ├── 1e7638f086a955653b0bdeb39b000c8bca2c6d20.nq.gz
    ├── 1f76dde915a7e97ff71ac735137010cb3f0266df.nq.gz
    ├── 20d1850abab8a66dce93c4bcc9825e1a413773f4.nq.gz
    ├── 21208e372c5c4647dd350abb578cb9d4bb2bf55f.nq.gz
    ├── 2196c9a623891d259db5a3af602ff7b9bedb43f8.nq.gz
    ├── 21c143e0780114531daf29c67383c3c384b39922.nq.gz
    ├── 22a2e76f394efabf244225e3e7d212cd340b49a0.nq.gz
    ├── 23323bba03ebd22c16312dc66cef62a91f35af29.nq.gz
    ├── 233a925dacc12de6dcac89581dcebdc785e871b8.nq.gz
    ├── 23e0afe983ba96e326c6da2fd1e3dba7396bd558.nq.gz
    ├── 255d1bc29f7f7efd3a2dd598a031520fb8981356.nq.gz
    ├── 261e18ed5a540b68eeb2a52ced5ea1fa98743d1f.nq.gz
    ├── 2683ea307cea39697a5be297f707ad1445f7b776.nq.gz
    ├── 26a89682f3520b1f81514815c6dba699e82857e7.nq.gz
    ├── 26fbe51c33a08b14b66c73107f4afde11b6a10f2.nq.gz
    ├── 2725729065125cc5022d4b511086d5dbca0b0639.nq.gz
    ├── 274302565769697673ab9de4ef3221e2e78684a6.nq.gz
    ├── 2765bd9d5b5888af036d61f6d141a86caa795e79.nq.gz
    ├── 27bbc430ff3173f71259323c035102e0e8aa2e8b.nq.gz
    ├── 28e36c004e473a77c77fdd28e5e86bfe553e00ce.nq.gz
    ├── 28eccfdc2a5e0b30aa71d611888685d8ecbb8f69.nq.gz
    ├── 2981b080ae127f23c7edc6d4014791b95485aa80.nq.gz
    ├── 2996021a03a5f58157ce21b26a5096a9739e48df.nq.gz
    ├── 2a7efcb01cb8451ab0d2b9b966f49108c320938d.nq.gz
    ├── 2ae2f28c2e6bce374ab8d4576a43eeec9dcda206.nq.gz
    ├── 2b5a3947694e2835c19a4c258d605f68629e7c54.nq.gz
    ├── 2b994a1b45453a180fd8616cb098123895a5d587.nq.gz
    ├── 2cab82ea3368fda6a9e1e128db1c0b803261d309.nq.gz
    ├── 2caff67129efafccebbff7e0be09abb69c253071.nq.gz
    ├── 2e2331a46aa70a08cddb34a19258e74c5b10b061.nq.gz
    ├── 2ed9e1d592e8fa6ce7249b75a9a2fad9482c3534.nq.gz
    ├── 30bca01da7310a22c902799b582680392ae87152.nq.gz
    ├── 30f831a8949772c92615fff4455ffa12fb8d4099.nq.gz
    ├── 31447249c21db226fbc9bb86e2c9fd22d429d8ed.nq.gz
    ├── 327f5a7fc608fe42764ef274b40aa480fafeb274.nq.gz
    ├── 329a7b3b379a7b390546405681af26536755287b.nq.gz
    ├── 32a59d3ce1b9321cdb6a69e21ea98b9829bdda89.nq.gz
    ├── 32cda28d16dd6dbb022ef68f09e5e538e791e8c1.nq.gz
    ├── 33dc599bb306329227ea377d575fb4290fef7f13.nq.gz
    ├── 34445da8db65068fb769a5bbeb9e5d556a56502f.nq.gz
    ├── 346cd4662c8194dfc4046a10f817832b90dd3aed.nq.gz
    ├── 346e2147565511c178f06777ed33fd3565992260.nq.gz
    ├── 34a0a01abfbdc9657831e933189f31605e4c6206.nq.gz
    ├── 34a163fee48dcc7292346b9ff2de32cf6975fa95.nq.gz
    ├── 3599269e30cebaac2dd5474a4409e8339b2d81c3.nq.gz
    ├── 363447d5c7846ab50287aba5be63685e018636ba.nq.gz
    ├── 3687529954b3d265f0735709f9d5d29322439f62.nq.gz
    ├── 36b17612f79a2efda51d539812ef83a04c1722a5.nq.gz
    ├── 37b97dceaf9080a8b5e3fff2d33c3440fa4b65e0.nq.gz
    ├── 38ba380b394035d28590173cbc5ad4e1985f94c8.nq.gz
    ├── 39abb79c3c0d4ebb1820108ee5ac481c543b493a.nq.gz
    ├── 39eec8291d928f8c8b15e4e00ea5def4296c048a.nq.gz
    ├── 3a0f215bcfc41eb3c25c6f83164781e447b883cc.nq.gz
    ├── 3adf16a08460921648a864cb96aab321e5fce304.nq.gz
    ├── 3b280206bd2ec45b7289667461f765245e0ef088.nq.gz
    ├── 3cb7ffa4038c0b6b05d39a983bbb2d7a1789e967.nq.gz
    ├── 3cfe5b642e21727bfd8a66ed1924163022991fca.nq.gz
    ├── 3dddda18fe5917403cf248cd839cc7b11a06b807.nq.gz
    ├── 3f3621f9113ab5e661869dd1202d1bf965c14662.nq.gz
    ├── 402c5bba6065adf0ff9b34f636206e889a513839.nq.gz
    ├── 4067b7d3d7d0428118469c525580c6d70b36b5ee.nq.gz
    ├── 414ef1dc892ebb14e7b79fbda48e0584d3b69ca9.nq.gz
    ├── 41b917bccc87ccc18b91fc59358536ea24db70b7.nq.gz
    ├── 41fbf9aa1ec04788cd3f9f5caa49e4d6f6805830.nq.gz
    ├── 421d1130d73be63aed3e02887fe8c34b0482e615.nq.gz
    ├── 42e249e71f1d8175dd36cd3040d4ddadc07729e0.nq.gz
    ├── 43fba5b5a2f9b7881b93fe1944849ca4773a5728.nq.gz
    ├── 44d006f4886737ce319dbc344a33ee84237f80bc.nq.gz
    ├── 458030a0851e3ef7e0a121c54d5daa8638777c4d.nq.gz
    ├── 45b17552f64a6ec0dcf774b3aad180d8635d3def.nq.gz
    ├── 45d668748660922c88117ab162ca43db2c02f6e4.nq.gz
    ├── 463e4471e3fd0d203fd4206debc31d2c36023cfe.nq.gz
    ├── 464394c308a2eba86066e0e061f4b1e8a9de706b.nq.gz
    ├── 46c70282e0c6cd58b04bc489c79a57a8b6a3e9be.nq.gz
    ├── 48bc78464d759a15bbda801686683fe28e76ec99.nq.gz
    ├── 491489241bda2bfc2af029f353318fd235343f8b.nq.gz
    ├── 494546799ff5a91b33f9e076fd90bd6e94e84b43.nq.gz
    ├── 4947a9f4f448d41b8b542c087dab23902adde11b.nq.gz
    ├── 496e176b39053acab88ece3a0fe5fbe7764dd19e.nq.gz
    ├── 49876ef58b019993e349e633a99186ffe2b3d5c0.nq.gz
    ├── 4a3399b29344addb429498ea24e21d8f3aae53c2.nq.gz
    ├── 4a4dda037fa6fc5b1ce669a89cc759cba29095d3.nq.gz
    ├── 4a77a243ee70e93ae15d942cb8b47f852906a5e3.nq.gz
    ├── 4b1e8650c46a93121605a76a0cdcdb9102ada9e1.nq.gz
    ├── 4c5860a05cecf6a90cfe64e17c7e78ec08182ffd.nq.gz
    ├── 4c5a03dc6314604a58c8ca6aa64d50ef64fb8f58.nq.gz
    ├── 4cb0e9a3f2c9d6d927ee33e11cf29785f337cf25.nq.gz
    ├── 4d83525022dec1795ff0d469ae5cfa7cf9d1d23d.nq.gz
    ├── 4d928bc812e03b196eaaa8ec83371718c69287d2.nq.gz
    ├── 4e3e1cf100a27f4114647a912c9bc093b074782a.nq.gz
    ├── 4e8fe0d7aa9b1c4dde7c446cb6b5c903d747f544.nq.gz
    ├── 4eebf98503400a7ded7aa69a03b39e556a02dbad.nq.gz
    ├── 4f459f4ca0ed7b557c5197c8fafbeb7492e417ae.nq.gz
    ├── 4fbd277294bfc478e6bfdb8bf6ae45ed9a40ee5e.nq.gz
    ├── 4fbf2fe87ca74826cc619e8416e34f45931f4097.nq.gz
    ├── 521f7a2f5a2724885ea592abff9542d1ae74b803.nq.gz
    ├── 5253468223cccbbb8f5ae03ae7a937dd1710ad30.nq.gz
    ├── 52713233c4ea2915959c45c7fb916d16506d8c80.nq.gz
    ├── 52720e9ca577e57fe39ce54f39159408e128538f.nq.gz
    ├── 540109597cc174d55d600d8e4d6bb60b7ae74fc4.nq.gz
    ├── 54126de23c56fdafc8ed5baebfd8da6f1ccdcf8c.nq.gz
    ├── 54169b2ba85c371d13475a63329b371eee911b90.nq.gz
    ├── 542e65ba61eb6cf9b00b4d7e6af0ec69a4b9b384.nq.gz
    ├── 5471bc7cc162366b2886192fd7b928fe0f68ef09.nq.gz
    ├── 54c12f50b52faa2b1a170059518b41e775b7d18c.nq.gz
    ├── 54f5ecbcb5ea2bd5508f64ea04f209b2beb9364c.nq.gz
    ├── 5592f8c2beafe28a951830eed23c350fd77afae9.nq.gz
    ├── 5599e16303898df17c7a116e4d37d26eb0debcff.nq.gz
    ├── 55ddd1f0cc1a1ac43dd7b23d33b737d97d732712.nq.gz
    ├── 56818dfb621be0df9aed617a92a6f50561739a91.nq.gz
    ├── 56992e22e811780fc2d1b5de044b18071ea428cd.nq.gz
    ├── 56f333e0d0175a47d5772dfab0d30ab87106d049.nq.gz
    ├── 574bd102628046b9136b3218317aa5f90ec3732d.nq.gz
    ├── 58d940faeb279b86ef8ce62f9ac8f65ae8476e8d.nq.gz
    ├── 591300ce762a97c9ec5d4241ff7cb8b1d73be899.nq.gz
    ├── 591771201eb4c11ebe47498650b6788db0115c0b.nq.gz
    ├── 5a342e2b5a2b7c3f6c9cc3250eabc8a0007080ed.nq.gz
    ├── 5b6d5bf5fc9fab0df1ddeda180e463e81077db7a.nq.gz
    ├── 5b92f60380a339185dac34adb3113bd0c1aa7284.nq.gz
    ├── 5c2de2efd267ed65b901befdb546f07d9d8718a5.nq.gz
    ├── 5c3121751bd4b09ee3f0b931917bda38a03537a0.nq.gz
    ├── 5c6aa08be19c88933d88c0d7968f0d2310298850.nq.gz
    ├── 5ce30e9684afa2162cb1f75b9d1c28155bc18816.nq.gz
    ├── 5d10d2cc51827a2b30b7d086ac9774e0db689538.nq.gz
    ├── 5d74f5ce5d7e29ea64fc6f44db3158d97cad4a34.nq.gz
    ├── 5e2a70be46223bf46b5a4def479c7f4f8cfb991d.nq.gz
    ├── 5ee3bd55c755a0e1d84983bddffe25374476b902.nq.gz
    ├── 5f01fd86cb2ecb8e98b3bd3cfbaf508e37f9b25f.nq.gz
    ├── 5f24e12120039eacb6a5226b74446835a8aecd28.nq.gz
    ├── 5f3d162fb20509bc54b41574f534a148ad27e271.nq.gz
    ├── 60287036dd77deaa0715cd27e3296eea9aa4f7ca.nq.gz
    └── 61292ebb03dbe719d61fbb428afd8867b4001507.nq.gz

8 directories, 200 files
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

[PyTables/PyTables](https://github.com/PyTables/PyTables)

---
*Parsed on 2026-04-13 by [repolex](https://repolex.ai)*
