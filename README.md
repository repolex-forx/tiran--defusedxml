# Repolex Knowledge Graph of tiran/defusedxml

RDF knowledge graph data for [tiran/defusedxml](https://github.com/tiran/defusedxml), parsed by [repolex](https://repolex.ai).

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
rlex download tiran/defusedxml
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c7445887f5e1bcea470a16f61369d29870cfcfe1
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c7445887f5e1bcea470a16f61369d29870cfcfe1
│           └── chunk-001.nq.gz
├── blob
│   ├── 00e824931d2b03fe6fccf056e938f484fd8651fc.nq.gz
│   ├── 04a757d99240451c0c1a65730fd6669a1c514c29.nq.gz
│   ├── 05a420404a959c3479a8fe9b47dc642cf416d12a.nq.gz
│   ├── 06147c2768cd531049d00f47a44239dc3e42edd4.nq.gz
│   ├── 088e9a79aa117b410a177bd3afe67eba0d6dd114.nq.gz
│   ├── 103513970d8a3f502b2cb074a0476d192da29365.nq.gz
│   ├── 15c179f9a42dd24c3374003e75c5bf7f9e914afe.nq.gz
│   ├── 26b409a01724c3d8b8adfbcd569d45a28a1d1f3e.nq.gz
│   ├── 2926c6706707c10a4cd7f516f0cc4b00a38f1273.nq.gz
│   ├── 2ce1ef6e9604fa70f3648925bb6780146380cdc5.nq.gz
│   ├── 2ebce6782f4779ebf888b8005d37413803220b24.nq.gz
│   ├── 2f1ddb7dfee0a5a4d06ff6bbd26d98a92257a365.nq.gz
│   ├── 311690c68fe4af37f8136cc05e62e9d51942b46a.nq.gz
│   ├── 31727d10275adb4123fc72df9a275f2544eeaf78.nq.gz
│   ├── 33fd9e46e9d773c0327b59c5162f5dbca117e81a.nq.gz
│   ├── 389c753a188f4e5918f2daada508a26aecd7a8f4.nq.gz
│   ├── 39e9245cc521b443b9fa0f971fecd6b892fb77c2.nq.gz
│   ├── 3d58b0f0982c0c4f25c25f1e069fb168bc5292f2.nq.gz
│   ├── 4906da718e3a5d18937a433168a5b079209d1c26.nq.gz
│   ├── 4f47b9351b6d6abadd5e67bc7ff443bad67bcec0.nq.gz
│   ├── 56d35b9e984befd37ed56f225301cd3cc7e403d5.nq.gz
│   ├── 611fa23e6f5c3543ed5ab60a74211920ec505b25.nq.gz
│   ├── 6b175594054de3a1411ee5a7ed209820c06d7831.nq.gz
│   ├── 6e85114ed398a29d452a5b6b1f16fa8513c541c8.nq.gz
│   ├── 7021d35ec6d5ee64580958c0638560ec241329f7.nq.gz
│   ├── 72f37346e6250c316ab19717e0fba84a57d0bcf7.nq.gz
│   ├── 78033b6cebbcb3bdeedd558f44d0e56fc12a722c.nq.gz
│   ├── 7bfc57e4f9971426f5e41974cd52940bfc4b1028.nq.gz
│   ├── 898bf2464f480163974ffc95f0309e95af138625.nq.gz
│   ├── 99d5be93f008cbbe3892d42ecb3840dced65e047.nq.gz
│   ├── 9aebd703046718a3a66e7f53d1b45cdeef48ae18.nq.gz
│   ├── 9d07cd9cf143d84905eaaf427544f84e8a9e8d53.nq.gz
│   ├── 9dd169abdbf9bd286b16d21fe40a76beeb77bf86.nq.gz
│   ├── 9ef2c24ee18339e033c7da5417342978f42bb134.nq.gz
│   ├── a728424f26c1fc85d2a38958d0f98790eb78add2.nq.gz
│   ├── b06c59a5f1afb6dd218e9a62c657773e69131d1e.nq.gz
│   ├── b2786f74f65e26b759ab6ce364faf1a6a2c25dc0.nq.gz
│   ├── b4af2dd73f926608bdc985d774f3b132f789e90b.nq.gz
│   ├── b88c2c7e69a0887eff79d18026b62bfaff4c5fd4.nq.gz
│   ├── bf4bcd8324d13e0a7e5cfa91f190bf691a878d45.nq.gz
│   ├── bf55580dd885de40c7bfa942e8d2625b9bb56671.nq.gz
│   ├── c0b544b87b0934feffd2c122c91420ee75da4b21.nq.gz
│   ├── cccc98ef48b668bb9c88c7ba04352d24907cd9f2.nq.gz
│   ├── d5d20ea33486dcfa5f117ccd6c6d88b47e5f1f6a.nq.gz
│   ├── e3b10a467599f09291b22db733115bd0adcbc87e.nq.gz
│   ├── e568a11c326d0ec9d5e3506822e385e55fe5fb2d.nq.gz
│   ├── ea081acacadf741724b16573f05a550ba5d38657.nq.gz
│   ├── eec080d35324bab0c0ec8cccc8f8b1da75d05add.nq.gz
│   ├── f1f34b2e29c73e5f8fe09d4799b8b1b13ce0a60c.nq.gz
│   ├── f1f3a2a8961d65e3f18199e93dde417023c87f1c.nq.gz
│   ├── f3b338ecc1c3e2425b9fa1d4a3d8490df5d2988c.nq.gz
│   └── fd935f9cd437be829ba97b0c1886b2fb03f46791.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c7445887f5e1bcea470a16f61369d29870cfcfe1.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 60 files
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

[tiran/defusedxml](https://github.com/tiran/defusedxml)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
