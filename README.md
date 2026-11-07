# Repolex Knowledge Graph of ansible-collections/community.beszel

RDF knowledge graph data for [ansible-collections/community.beszel](https://github.com/ansible-collections/community.beszel), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/community.beszel
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c793c29e1e0855c8b740195ed007f0fbe029e45b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c793c29e1e0855c8b740195ed007f0fbe029e45b
│           └── chunk-001.nq.gz
├── blob
│   ├── 0164155b81025416095f31a4732098ec238e6476.nq.gz
│   ├── 025289f92a3272d71b511e88a584cf9fe7762407.nq.gz
│   ├── 061659fbc665e19464d18bf8587ffd90df5be64a.nq.gz
│   ├── 077148adb5737b44216f0985d9d6ad620e814e81.nq.gz
│   ├── 0a9947692be44defff14a6175b562c67fbaf8e44.nq.gz
│   ├── 125e7fb71a1bc284a118b3007870884329a9d208.nq.gz
│   ├── 1301b1abdcf608d8448292a1d40f4c244e7fea7b.nq.gz
│   ├── 15453d518e48cad00412c3d180d5cb430004798b.nq.gz
│   ├── 17dd94414f30b261885ba73de887d3c2d5065bec.nq.gz
│   ├── 1b4891abcb68484c79ae57da1ebedaa1804cd2e5.nq.gz
│   ├── 1fe6ced10465ee5563255d3d639f603b09093273.nq.gz
│   ├── 206722bd42057780de9c9a0523b101b343cab2aa.nq.gz
│   ├── 21476c84804c6e67d2c3f44ef3fb0d9a460f6054.nq.gz
│   ├── 249f4c74dacb053ed08a5d0e027fab82b698aeee.nq.gz
│   ├── 25ee1d3aec19de6b8c16407b05f112551b41975b.nq.gz
│   ├── 29b14f361ac0355cb3dcb421289ffc56a1d6e918.nq.gz
│   ├── 29ebb00387cfc96071d97fccd17263114993668e.nq.gz
│   ├── 2a7f6fde147f807b9c44b34852deb1bc2404364b.nq.gz
│   ├── 2c90ba22f9a65208d8ab62d76d96391112a57fa3.nq.gz
│   ├── 2c9109ae1f0db54026650be6b3b9e09832e910d1.nq.gz
│   ├── 3127c800457ade49a605a65e50a620c2f5b44cec.nq.gz
│   ├── 322d71a4dcac997cb8f2c9ae0c44028d762d989f.nq.gz
│   ├── 35744e08ba9b07754d9585cf7daccbdfd082d9c2.nq.gz
│   ├── 388d9174b3b14604d614e4c4e7adc2667804dc02.nq.gz
│   ├── 3a0695a5dbe55df73eab08bf4b26c3f65e731409.nq.gz
│   ├── 3ad58edb7f150fa25b59a455b0f3ac7044b7fe20.nq.gz
│   ├── 3bd23b672903265ae39d01aea4622ed25e25c44f.nq.gz
│   ├── 4b240288fba20dfd6784fe138817c81042c569ab.nq.gz
│   ├── 4f6f7157ff8f2e5266373a240e64b3d6f71d02a2.nq.gz
│   ├── 5e911cee9bd651c0fe9785b98cad6747b08a768a.nq.gz
│   ├── 606f00e2722b8fae93ad855eafe03a9efdb989e8.nq.gz
│   ├── 61940fef09b74fa6ce4e65d275fdeb678420d22c.nq.gz
│   ├── 701609a151a0c953cdc8c6ce5d8afe9e9fa6e08d.nq.gz
│   ├── 711298ce6980a30f5a6407c99c5280aebbe08d7c.nq.gz
│   ├── 71fb64a80cd4100089869d8154ac9908dd0116a5.nq.gz
│   ├── 735edb86614129b2580755686b216128e1e09453.nq.gz
│   ├── 74eed62ab8093e4b65993db372b9affe7a65d63d.nq.gz
│   ├── 7604b0a8f85fed4eb8dd638d66fd695f6791ca25.nq.gz
│   ├── 797e4bdc22dc48069951ebe1893d66842b91e5ef.nq.gz
│   ├── 7a193de410f900957743b54316fe89195624d7b9.nq.gz
│   ├── 7cc993964b6a3045c18fd5002fa95a7eddea696b.nq.gz
│   ├── 844d8379c376f368c1f62c3c0296a7be9a2411ff.nq.gz
│   ├── 8608b916b1bac089d99ea43bb9f22af975e8bee8.nq.gz
│   ├── 893a619de730ea1e852dc5fdf84bf01d5f206ef6.nq.gz
│   ├── 8acbe3720f322ebbe4b5611f716f73d9d46fcdd6.nq.gz
│   ├── 8f7638099e3a36217f33f6e1636589984808516d.nq.gz
│   ├── 904b9dcdf2dd749ce1e356b463d9be162c044968.nq.gz
│   ├── 9264d5e04cf2da7b8ab3ef8e45dfd515ba8fe8e5.nq.gz
│   ├── 929b27961819f11884615740a5e3d903b3513429.nq.gz
│   ├── 95ef19c2caf58037d1428aee452188746e6e1d0b.nq.gz
│   ├── a056a90e5819e018af1cf914f42fb88a8e819c11.nq.gz
│   ├── a2201096e3e6486f64aac8506c6d54da5ff080da.nq.gz
│   ├── a26ba297d9da543414e7d9be0776acfe2bdb339a.nq.gz
│   ├── a278fcef9cd6aa258df784d074fa686055bbabfd.nq.gz
│   ├── aa9e8e077b4c5e86373511d0fdf8adbd4a75b210.nq.gz
│   ├── ad1e94136e88c50b68d6b8202e0e5c4d374013a4.nq.gz
│   ├── ae7971db2ab5ca9c33db8fd8a8bee6474f607c2d.nq.gz
│   ├── b5696832611ed6708027da68166e06391ac5ab7e.nq.gz
│   ├── b9bee31379acef9ae8b9f7ca1ac8ab51d90f57bf.nq.gz
│   ├── bd0a76623cfdafe16cab71515c07952326abdc56.nq.gz
│   ├── bd642dd96ec14cdfbe631b56bc188767d26e42c9.nq.gz
│   ├── c204bb79cca65da06ba3fa2fbcb1978bec346110.nq.gz
│   ├── c632ce7b179544b28b9e5381a866ea7bf180bba7.nq.gz
│   ├── c92868722a4422f9fb6cc5336d2c0e7906daf7fb.nq.gz
│   ├── ca9ece78b069251ef4ed7b8f06e1006791064982.nq.gz
│   ├── cb156cb3492fcd0b7cf4ccf12a33d99eda17e051.nq.gz
│   ├── ccba1d6128fdcc9042beceda172f2d79cd7e158b.nq.gz
│   ├── cf059a00051f1ae6eb7a365198d4dbbbd1d7b2c9.nq.gz
│   ├── cff57e55cf39d80d8ce7f199edf75619c8c9cdd2.nq.gz
│   ├── d296727e7d38bbd5f59d112634686e266f8f5c2c.nq.gz
│   ├── d29d646e4d879b86846d589b089189a2d02113a6.nq.gz
│   ├── da5e6f3bed8ad78ace8d839693ffc64ee8be4b6f.nq.gz
│   ├── dcb9891585d00e5845916694a4d6b7ac6957e3da.nq.gz
│   ├── e44312d8f946c561c1dbc13f50275bbb5bb930ff.nq.gz
│   ├── e5f9559a0b73e4330c08f9a5c0031df464a5f248.nq.gz
│   ├── e64405fc6d9c6f653701fb961887430b6c425017.nq.gz
│   ├── e790700e90d3330016308a8a093ab6aa3c5ba5dd.nq.gz
│   ├── e906b9df9b73dd4101d2ccbfc161118a4b46fdfd.nq.gz
│   ├── ea4f5bdcebdaa03414f7684484a33fa1d3a58c79.nq.gz
│   ├── eab198f331fe6c5b7d6a01d7ff749d29691df5d2.nq.gz
│   ├── ec50dbef67d3580293f8068508ab6b35994e5025.nq.gz
│   ├── eeb62c0647866faf8c4f5b0c046866f5ba0af4f7.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   ├── f7a112721db4c537da8ba34f0609f2e5b06e7845.nq.gz
│   ├── f9dc1b0f73e45b33139b3c4355280b066a78d7ea.nq.gz
│   └── fb7d2e36be243c4b13d9f20e975bed11fdb47817.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c793c29e1e0855c8b740195ed007f0fbe029e45b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 94 files
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

[ansible-collections/community.beszel](https://github.com/ansible-collections/community.beszel)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
