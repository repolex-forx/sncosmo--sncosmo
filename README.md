# Repolex Knowledge Graph of sncosmo/sncosmo

RDF knowledge graph data for [sncosmo/sncosmo](https://github.com/sncosmo/sncosmo), parsed by [repolex](https://repolex.ai).

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
rlex download sncosmo/sncosmo
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a42c93634a472b2c80878cebc43976aadaff6d2b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a42c93634a472b2c80878cebc43976aadaff6d2b
│           └── chunk-001.nq.gz
├── blob
│   ├── 002e04b14481f8066adfaf39ca592932ab371e9d.nq.gz
│   ├── 0225c4bcc7cd2a3136fb55b3917e0bd902f0a6fd.nq.gz
│   ├── 028bd5727a2ffc090d35c18110ae87d387962ee0.nq.gz
│   ├── 02a9863401f11745c3d5c2a431e193f72603cdb8.nq.gz
│   ├── 040762888b9b4362df93fe7b20738a37936ad2fd.nq.gz
│   ├── 0675e465d5296a321541d398d3eac3c50c3c9eb1.nq.gz
│   ├── 07fed1492844398d25e0336edee720f948785f9b.nq.gz
│   ├── 0873bee82e80abca54c46045c30ac53ab84d1011.nq.gz
│   ├── 08b27d183bacec290366542b92297a172edc70d2.nq.gz
│   ├── 0a3f74daba5a1756cce363779665b17b228412fb.nq.gz
│   ├── 0b44a9405292dc9795f35587f559e7d8e5d4b356.nq.gz
│   ├── 0bd4e6ab5b37adf39634d6f4e990e2c15b1ca013.nq.gz
│   ├── 0f59b5b6b5fe1ae0024fc7c1ea94ba0c391e5237.nq.gz
│   ├── 115394954597e0c4dd14cc03eaa94b17c93c67c9.nq.gz
│   ├── 11d63bded9b4dc6fb9f0a47381b71919bd6c21cd.nq.gz
│   ├── 1289fa655ffce43a1498686f0c4eec1ab9a2c81f.nq.gz
│   ├── 15e127d39e8e80f67dd21b605084853f7bc1d7e4.nq.gz
│   ├── 16ff217b038d47ec8f78af1bdc577537b9921e77.nq.gz
│   ├── 19d282c1a5ebbce747fbbb6eec732e73b203fa88.nq.gz
│   ├── 1ac93d06d009667c15e59440738de5c777ac290a.nq.gz
│   ├── 1d771916066afb713d119993236043e7a7cc5abc.nq.gz
│   ├── 21b8c6844beed1a3ac7aa9c1cef3ca4e6a60e479.nq.gz
│   ├── 24eec3d1d6c44d25a406b8ccbe0eb94a4da40343.nq.gz
│   ├── 27385bdddb2c78ad6051119bb346216b60c9888e.nq.gz
│   ├── 285f364eecea0fda805167aca0fbad325bade6c5.nq.gz
│   ├── 28becea6a217ac6fe3621f522069c5aca96be7e4.nq.gz
│   ├── 2b0db804d499296f2735f05d4bf77542a017b769.nq.gz
│   ├── 2dd6d09e8c5461036404188aa0c84cdfd5b77ee9.nq.gz
│   ├── 2ec2b48f4c51773f8036977414e008a074737a82.nq.gz
│   ├── 2f08e2a6a854eb9481bbbb252b74827f711860e6.nq.gz
│   ├── 2fab3c78ada3162e38b233563f6159c79be81334.nq.gz
│   ├── 2fc64ee830d599b9b990c7aaa5a3f2f6c6598ef0.nq.gz
│   ├── 31bb4c54626b5f4b989a87158b63bbaf52a44f90.nq.gz
│   ├── 36d64352edf575588d7f1e6c77fe3a299b5f16c6.nq.gz
│   ├── 3bd4cd2f60532b47cbfc6e6408de69e3d214c636.nq.gz
│   ├── 3c73982a2dd63f79df7f28a768bb80b543bbd755.nq.gz
│   ├── 3ddfb6cc976801402acc497bd41ae6b01e09bd9e.nq.gz
│   ├── 3f008ed690e9fa85da02181a60edaa2734c291d9.nq.gz
│   ├── 3f68287109d3ffd3a10949be05bc257a00a92fdf.nq.gz
│   ├── 41f7e4bfc4c0740568d6cc268d2e19933e224057.nq.gz
│   ├── 4201876db2598b0bd40dcf1c25e377478e688119.nq.gz
│   ├── 429b3d13681968292eda4f090113dda61aa5270a.nq.gz
│   ├── 43d1e24f5b2f4925fcc7aeb761c892ab252bf08f.nq.gz
│   ├── 43e5de1182606387dfa4a439aa121a1074a67e86.nq.gz
│   ├── 44ff9c815bf20dbd5352dafd27ba823a5ee691c4.nq.gz
│   ├── 496c27b0e1703b47a200bf9713c16d1d41887826.nq.gz
│   ├── 4e38dddd22b122c661c63111ce24fea9d727b90a.nq.gz
│   ├── 4e46669f8663f90587b1b89045fde3e7458ddfce.nq.gz
│   ├── 4e7241415f9bbbf3484e3f4af68123828bbc860a.nq.gz
│   ├── 50fdfe873ef9a3955a6dd251c4da07e80c966d66.nq.gz
│   ├── 5329f6ae2af7e8a956397083d190e3006d6c166a.nq.gz
│   ├── 53eabf296aaf7f9857e29d7635d195a1cfa6d13b.nq.gz
│   ├── 5674dcb301190b0f78d484c975c351dc693e9ad4.nq.gz
│   ├── 57dc8b258d09040bc703d651876fec4be99fd18b.nq.gz
│   ├── 58e2536a56832750a29fbc4da543fabd5be3fdca.nq.gz
│   ├── 5a2c707bf4a2b43b3d2949a3dc81c2965e4e2513.nq.gz
│   ├── 5b70a97152e7e7a8ed8d78aa350f936e1aa1fe22.nq.gz
│   ├── 5ba7631dba2704a1775f2ed98a5a042fa24fd3a1.nq.gz
│   ├── 5c09f9ad0387691eeb15ddb66b3b0cd9cbc09e2a.nq.gz
│   ├── 5fa0b72c0a70572d2b3861c2632e684c5f1a0b8d.nq.gz
│   ├── 6006799f588343459ca894a31fcc30ad46db3a95.nq.gz
│   ├── 629df9cd1ebbbbaa6f10152e145cf06bdd336538.nq.gz
│   ├── 66bf348c67a0dabce25f9b0b99ad91eca52835ac.nq.gz
│   ├── 67ed76a8675a0fe5c98d789dc393a83f713ef2ba.nq.gz
│   ├── 68d5f86872dc646b8c083ceb05339397d501e5a4.nq.gz
│   ├── 69666c4bd20a1daba407778e6fb2fc7015d47fc8.nq.gz
│   ├── 6d616c6beacc8b2f12c7f764b7c835bcf368360a.nq.gz
│   ├── 6dd6da4acd3709911e9de97c626b0bca762f8915.nq.gz
│   ├── 6df22f273f84c47b35a89544e7beecae44fb098d.nq.gz
│   ├── 6e13daf0a1de83fb90886b172e31044e966f30bc.nq.gz
│   ├── 6eaffcbc66ed6a6d7b8ad79802e10d761f029844.nq.gz
│   ├── 71f265bfc4bd5f3a1103d30483ecfcd18c59d110.nq.gz
│   ├── 7319347d61d27534b7ef2b4c15404d37fb9584a5.nq.gz
│   ├── 73c04409e3df667df1584783089833f624a30a07.nq.gz
│   ├── 7461f7e9801fc6b56ac18b59fa4ff4278cf47e51.nq.gz
│   ├── 757743ad081601424c92b4df95fddf58da7665f4.nq.gz
│   ├── 760aa5a8c5298404f7b9022541426076bfa20a3b.nq.gz
│   ├── 76fd7e1eeceda3a334d4540a9743ae70d58a44b1.nq.gz
│   ├── 78dae09bb521ed0f409ec84c4b8fc29a2e9ff9f5.nq.gz
│   ├── 7a355b1255e3c3bb1dce93ebaef65cf608eb4474.nq.gz
│   ├── 7d2f7790678155cc6183f6ad875884a60cfc8844.nq.gz
│   ├── 7da014721e354200658dbeb41e6fed2a25efde5a.nq.gz
│   ├── 7e9642440d7cacdab2a792c548aaf443aa39e693.nq.gz
│   ├── 7f8e1300809360322cf78950e0ede86b33356024.nq.gz
│   ├── 863609db8406f53321584ace4a1481351459e7c9.nq.gz
│   ├── 89e21800a6e90c84e66eb641ead33b321a4234c2.nq.gz
│   ├── 8d3f0a72040c943ec0b6af6e88cca5a1560d2c14.nq.gz
│   ├── 8dacf3944a44e428d223a3b64eefff1a2d3e5966.nq.gz
│   ├── 8f20c2ce53fe930fd4170c5916e0c19a589adf19.nq.gz
│   ├── 8f2316a82170a098453e3f960c80951bf9f40fea.nq.gz
│   ├── 90f76abb4748bd0735b86754829e25782a8aa566.nq.gz
│   ├── 93dfe92b9c98e009c2f75b6477817411d3a15585.nq.gz
│   ├── 94a0c4b29789ee86f071b5e409b74f0dd4ef67df.nq.gz
│   ├── 97bf261c42e3a8431f8db27069aab5bc16257dae.nq.gz
│   ├── 9a10322f8a4313cc02fac5af71e490c97eff0f2f.nq.gz
│   ├── 9a2b016e8be145f80a4245d05c6c9994c6ce5f39.nq.gz
│   ├── 9b66c1b7674c2c6dd66364e779135789e0bab882.nq.gz
│   ├── 9d48a3428fa1c0176f20c5f730692b0a005be373.nq.gz
│   ├── 9e9479574faa53b74cae211d5ef79b1e4a268d17.nq.gz
│   ├── 9f76e2d2a2f00af4c96cf849aafe020f88692c9d.nq.gz
│   ├── 9f7ae3b7003f16e335496bbcc600b59dcf98ce7a.nq.gz
│   ├── 9f7f9fff3f7655d099cfa3122a77ea9513bc0b0f.nq.gz
│   ├── a0bd437025d34e7fe8d380463767edbfa5330125.nq.gz
│   ├── a3497925d09dff629e6628766cf1bc25e45842aa.nq.gz
│   ├── a641d6590bf13978933c8bc9204d2f8818208286.nq.gz
│   ├── a67a7865bcee69786383f03e00271d71da5fca1b.nq.gz
│   ├── ad3abb52afea06f2202dd1b786a172aa34099b05.nq.gz
│   ├── aeb22e691f3cee159ed212d0a1b020f21ff8a8c6.nq.gz
│   ├── afd2e38308be1b42f7e3ade14a641637f805614a.nq.gz
│   ├── b012065921b3ecbfdf84edc78fefa66812e95ba9.nq.gz
│   ├── b2457d81167eee09ea0ad734e316f5a2458ffc7c.nq.gz
│   ├── b26f397bd69ec859fb07f273be2f596caadd0653.nq.gz
│   ├── b65de8c4d01f2cfcaa89be8fbab5e9c54d980cf7.nq.gz
│   ├── b789ef99b116847eaf6b193898ae291184372379.nq.gz
│   ├── ba2c375ba78766541ab07c7ab0703b82dc6523e2.nq.gz
│   ├── ba9ab7a5c28250b104962799f66f505c1d44f890.nq.gz
│   ├── bd475563d2c7e39c0156f10afb814fec775bc4fe.nq.gz
│   ├── be6d264d06fc373af0928e24940cfa6042e20631.nq.gz
│   ├── c03f65a7ed0416b694ec9372632b780a796e7147.nq.gz
│   ├── c3a5f15ef1c22d9cf0bc200255511f2870d4f702.nq.gz
│   ├── c425d7fcb2691fee3fa6d24d1bcb6b69f92d2772.nq.gz
│   ├── c63b8af1314c7bb56ccd38b80678122ac2da533c.nq.gz
│   ├── ca1c0308f9c6c977830394e5538ec5fef242abd9.nq.gz
│   ├── cdfae3d170dc60c50aaaa8c450e0116176f55abb.nq.gz
│   ├── cdffafb29167b2035ea0475a4b749154effc2099.nq.gz
│   ├── cf545d572604c99131c56ba1c3f84576d39ad9c6.nq.gz
│   ├── d3327b49b08460166284690dcc1c70235f073206.nq.gz
│   ├── d454b8e3f1ced2b47a89e3654914a3d555ad7d48.nq.gz
│   ├── d6c4a476ed4aab372c85abf2ec29def01e94b166.nq.gz
│   ├── d7cdae55e5be73b3ff6800c63b7ad4e8b8ca193f.nq.gz
│   ├── da9533d808f2d3ea2315bd7d2df867f43d0e2097.nq.gz
│   ├── dd0ab0de511b6afcbe200e5e22f926695214510e.nq.gz
│   ├── df6f623846450715babf37edaf8f6bed3c1d294a.nq.gz
│   ├── e01b416aeed57f9356ec7c1600f5fb76cbb44d36.nq.gz
│   ├── e2489b1340831a157762d9c27d170afd9b3224bd.nq.gz
│   ├── e285d59ce00184ddf01859d8b1abcd664f16e87d.nq.gz
│   ├── e291bd56c1fbb11fe86b4906c6902abd6cb5ad59.nq.gz
│   ├── e609888db7544a0ea74b85c5ddcdb99d148ff156.nq.gz
│   ├── e6316a52704be728d6784ff9831d7d9954109dfb.nq.gz
│   ├── e75687bca399759cba570204d843f0a59105ae67.nq.gz
│   ├── e8d15ee7a54647ddcfefd13504519c3480e2e1d6.nq.gz
│   ├── eb17cac060f0ad52c829d3143eb445fbf7ca1862.nq.gz
│   ├── ecae3391e9d932d0b7ee0b93c641aeda365bbfb4.nq.gz
│   ├── eef06a203e5f1aa5ebe983408e7c5c865e9d9c09.nq.gz
│   ├── eefe9138cc70b261770f6e788a3a576c960aaca4.nq.gz
│   ├── f4815cfa28764e26b51abaecfae0aa87e8648a0f.nq.gz
│   ├── f52c584d65673e2212eec66f2aab6c4f688d7862.nq.gz
│   ├── f57ba525fee941766002d319e32e8f634c48cd23.nq.gz
│   ├── f797acf0b699543feef3dd5ea4791ec776482cc8.nq.gz
│   ├── f9d60a5259a4bed7ef1838316ea6a8540d3e5d38.nq.gz
│   ├── fb97a638467c2ecdd4f58ef523764241f7a07714.nq.gz
│   ├── fbc0cbfff7e4eed5599925786131a3c0efea48c3.nq.gz
│   ├── fbcddb5196db484e3dc38d3183593b049fbb4729.nq.gz
│   └── ffc48e2bb3e473f073b2b776c2f6f456cf338a2e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a42c93634a472b2c80878cebc43976aadaff6d2b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 162 files
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

[sncosmo/sncosmo](https://github.com/sncosmo/sncosmo)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
