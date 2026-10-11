# Repolex Knowledge Graph of pytest-dev/pyfakefs

RDF knowledge graph data for [pytest-dev/pyfakefs](https://github.com/pytest-dev/pyfakefs), parsed by [repolex](https://repolex.ai).

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
rlex download pytest-dev/pyfakefs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 796c48eb7830e3ee7fb57eb368dc115c1f3436ba
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 796c48eb7830e3ee7fb57eb368dc115c1f3436ba
│           └── chunk-001.nq.gz
├── blob
│   ├── 0106af6b06cdba65e2ae253119a50da684fd0497.nq.gz
│   ├── 01b464ad51ce269cc5c7c0d69da689f817f3bd07.nq.gz
│   ├── 046a18c3de22c960bf4928a32d662ed56336b405.nq.gz
│   ├── 050c09304ae5d74f9f8fe6f3e5b67fcb455f279a.nq.gz
│   ├── 0a3bf7ff8a1952bb37188a07d693972ec1dd4442.nq.gz
│   ├── 0cdb2e17bcc8d374f0148aa0f742d795f9ce00cc.nq.gz
│   ├── 114962433e1a00d1b1470ad752e85592f8edff57.nq.gz
│   ├── 115b35e4c82fd3c0da9cca70ceca941d19579bd6.nq.gz
│   ├── 13085cda454c70e716c9a1a7076ba4ac93b86bc1.nq.gz
│   ├── 134cf144ee514f58947e1de005136892ae84de46.nq.gz
│   ├── 1502f57dd582125382941e6396db2ece24bf28ec.nq.gz
│   ├── 15f704d31e71cd069e838062a8f4ec02323c224e.nq.gz
│   ├── 173dc46fb499be280b5b908b8acc1207874b3f7c.nq.gz
│   ├── 19344f0b3c71efac90fdadb2b1e97a69f90a05a8.nq.gz
│   ├── 1daa11f072978c6ea8ee011b0452786e8ae9a987.nq.gz
│   ├── 1dee84b216d7e28ab37ce3d4250bbce3746481b5.nq.gz
│   ├── 1ef82f9b1d8b97f6e2405865c80d98d364df2e31.nq.gz
│   ├── 2104fc461d0c0632da552c63f8cbd1aaf38e7048.nq.gz
│   ├── 22ce33d45123a0607300ad9e13d8343179c016c0.nq.gz
│   ├── 23ec944d08a8e90fb76602637bdeec1b098cc5dd.nq.gz
│   ├── 24e21331c8105693269269d94ad4b480a9bc665b.nq.gz
│   ├── 25764439fa43918dcd33d0c282d7238692d15079.nq.gz
│   ├── 25eb270495de5f8e558f32a6f33cec05a79ffacf.nq.gz
│   ├── 25ee0ad2189e81c2ea0e44dbb509527158060105.nq.gz
│   ├── 2d377bf01a4eb50939df0e6382855e2146b95d3d.nq.gz
│   ├── 2f9ba81cda38c6b6cab892e8ca51831dc27bb044.nq.gz
│   ├── 32a8dbf88484ee2df2691d2e06a4b251bffb949e.nq.gz
│   ├── 3302c2837c76f208c6ee31f2a2fcd72301ffc504.nq.gz
│   ├── 33daaae72e2065239c3d7c3fb6edd7b0954304da.nq.gz
│   ├── 3747e8afbcdda8160508a3e1b5f2bf18f947ac9a.nq.gz
│   ├── 3763e28948d106eed8346d2362ca219f70b15b0b.nq.gz
│   ├── 37d93ca3996387257faf48cbd48f9026e0a67335.nq.gz
│   ├── 3e5d16fb77d0bcdc7bcb512bab96fccd0e8ac7d0.nq.gz
│   ├── 3ed15444a74608c7214e94ea1bac2efe0b586c3b.nq.gz
│   ├── 3fde22d1d8c42ca3c67ac210685cb125d0a1e820.nq.gz
│   ├── 424ee17f97e2be9f93b4de453e65f52626a189d0.nq.gz
│   ├── 42afe3fcd2dfa05755f69efd16f7cc986a452620.nq.gz
│   ├── 43c5d594a6c417cbee9230e5a54eac331e549f9c.nq.gz
│   ├── 444f54788186c607eaee90bc21a7222184ca487b.nq.gz
│   ├── 45ba4781b7a79eceda5405957790a3d5c85618f8.nq.gz
│   ├── 4e0e63ec2e8f44a6032cc53714a879fcd66b5f81.nq.gz
│   ├── 4e30676b0f620d596f7d7455b61ce4d69966e546.nq.gz
│   ├── 504f1c55d98c43d7323cebc1248d504e4fb729d9.nq.gz
│   ├── 50a75d075eeebd3f680b50537a992aea93254328.nq.gz
│   ├── 556b49210d3c2f61a7ba8ee8df1fdc4b3db7f45d.nq.gz
│   ├── 58b2df462154dd54ddf9612727e63d22823d47e9.nq.gz
│   ├── 5d8abc67d7c495e12ac77a848caeb42a92287c09.nq.gz
│   ├── 6110aa5d2b3151170bc75214e8d987b731cc11d1.nq.gz
│   ├── 651c232da02c03e2e3ba2723f7eea76e8f56129c.nq.gz
│   ├── 67d3d777c052fa1853d4bd63516dda4ff25ba5da.nq.gz
│   ├── 67db8588217f266eb561f75fae738656325deac9.nq.gz
│   ├── 6b6b64d503229784f6611ef35f13df36f8b37dc3.nq.gz
│   ├── 6cca62e2d7f029e2ac370169bee5dd9c2ff1cb60.nq.gz
│   ├── 6d0916080be69a4126d647efe2952c29b6da11ec.nq.gz
│   ├── 6e3fd8b8c0b6c4bed7cb5c1d391c21b006b765ce.nq.gz
│   ├── 6e500de0359195a925c8bb0f943509f07eeee8b0.nq.gz
│   ├── 749caa14e2da1a28da2bf4b5e2df9d81bef22589.nq.gz
│   ├── 7a950059f8a3dcc9555a53b3edb437cfde50a92e.nq.gz
│   ├── 7fe1221dbdf849466f8b6251a5005b447b1e0cbf.nq.gz
│   ├── 806a5a99615e48b926ef007c3aa34abfd7fb1689.nq.gz
│   ├── 8327488db7efebeb6d695c5d674dbf2b95b83308.nq.gz
│   ├── 857e81c0ba397bfd8aec80980fd08586fbd1fa4c.nq.gz
│   ├── 86ec3ac199494c888ce10d2527e1b5ab35b268e4.nq.gz
│   ├── 89da024fa3777230262dd19070b1c67730afb019.nq.gz
│   ├── 8d84855a14eefbf7dae04d833df7c2574ff53dac.nq.gz
│   ├── 8f3bd6fb56e960062ef495b1e680567776995d0f.nq.gz
│   ├── 944c4718f7eedb74f4b04c1494ed494d84cfb7cb.nq.gz
│   ├── 96dd6ca8cd9f0dbbac225fdd5f50eda245a391b0.nq.gz
│   ├── 9b32cd746153b7d8d16986c25e129c08aa96be3d.nq.gz
│   ├── a29e06ebd87a62b9ed5e704c455affb8d5bbf08f.nq.gz
│   ├── a608fc75dfd7bf7a449a47a714da1a9c66e71c0f.nq.gz
│   ├── aea2f658e79f9eaf1a0f0e0bb2e7f67f8afe26b4.nq.gz
│   ├── afe267626a5b320d5bb7ef43031a388156aa5189.nq.gz
│   ├── b000261f6811b897675bd453aa5ff6292a96a1da.nq.gz
│   ├── b27f3a6e72a23ca3a0b883e89532fe6aab671a12.nq.gz
│   ├── b566b558e368bef97eeaf8185ae544321cd03e56.nq.gz
│   ├── b5a46d36b54d6319ca68a1b9f7e43639cb609fc5.nq.gz
│   ├── bc07bdb19cffdc24241ed04bf8bd97bbf418b63d.nq.gz
│   ├── bd0c5e51a6e7a1d0aa2e0608c20fe034db3c9605.nq.gz
│   ├── bdad7be22e42b252979098f6e1ed6d871623799a.nq.gz
│   ├── c27f7cb64be354fd83c789787ddcdf3b912e08d5.nq.gz
│   ├── c3388279ceab66052e6ff43e4ddd0bc314a0c723.nq.gz
│   ├── c40e74046b54570ef00784bb20bc64ac6864d0f0.nq.gz
│   ├── c73b8d6091075d46b6677a05a31a216461d1a145.nq.gz
│   ├── c99fab52357464ab9dd1372fa362d2616e49544e.nq.gz
│   ├── c9eb43efd7402782b77868cd6db915d5632e31fe.nq.gz
│   ├── cc9f4a3c43c4bed5757a93531829e6f6a6ce2d5f.nq.gz
│   ├── cdf72be33f8265c240cda9778634ec288b7785c3.nq.gz
│   ├── d1351500e5761df582879cb643c9e513399c9eee.nq.gz
│   ├── d149b18dcea626fb57b4bb54455be43c06c2cab7.nq.gz
│   ├── dbf4dc08d5003fe002b2d04d33988fa1d3cdcfa0.nq.gz
│   ├── dc0e7a135ee9f0e674154bd146e97d3a7c7e3a21.nq.gz
│   ├── dd570b0a60e2865d4d40a79de7a39b6a38bcd860.nq.gz
│   ├── df5a38130164932a06b67d4da88b8e70d418683d.nq.gz
│   ├── e12f065894de7617eb67af8fc97d9cafea65b5de.nq.gz
│   ├── e5903e0b83dc737c6590aed92cc76b85b8613929.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7d30a496c8fba5c83ae3022d498ffc36df239ac.nq.gz
│   ├── e8b4e1e0b12e3d68ede457ece326f524a65b7670.nq.gz
│   ├── f7903b4dbae835a04f3763af5a230b5be6a40e31.nq.gz
│   ├── f978e366ad23355f46329339c909d4e6309e21ce.nq.gz
│   ├── ff8967b236d37c8645ca5bfd1a3d748b7bb13b01.nq.gz
│   └── ffbfef78c3690f6779edbd845c213fecc91c7f6d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 796c48eb7830e3ee7fb57eb368dc115c1f3436ba.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 111 files
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

[pytest-dev/pyfakefs](https://github.com/pytest-dev/pyfakefs)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
