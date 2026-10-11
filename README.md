# Repolex Knowledge Graph of samuelcolvin/forgettable

RDF knowledge graph data for [samuelcolvin/forgettable](https://github.com/samuelcolvin/forgettable), parsed by [repolex](https://repolex.ai).

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
rlex download samuelcolvin/forgettable
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a411426afc7b69dfb091fd26ca5e2d653a075b03
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a411426afc7b69dfb091fd26ca5e2d653a075b03
│           └── chunk-001.nq.gz
├── blob
│   ├── 006a608dfed7fdef97ca1f163845eb6518f459a7.nq.gz
│   ├── 05fa8ea4ecd5850e7823425cf4bda87d9be1c671.nq.gz
│   ├── 073a72da9d7b5c0c343278e12b92e12aab503f01.nq.gz
│   ├── 07be17276136579cc035ab1d854b5a2febce07a5.nq.gz
│   ├── 09708a1b272ff74d19861c2b19595b5c5e9fc9ff.nq.gz
│   ├── 0a407375fe8a1437bdcf3c5a27f0b9ae4e8e209f.nq.gz
│   ├── 0b5bffb017a2d01171a3341cf7acf604cebc5a50.nq.gz
│   ├── 0d22eca5278512b18de0e2086f46e21ab166cb87.nq.gz
│   ├── 1655c54a56f8f16afe046dbf9ab08045ce4f5533.nq.gz
│   ├── 1846be06d114bb8f8feb9fe6de2dc070cce33d60.nq.gz
│   ├── 1a9a052a15f2c58d0af945d65c5e4ac2d719a7da.nq.gz
│   ├── 213d352681858999e42f133f27a7868ea6d29473.nq.gz
│   ├── 22969bbdc5a1d1a39fa804aaf71d7c925eb868c9.nq.gz
│   ├── 24613912984f0148f1f28fc6f38f4c77e0ebc061.nq.gz
│   ├── 26e9f05b8a0d524a9584102559d33bfe30c52580.nq.gz
│   ├── 28036692f55a398e0b7277f8884a1c16e91df4d1.nq.gz
│   ├── 29152b99cf9717b317620f4ab8c5ef7e6765379c.nq.gz
│   ├── 2aa6d41713c17bc2ef1fdff2df63ab5cf061157c.nq.gz
│   ├── 2cd811719155b987c8f291e56f694f8bebab7b37.nq.gz
│   ├── 32339ae091fe39f77b2792aaff6ddd558bbccc3d.nq.gz
│   ├── 340747efb8c6287f8465e44e960135eceb7d1ed8.nq.gz
│   ├── 345e48dfa7f3ae5ebef33155aa47c0dc5e8ea3e0.nq.gz
│   ├── 347e02a75c1a49e3303e1277537ec08320ba175c.nq.gz
│   ├── 356ae4a3e4884149b4b56c52e66e5e98171449ba.nq.gz
│   ├── 36e4fd5ad4455a62febbb700591ac8806580040a.nq.gz
│   ├── 3745decf79e26f1f6eec3055a2dd5e6bbddae006.nq.gz
│   ├── 3c03f8092ac727ccde9aa4d78886b0d36e354347.nq.gz
│   ├── 3de49f34b2663804787611dfcfd9b38c78fada55.nq.gz
│   ├── 3e6d887a9b61b560f0a9add35da76015ff178c6a.nq.gz
│   ├── 3e763d7ed42c7a4273e8138272f30ed840396ccd.nq.gz
│   ├── 42c8bb4a4a321ccd3292332825261d6061cadc39.nq.gz
│   ├── 447c6fdcba047726ef7f6c2841ae010e7c4b5ed8.nq.gz
│   ├── 45f10b929f677da661ed170a6ce7af11ff1b8180.nq.gz
│   ├── 46eacb24f01d28cd6c3085332e593596c327c9f1.nq.gz
│   ├── 4aa6b9208af7f8fcddc70547e4fcc5dfb62b548a.nq.gz
│   ├── 4c3974a218e76a6be433dbd4836a58b5b935fa5b.nq.gz
│   ├── 4f810c948f7e887c2489a187acd21e14cb02de89.nq.gz
│   ├── 571cff9c2553b07a3d6d348dfbf5db5cf645023d.nq.gz
│   ├── 5d8a43fa8fe44e44b655884a377a0610220c5d8b.nq.gz
│   ├── 5e412fca2c5c78f772f79248919db224502b7d34.nq.gz
│   ├── 6225a177574dd340f809daca61bb253a778841fe.nq.gz
│   ├── 62e8e23041f1035dc5a28e66506a50c1ea7065e9.nq.gz
│   ├── 6324d401a069f4020efcf0ff07442724b52f47c2.nq.gz
│   ├── 63717dc29f9a9020212272c2fa14498c7ae9cef4.nq.gz
│   ├── 655b8219c621d200976a1dd9178c96b2bd5ebc5f.nq.gz
│   ├── 6c1245a50a6a1f8518cbdb9df248ce1a47bb8240.nq.gz
│   ├── 6e7280aecd31859fa990e988eee146f39000cb3a.nq.gz
│   ├── 70381c5081ce826195142f02d9fa11a06c19a044.nq.gz
│   ├── 720a8cc46d03fa559381cf62354dd2c675eaca0d.nq.gz
│   ├── 72dcc28082edf311c8db783934adfca4a30f8e60.nq.gz
│   ├── 7346b3155d4e67fc396487d6e2a343e353164a18.nq.gz
│   ├── 73e59b286841b670112123fad5f9afebb717f559.nq.gz
│   ├── 757e78233259bdca7821998a7175f18572e7641f.nq.gz
│   ├── 75c8969563cf3b6391feb6eab10d3ecd6d8b39ab.nq.gz
│   ├── 78afe526e29a4360b53638286e87c3ef8282c633.nq.gz
│   ├── 795bdc40be9e10a5ff23c8838ad19d15068870c5.nq.gz
│   ├── 7d13c42d1b8b3e09d97bb72fd61b3b94629dcfc0.nq.gz
│   ├── 7e5ede140571bee5ab7ed635629d7e2af2a00a2e.nq.gz
│   ├── 81353d745330bc63e6e9be89aa2c2af11be08835.nq.gz
│   ├── 8237c49034cc458f9cc562e5515b80ea914e7246.nq.gz
│   ├── 836665777dee0d9b6ab93d86b983837a5441c877.nq.gz
│   ├── 853b22b536b3065bba3557b544e1640c41dd2b06.nq.gz
│   ├── 890dac609997f60ab1c63415f6eba6d4de6a26fe.nq.gz
│   ├── 8974188ca8e4fb304301a97ae76b1f61380a0e07.nq.gz
│   ├── 8a67f62f4ceebff3424e6e8cd4b3c25b17347546.nq.gz
│   ├── 8c73fd7c23235417a56b4d03f1b240fd345ee7f5.nq.gz
│   ├── 8c97becfb5e34ccdd9ea91a2cace811b1d66cd10.nq.gz
│   ├── 8e47c6524120f56254d4cf99aa8f4ed432d43a2e.nq.gz
│   ├── 8ef108d0d071ab7bdaf97cc9cfa9888efd855c27.nq.gz
│   ├── 91fd9b271b39509de6f60b00ccfc42ad8b5770a0.nq.gz
│   ├── 956e61ac0f398fa9cd03585dc6ca31199c1e9dac.nq.gz
│   ├── 9774bde93f121efbe2b2859bf1414c29e2473b63.nq.gz
│   ├── 9ab3f4b3375f1de43f061fa00de8911fc72f13d0.nq.gz
│   ├── 9efed4188f32200f1fe82e9d030c689995d63140.nq.gz
│   ├── 9f790761a3e47065cd3e3f4742a85d5ba841c4e3.nq.gz
│   ├── 9f918b4d695b85c64ed631c348cc43918b97d61c.nq.gz
│   ├── a0140f0874629c0c185f388d562fdf74f1da828b.nq.gz
│   ├── a21f178d3ab70995291ecb91ca05e8627f3d0380.nq.gz
│   ├── a28c028c1e353d54d9e86506ada0b41a96f459af.nq.gz
│   ├── a32b88079c50aa53a50fd25b0b63e9a1ab101481.nq.gz
│   ├── a48607a982dce5f59955c7effebfc0b7073e022b.nq.gz
│   ├── a547bf36d8d11a4f89c59c144f24795749086dd1.nq.gz
│   ├── a5ad8ecf347911cbc03c23829617aa3456d2955c.nq.gz
│   ├── a881dbf43a0c7b051ab2569149824f130e50eebf.nq.gz
│   ├── ac67a61be86263be1eef7b8567561f3dc1a6ea79.nq.gz
│   ├── b25cc357f80873d458695288432d814769e8be97.nq.gz
│   ├── b4a6303025948af4ddf6226817b0ad8a288f79ea.nq.gz
│   ├── b57f98933ce732f58d225e716db39e8aa607b0bc.nq.gz
│   ├── b9db64c62e500535049293b99c66524db64676c6.nq.gz
│   ├── b9e8d22999eb36e87ea9d3310812fc07ebcceacb.nq.gz
│   ├── bcc569ec81b4af66cb2791589ca67c07456d3627.nq.gz
│   ├── bd0c391ddd1088e9067844c48835bf4abcd61783.nq.gz
│   ├── bde8444cd2c1f29d3451c33d60e6248f419a3a1e.nq.gz
│   ├── c053dbbcf68d0b1a441f5b08bfa1255ad921ef21.nq.gz
│   ├── c437039be087b06d4061d363680915b401fbb5a6.nq.gz
│   ├── c5e09c14c889941cbb79ac5c50e087c016d1c7c8.nq.gz
│   ├── c8adda016708fad7e1a628cf64ff3a53d82b3910.nq.gz
│   ├── ca3015789745e1592ffcef6f8bba61850e1b391c.nq.gz
│   ├── cbc96cdf425f52da3d989331955daafa0d6fcf23.nq.gz
│   ├── ccd6a39a23c527d9ce519b787c0f9d1b662e8758.nq.gz
│   ├── d0b9c5da8c988628ec77f1b0616a0c173b25357a.nq.gz
│   ├── d2c7ff40921f984f97c10aaaa5bfcaa83fb1ff94.nq.gz
│   ├── d32b0fe652e3a7129dd9a4a2fb82bfbb6faad449.nq.gz
│   ├── d35411bab389a833d5a7a7494cfd87fdedd00f3b.nq.gz
│   ├── d40415c33648a772cb69347e11a9e75b09294c68.nq.gz
│   ├── d69f57cd376cbbb824c8f430cc396aeaef8b7747.nq.gz
│   ├── db6c02a1d89654f8653de6be09a9573a8cf21dfb.nq.gz
│   ├── dde143849f94c885127ba9f67fc5aa6bd539a00c.nq.gz
│   ├── dfccd5158e5ae156f3900583865ca3bd8e5d661c.nq.gz
│   ├── e131133b168bace50ad705c58ed1d728a42a7fd2.nq.gz
│   ├── e21660b99445c38940be1e418ac806c09190e728.nq.gz
│   ├── e4a7cc154276f1dd65c62519922cb26e80808d3f.nq.gz
│   ├── e4e5bd44d7673020a7b8616e9c3c8db24e1c2857.nq.gz
│   ├── e676cc00555a79abcb5c05d80de9da5d1a47aab2.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e75b33d31d2dd9e1dc96c4ef187eb5be77588b9a.nq.gz
│   ├── ea8c4bf7f35f6f77f75d92ad8ce8349f6e81ddba.nq.gz
│   ├── ebeeb956b8b211b7b22aae691a700f4989ac84b5.nq.gz
│   ├── f0757eac07726beb2b70ff842583bd7e6bbd3618.nq.gz
│   ├── f700be7709db60f4b483489fcfb8ca9fec470325.nq.gz
│   ├── fbc738c09516920d417d89ad7147082d8a93b989.nq.gz
│   ├── fd37857e562493102d983d34285545f35069c6cd.nq.gz
│   ├── fdcbe9e2eed537fdd44a6d0794c683cc485588b4.nq.gz
│   └── fee11e02df8053ca257746f3ef4b0f781f507c05.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a411426afc7b69dfb091fd26ca5e2d653a075b03.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 131 files
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

[samuelcolvin/forgettable](https://github.com/samuelcolvin/forgettable)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
