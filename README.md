# Repolex Knowledge Graph of python-trio/trio-mysql

RDF knowledge graph data for [python-trio/trio-mysql](https://github.com/python-trio/trio-mysql), parsed by [repolex](https://repolex.ai).

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
rlex download python-trio/trio-mysql
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 34812ab35477f46d322876a2ab037e4f5c086a46
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 34812ab35477f46d322876a2ab037e4f5c086a46
│           └── chunk-001.nq.gz
├── blob
│   ├── 013cb2fee90ff35b49368ffb509d4e18f407acae.nq.gz
│   ├── 04683f83c86040968f5ad41cc8f7b2cbb2a1e527.nq.gz
│   ├── 0d7f9219977906e3824fb83c66f7e6b2495095a0.nq.gz
│   ├── 163aaf8d82b6c54f23c45f32895dbdfdcc27b047.nq.gz
│   ├── 18a056ba7094cbeb4bcd6f909418652c557d9a65.nq.gz
│   ├── 1a041b13c11f1fc85a28a4c6f39d01d78a6c4ef6.nq.gz
│   ├── 1da2755338a72b7e6d89227ef0fc395f44a00b2a.nq.gz
│   ├── 22bed9d8d68bcd9f02517f2d28028003e0d62ce9.nq.gz
│   ├── 25e71d2de01c6314aed56dbb7687e54f7d0d6f8a.nq.gz
│   ├── 2789473422ec46da18e3a4706943f766694d8925.nq.gz
│   ├── 2bda5a96fa7e00120227c3377bdd94da2b60e77f.nq.gz
│   ├── 387be205c4fe4556b4808bbc156956e222ea7283.nq.gz
│   ├── 3a58e2ea5d677d5dd942adb62313f30df1725882.nq.gz
│   ├── 3c14f6d5b1ac8bc2b6f8076282bff13a0bfa33f7.nq.gz
│   ├── 3ee5a629d44e8f3c23db8f6a46775d16c7561dd1.nq.gz
│   ├── 4497dacf6a9de334780172896e9e1728d3f4ee94.nq.gz
│   ├── 46dc9a35db6f6f18d87ec0aea6e80792cda4548d.nq.gz
│   ├── 48ca956ecd40df08896e125936a630042abd2d96.nq.gz
│   ├── 4ea0671b7b8413d49d160516714076d1b95142ad.nq.gz
│   ├── 4ed75d3f1b229dfe0e3741ec61e40739fd2036ab.nq.gz
│   ├── 51b9f3a55d598fd29af96c408e708160c324a0bb.nq.gz
│   ├── 51bd5143b77cd12a2d3d5926bcabafa1ff536a81.nq.gz
│   ├── 52f4d9b173e8294182e0faba462c8ca296235c91.nq.gz
│   ├── 604aeaffe56e6ff24a94ac2920c5f7274851ea1a.nq.gz
│   ├── 60eac1090098267c14539d7837b3936a27b4c072.nq.gz
│   ├── 625c80b81ada945a0f0ec0883af5e3e170c7bfc8.nq.gz
│   ├── 66f338ea8e54a005f8c89209bdd7e023a3e8a536.nq.gz
│   ├── 69d9e455e1817a39713e98ecb0facd9a495447c0.nq.gz
│   ├── 6c62c00c675086d69416e2eac0dc055bc4ba6a50.nq.gz
│   ├── 6f5d566303a5111d9dfab97236cfbe6374ba6e43.nq.gz
│   ├── 70ec41f6c6d8a247a32ac519fbf7e7f635870da6.nq.gz
│   ├── 7a3a79152f1944b65feab9093580ff78d442f303.nq.gz
│   ├── 7a613478d43ac7b38db2bb9f1d8809c4194dd193.nq.gz
│   ├── 7b9eed661d33e8702dd4407b475a232453066844.nq.gz
│   ├── 7cd1b23aac54bf2b6209647fe83a31b148dc8efb.nq.gz
│   ├── 8027afa45610cbc00492f5061acf8c66bd69963b.nq.gz
│   ├── 82f25d6ef73732c9a5f58f1f7a649ce19592305b.nq.gz
│   ├── 838eab40404df42a3830a00936a5fa8268479913.nq.gz
│   ├── 895f64e0d8ca8dc37e90ac1b038d64b20be8385b.nq.gz
│   ├── 91ad57631b9be30cf3143bf78d85b36516b09778.nq.gz
│   ├── 938a37ab276464711a71b662b277ccab81c7f0e5.nq.gz
│   ├── 94100cfea6765801716857d1d4b920e9be1028b9.nq.gz
│   ├── 993d4c253182747f0b8f239ea2c6b4f56a2caff1.nq.gz
│   ├── 9bae2b68999839fcc991520559313e25e92d376a.nq.gz
│   ├── a0e6d5444a7b76640cc403ef04d5fb3aab8a4822.nq.gz
│   ├── a536d421fec897b9511dd0d4922eb1d601194cea.nq.gz
│   ├── a9e23d69ab29f46d59d7f19df10fa2b17d0a19fd.nq.gz
│   ├── aa23e065d3fce9a959a405258e1b3782b928d0f7.nq.gz
│   ├── ab385683cf7c3abc32ee4d08834d1037e370b5ab.nq.gz
│   ├── ac7693939ea2e4ceb2d3c80154cc48edc4113de0.nq.gz
│   ├── afb586677ff72d5722d91be4f1415c1c9eea70c5.nq.gz
│   ├── b42f1523c89d13db0827b1b0edf2f4cf73142199.nq.gz
│   ├── b662271a72c8d1fd89e2ee88bf57083ae8d2520d.nq.gz
│   ├── bcfa3bf541bc74feda3bb7af5c3f64a82a07a917.nq.gz
│   ├── bd0d69e6e7c39dfa6e3378e10c41e6b7a2949acc.nq.gz
│   ├── c0d4a1177eb4765461a7846135cd81eb78dbec31.nq.gz
│   ├── c381672509eceaf4a1bcf56331c293b03de250c1.nq.gz
│   ├── c4cf378e538f6280179ea5365f749f35734029e8.nq.gz
│   ├── c60f857cb9a126048da8ec88094030e69e1a56b4.nq.gz
│   ├── cd1caacf1c2cb0cc2e34ac887d37b130ebaa5123.nq.gz
│   ├── cf6a0b562e5bcddd9a032a8feaac5505847170fa.nq.gz
│   ├── d3ced67caaf9238053a71bc8eb54144898ceab49.nq.gz
│   ├── d3eeac8d9f9ba15351730b716eca51c68b1b5fdb.nq.gz
│   ├── d5467b11b3830c2d7537edd634acbe3b0ea7b88d.nq.gz
│   ├── d5a332acb5621cf28b5fec9a9da0f95bddca1a51.nq.gz
│   ├── d65512fbb3fa5276e9b13ebf81a2666d61f872ba.nq.gz
│   ├── d88bcf3198b8bf00f23bb07ad13cf8b98e136b2e.nq.gz
│   ├── d8c1bded52350611c2c47b9e854dc0915b91bd93.nq.gz
│   ├── db1af54526b7d8c5809c6517a1558efdc909df44.nq.gz
│   ├── e0abab27d718cd0014465d0478483f6342fc1156.nq.gz
│   ├── e435d53e209e3e48dd90eaf1b26a2a07748cff5d.nq.gz
│   ├── e45306d79c594b98766c670964dbae04f8455c46.nq.gz
│   ├── e46083f6acb61a8a56a69b21d9445de58605abc2.nq.gz
│   ├── e518ad0636596cdfe5cda174746f5e4396ff5352.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e82e08cfe93e55ac1b837d7faf758e8a1596768d.nq.gz
│   ├── e9e1eebcb388fc71677dfabbf4f04f7fd0802300.nq.gz
│   ├── eb75f853dc9b9c3d3321bc01d15f4c5b0fea6d79.nq.gz
│   ├── ec635144f60048986bc560c5576355344005e6e7.nq.gz
│   ├── f0489f59c2e85bd33adad4e18a5aee53e1ca1dd0.nq.gz
│   ├── f2746f3e1398d1804fcc7a4102a1ffa87c5e5020.nq.gz
│   ├── f2bd4d300f48fb3b261ded5531598d3e5a4e78f4.nq.gz
│   ├── f50ab3efc4b19f5ca009c6ef85dc5bdc2c3bd659.nq.gz
│   ├── f53f05c10acf6c4a538ce7b0e094573501a8456d.nq.gz
│   ├── f83745afd24c5fdc8e9c92c3be201a838df806de.nq.gz
│   ├── f9ebfad6d5c387f95b5a591c59b4f38c6215ec3c.nq.gz
│   └── f9f99c8fa32de4a75ef01859eadcc4de94c5c961.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 34812ab35477f46d322876a2ab037e4f5c086a46.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 95 files
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

[python-trio/trio-mysql](https://github.com/python-trio/trio-mysql)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
