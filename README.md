# Repolex Knowledge Graph of google-deepmind/ferminet

RDF knowledge graph data for [google-deepmind/ferminet](https://github.com/google-deepmind/ferminet), parsed by [repolex](https://repolex.ai).

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
rlex download google-deepmind/ferminet
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e9d5a604d15c617864e7caefd948d87453b01ae6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e9d5a604d15c617864e7caefd948d87453b01ae6
│           └── chunk-001.nq.gz
├── blob
│   ├── 0274ab8e1fe1a003d636aad4316b97c4f394ed06.nq.gz
│   ├── 04404767969b75e9e3500a61aa69d67dc5ea95b2.nq.gz
│   ├── 06ac7d825378c8cc3771b6d33133eded383c505e.nq.gz
│   ├── 094af3c0c5a434a7b1c83a71df782622a9ae3a26.nq.gz
│   ├── 09ed8c7c9e57385d1243c532d0e0ddca69e56290.nq.gz
│   ├── 0ac708a14ded680901db22f168f3fd2f307f93eb.nq.gz
│   ├── 139d3307d72711bb957935e341bbef0a074fce9d.nq.gz
│   ├── 1412b3c7eef1878974929d11bff79967e47fbe3e.nq.gz
│   ├── 14506f4075476c1d754ebfa983a70a11953808c9.nq.gz
│   ├── 188659213333a57456b707f08bdcf652eb61beec.nq.gz
│   ├── 18ef71cdb719e73fc835f304c07706a48fcd41aa.nq.gz
│   ├── 1b885cf4bfbb28556c6804ec14a355067745adb5.nq.gz
│   ├── 22b241cb732cc4ff325263263cd603784d580eb7.nq.gz
│   ├── 2395bc23a1d23075dfaef54ad1d84cb59fa1e932.nq.gz
│   ├── 26452aa37342e0a0b7ebe096a15eb01b3f34973b.nq.gz
│   ├── 2ac7fb9fd44de0c90e656e1a1b7c6d7f29b8bb03.nq.gz
│   ├── 31f7ac9a134b2a4b778588e4b9769113a657c8fe.nq.gz
│   ├── 33febfe3f65ab7cb5ca3c03607253e7cc60bd889.nq.gz
│   ├── 34322a543cbbdfbca4f676ebb5e877f86f36de57.nq.gz
│   ├── 3450d8ff43f672985535911644fc13d535e6cbc4.nq.gz
│   ├── 378f9195b64ebd513104d7e1b783a772a7a84e7f.nq.gz
│   ├── 396c45ecb46b058a704f28495ccd285b5a11b6e9.nq.gz
│   ├── 406d5b7ded58bc4c0cfbbfb138264baf2f04e628.nq.gz
│   ├── 41863bc2b8b7b66e3a7d1c2da0f9e46a47776dc4.nq.gz
│   ├── 478812bf34ba9e1292deb56e03d9060c4cbe31a4.nq.gz
│   ├── 4a5f32eaaa57f855a128359c41c47bbb476d6532.nq.gz
│   ├── 4b21439de8cb5688ea0be9b8e9de08375418726e.nq.gz
│   ├── 4ce1c926eb820e98a479872412b9273e385345ec.nq.gz
│   ├── 4d3a3fa43a42c6e6bb40d8d7f09ebc37377826e8.nq.gz
│   ├── 4db8006e8165a27f6a319b68233260c1f01c67cd.nq.gz
│   ├── 51b6e541fc52f2898279efbc599c4d8c6a672f37.nq.gz
│   ├── 55257cbec742be78173bb3b129214b47d00df330.nq.gz
│   ├── 5bb8aac4c8e788554b417c9931e30855c305ef3a.nq.gz
│   ├── 5dbeda6451a6afc54eb757a8430450c555ace558.nq.gz
│   ├── 694f312f8909f3d005ebac1eeed850782224c6cd.nq.gz
│   ├── 6a1eff1b830b533975206fc79ac36ff10c945d79.nq.gz
│   ├── 6b0b1270ff0ca8f03867efcd09ba6ddb6392b1e1.nq.gz
│   ├── 6b7d9e51f180cd33a49c5db38d938b969d3c605a.nq.gz
│   ├── 6f19272516000e978e69bddc490e92133fadee6e.nq.gz
│   ├── 727937ae15d029c9238ea7f3e8921fc7a22f1180.nq.gz
│   ├── 769f186da8aff50d6fef9dff8745e8aac09284b8.nq.gz
│   ├── 7bad38ca2d4424b55207f49191b947921bd5fe47.nq.gz
│   ├── 7d83ba8d99062532a90f04496ff5ddbb786c3291.nq.gz
│   ├── 8007bcf42730f5cb5e009e13d42be8b1c4104540.nq.gz
│   ├── 817fe97c65a2709283bea69e11397e8a2ce47595.nq.gz
│   ├── 832a82439b7759fdf53af16edc467343baf72142.nq.gz
│   ├── 86bf9a3897fa66740c8164e2303455da64fe5b3e.nq.gz
│   ├── 86c8048fc6e5abc041d7f4a72c859e61764762ba.nq.gz
│   ├── 8a4e2391e43bf15239b6ada07378e4ba9c5967e3.nq.gz
│   ├── 90e0d5b40a3c920a68d38f96a47c89e874224b77.nq.gz
│   ├── 966ee6bfd73b447a453f1eb615cd44d6073a261b.nq.gz
│   ├── 9978e458fc495a74e07521988adaa5a64e6a2b5b.nq.gz
│   ├── 9af44d98bc4fc3d5f63338fd0a0a6b3fd55cd0f5.nq.gz
│   ├── a082df6b7de761938af72b354ad1b8e1ec61b097.nq.gz
│   ├── ad79902676cbf7c2985b0c1786d0e47e5540e8ec.nq.gz
│   ├── b53663868de303d1aa011f2f3fe94e46f1a39b95.nq.gz
│   ├── b54d956bd0f3ece31735da4fd19b883601717a48.nq.gz
│   ├── b5730d35e886427ab1e66f7a95b637af43a32053.nq.gz
│   ├── b7a9e8e92c2f8d9f88bdf1c48d4ae9e2b1b1c73b.nq.gz
│   ├── b991e537f9f7d975a8de491c18f3d90291981892.nq.gz
│   ├── ba9feb071311d3151b4d0380f16e9809648a56bf.nq.gz
│   ├── c06c79790c5779ca8324d9fb83299ad2e2903b0d.nq.gz
│   ├── c28a55e33026490d809d11e610f78c7d8425dc15.nq.gz
│   ├── c7ba77f46920574ca7c317a64a7f668830619ff7.nq.gz
│   ├── cb81fe20163a64219979bc5fa1af37d3ead54f27.nq.gz
│   ├── cea45937b025b36ca7bdc52b65f9759060e31276.nq.gz
│   ├── ced8df15d398954bce2924dd48cc233ca18ba2b8.nq.gz
│   ├── d17e84f0a81d55f7db5f436cbd1c1263fd6768f9.nq.gz
│   ├── d2261ba52345a152185eb8734e27b56c12438324.nq.gz
│   ├── d477dec81f856d26ed8a185decf9185bc45863b2.nq.gz
│   ├── d5327d002e10a28652a81218d9a4fbd7014748e0.nq.gz
│   ├── d7693d1091286d36b19d596e305efe3a75783c2e.nq.gz
│   ├── db5b766410fd04fc6833063343420db68e0e7645.nq.gz
│   ├── dda854974901d8bff6e3490b7d9ea33b2e3b5851.nq.gz
│   ├── dece9d82cd7370c1dc612f448fc92b4c4d744bd1.nq.gz
│   ├── e37fc54bd485d480849cf8aebabc9516f1e1370b.nq.gz
│   ├── ed5a1c1550973a12cf7a9251bc3da90814f4cc5a.nq.gz
│   ├── f183ac97e96213169c1f7e8e461f0249da2fb38f.nq.gz
│   ├── f915d4b63c534186b2fb1ddc748c5993bdeb2d33.nq.gz
│   └── fab559f35061bce96b495066d532b115231caf03.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e9d5a604d15c617864e7caefd948d87453b01ae6.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 88 files
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

[google-deepmind/ferminet](https://github.com/google-deepmind/ferminet)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
