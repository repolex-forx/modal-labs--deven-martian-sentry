# Repolex Knowledge Graph of modal-labs/deven-martian-sentry

RDF knowledge graph data for [modal-labs/deven-martian-sentry](https://github.com/modal-labs/deven-martian-sentry), parsed by [repolex](https://repolex.ai).

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
rlex download modal-labs/deven-martian-sentry
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2f1e6fe2356885894dcecbfaeb529186dd8be847
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2f1e6fe2356885894dcecbfaeb529186dd8be847
│           └── chunk-001.nq.gz
└── blob
    ├── 001cde9f9d88ea5807a2aef27ab68ce8d09c06f0.nq.gz
    ├── 00b6f09f2a7bb758b369517530a1496dd25fdc31.nq.gz
    ├── 00dfa7dd03133126816f34b93e599863cec4f47a.nq.gz
    ├── 0177e8c05dec51150e6185596c3d3e3928f0d1e3.nq.gz
    ├── 01f42683141a15dbd016c907d550b25ce169c729.nq.gz
    ├── 022a05a731769e7796399e95e0a87180bb9d1f49.nq.gz
    ├── 03599631de17aff9f919c09175bc7a13c08f67f4.nq.gz
    ├── 0429f945066c3eed793732add469ac0c144f4615.nq.gz
    ├── 045d88c5b351fffef2e10b91aeb3281f8704ec77.nq.gz
    ├── 0567f945fee00b3a0d01dce3cc3248db99e24caf.nq.gz
    ├── 06750fbf16c5f6debf4bc8dd8bd496d9d6cbc610.nq.gz
    ├── 06ba1a7efcc0959308d3c3b9e5968a8f7ef2d1e3.nq.gz
    ├── 06eff9a9d4b4bd15e2c5b9b2ba7ee63b45339dc0.nq.gz
    ├── 070438e452d233b3da4e944ae0f00c825c44e176.nq.gz
    ├── 080335ab08827b779f845f9516a73b9dfa298fa2.nq.gz
    ├── 080ef349b163b1ed1c84b24e069e711851872fe0.nq.gz
    ├── 095adbc357782c41def8b60077b44b67b28311e9.nq.gz
    ├── 0961dc4273826858a243ed46c628c96361d31b38.nq.gz
    ├── 0a0eb8d2327c5c99ac98d99d834b9d94d78c5862.nq.gz
    ├── 0a62925f647d8490fc64fb7aca904c97540636ec.nq.gz
    ├── 0af27738b66f03c258ad0e8d3b5fcf8a55eff45b.nq.gz
    ├── 0b12d84442ab0e04f8c5f1d091dc1c0c19277eb9.nq.gz
    ├── 0b8d45b90dff194bbfdd9ca6cbd4ed03c332e111.nq.gz
    ├── 0bb102079d03ce69bd6b81b782b425d0ee8f7095.nq.gz
    ├── 0c1ce85bdb4eab2cf788ed10ca39d98f97d9549c.nq.gz
    ├── 0cc7cb31c574d3bd479a7829d73db0b502001738.nq.gz
    ├── 0d6a81bc90f445aa456325777b445f1d72c28a4f.nq.gz
    ├── 0e409aec4685f133007c3fdcaca3585191b0c129.nq.gz
    ├── 0e4b89fed3c69bc7f8abf6f5fa4b005a7ab2f104.nq.gz
    ├── 0e9d33d323409b343496a1b295d87a13989015d1.nq.gz
    ├── 0f7438d53296ae3d54969fbb3a45e167d54fc2b4.nq.gz
    ├── 10a3a2c6298293ad79e9c022fcdff1a16c41f367.nq.gz
    ├── 10cd10d6605a5876e42ee6c8e4186fe2c3cf6ec2.nq.gz
    ├── 1167ecd806bbb9e0782f16efb64239dc429ba24e.nq.gz
    ├── 11bf8cea7be3f20acda8b8ea8e9509edeaef9cc4.nq.gz
    ├── 12e1ccc0e47aad6b0c00b9fa48b0de66e99ffba4.nq.gz
    ├── 1329a554ab28d4db754f5911656dfd3ce5362c49.nq.gz
    ├── 133508582ad23db2d10b75ee85a6d2d482b9b7d1.nq.gz
    ├── 1475ccc757a17e16865dfb1fd7423582753cbb38.nq.gz
    ├── 1651337dcc153aed4adeb7fbbacc18711eab709b.nq.gz
    ├── 1723613ca0c4bc8995b4d79e08ac0390866ed3ae.nq.gz
    ├── 1761ed0b01524adaf8bc349eaf7ce3e6af216723.nq.gz
    ├── 17cc79f1b8adb348db3b3cd747618da4be64d4df.nq.gz
    ├── 17d01c285e8741ce7e40247332eb5cad7954dc36.nq.gz
    ├── 1826d8cfc7dcf0a19b0fee8e550efb0a8ba5b44f.nq.gz
    ├── 182b0c1172027aca0e2e3940af61e6131e848112.nq.gz
    ├── 18f4d9fde26245fc6bc75c1aee68eff200447c87.nq.gz
    ├── 1b43abbac1942ea1cae9d08e149c372d10d47b1c.nq.gz
    ├── 1b54291326fc8e020486fc2891fefa1fd7a95ad5.nq.gz
    ├── 1bee7dfc781afd9007b4dfd948eb6b520f7964ad.nq.gz
    ├── 1cdb46617767828da0a5679935cfda0a1bcec250.nq.gz
    ├── 1d32e6e44e6ef07a1e7009144c48b09a5a739ee9.nq.gz
    ├── 1d7468f9756d8f1ace7781ac1e6dff3c55288c99.nq.gz
    ├── 1dbcb70042d2b8046e86fdc3dbdf8737816f7da1.nq.gz
    ├── 1ecf694c7e1935b7e62f78cca5ef3bf0a0db7209.nq.gz
    ├── 1f314c24f956804e728b34651e9dd737f34b695c.nq.gz
    ├── 1f4b538f1e1e6bb4fdcabf7eb823c7dfc5cf4466.nq.gz
    ├── 1f86c83e1cfabda3ba512620329eddb8b1bf05c6.nq.gz
    ├── 1f8a7c338a59259ac18361df2274cf45215f80bc.nq.gz
    ├── 20a89b258454a9ee86347862b837f9e26615ed6f.nq.gz
    ├── 20eafed0a3de74c9b4571abc35fd4d70effc2c0d.nq.gz
    ├── 221d8024fe43d4ba8796bc27eedb1d29d02e7c38.nq.gz
    ├── 22756e1e94a8e5633a8f35dfdc842f10608957ae.nq.gz
    ├── 2388e65a7698e58b7d8bb5129ab335e99d1d7465.nq.gz
    ├── 239077fb350782b7b7efe43b6a899bd9b607d5fc.nq.gz
    ├── 23d7668b405cd35eec839df61bfcdde7da36200c.nq.gz
    ├── 2428a263297e8604c57d090f096b4beecbfc64b1.nq.gz
    ├── 24a13abf5f4e3e5132f924c6cfe880fa60c6a3b8.nq.gz
    ├── 24d592f264464cb35103e90310cddc5a4481ae96.nq.gz
    ├── 25e6aa3167959f7bcb12953d3a0659da0480fdcf.nq.gz
    ├── 26065543d39abd49a7ebba0e9c9d189eaf4e5c37.nq.gz
    ├── 26693140f9c17abdf2373eb0b944a67087749959.nq.gz
    ├── 26c6767b0f0a9a3471fcafe5a324c7351cfdabac.nq.gz
    ├── 29234a02eefee86ad26728834414a477f7be7d53.nq.gz
    ├── 2b1d7645da46d4e24576191558e7816d93b62b39.nq.gz
    ├── 2c4103665e765c70b4aa370d26656251caf69ec8.nq.gz
    ├── 2c9ad32c6e0f8bfcc1abb96c7addb6240a519ac6.nq.gz
    ├── 2f1f3936e3af551678d5b63285cbe01a21f5eedf.nq.gz
    ├── 2f2fe203695402967e469a6d10441da6abbf959a.nq.gz
    ├── 2fbdcd0dad2d15b38e761a2cac70053e6f9e3663.nq.gz
    ├── 30737787feb51f02884cb3e069ca339bff5d1595.nq.gz
    ├── 30b6836efc96bfd4ff7a7635b83ae509a67ae8eb.nq.gz
    ├── 30c2b17ecbb2b089b1f0504e694d03d63aa325b9.nq.gz
    ├── 31c1930d91fb6a4bcf89b6bb2e9cf92e63a01f54.nq.gz
    ├── 31e8dc26980a808cb3db2c2ea9d0c8c195ca6fd9.nq.gz
    ├── 326bac854cd0e8eed9a98ce8d3942de668218687.nq.gz
    ├── 32700df440935f690d42fa28d4898fdd55c47388.nq.gz
    ├── 329b439db89b0f1d92db6d07596befc10d08f956.nq.gz
    ├── 32b86a49f84cbe8faca11f547ca020e6ba58a401.nq.gz
    ├── 3388052098217ab9a6266f601f50102679130ce1.nq.gz
    ├── 3483a54c8479cb9d369e268ba34fa0b7cef21bfd.nq.gz
    ├── 34b18b6400e586281516180c3bdc1c211aa51828.nq.gz
    ├── 34cd3a6d01ddb3f6be6950d8c8fef71af2defd81.nq.gz
    ├── 35b258e1672b6e17b301ed35ac10a6fe150e38b2.nq.gz
    ├── 35d3d086ff4cdeec726b68cba4532ad19d366010.nq.gz
    ├── 36640f65c2f8641597202172a3cbdf384971628b.nq.gz
    ├── 3671f90067d12c4d4afe4680b215b8c061371f16.nq.gz
    ├── 368bdef446b283575aa72674045162081fc14019.nq.gz
    ├── 36ab0e1b707df53a60813d2ffc0f18af4b5d4c21.nq.gz
    ├── 36dd070c49b8a1444aa7ffb85c8b253ac5aed487.nq.gz
    ├── 37eb3cd48d766dd7dc2ebd441f87ac084c3e10f0.nq.gz
    ├── 385d1fe0dbc90fe950f57af7432f1c42838aa003.nq.gz
    ├── 38c6092a0e186b9347396dff389c26f5369a3720.nq.gz
    ├── 397d811748d5407dea4c749a98961b06fac7ce37.nq.gz
    ├── 3a5c9283014b38cbe9d80df3254baf0fdbc68778.nq.gz
    ├── 3ab508999f0935e28c36fd7f55f92d7a284ef0b6.nq.gz
    ├── 3b15df3a88d192a7d3dd6ceb4eb899331a3724ce.nq.gz
    ├── 3b7e9cc5f81e2d8c046b8bf34987c6d18db1429a.nq.gz
    ├── 3c02472c68e2b4e56d3b557e0e1db15c36932028.nq.gz
    ├── 3cbb86d2f42f0ec4d36b7166b7d493e6f766f358.nq.gz
    ├── 3cfb60dc87dd330db3029b3e8588c0880f831d74.nq.gz
    ├── 3dae7f9e88e3c26d83230df5a4554e23af990531.nq.gz
    ├── 3e08e57a21ac767d60409ff6dee4b0dfcab96ef3.nq.gz
    ├── 3e74188b47a1154a4ffb0297e345800d3ab3882a.nq.gz
    ├── 3e8cccb9b50c930dfd0b76143e999611a8a39cf7.nq.gz
    ├── 3edaf3a0d01af1bf67e27734f8257ed7b59e8b96.nq.gz
    ├── 3f40d6a89b22cd4128350118c1a935643f2a8bdb.nq.gz
    ├── 3f96ab2d953a741312fb224674ae220434438ea7.nq.gz
    ├── 405a859993a909c80a61e71e39aee4e420872663.nq.gz
    ├── 40d57a87ec7de83d6ad3815c41939cfe41182eec.nq.gz
    ├── 40dc41db52a0b6071de42802cfc1281005f6b574.nq.gz
    ├── 411ed4d570c39ee61b0f59c4995644b014516a26.nq.gz
    ├── 4155dca02eae0a6d926236b2cacc37d75e62a066.nq.gz
    ├── 41595d84da64e62815726610e7a93cc5e97b36e3.nq.gz
    ├── 42c3061181341e29360d4d9de891d29ce94ad91f.nq.gz
    ├── 446960c55128a8912d4f49a5af0e7b06bc03f75f.nq.gz
    ├── 44a791ae94624723f1d0ca4f3afb4c14cf51eed9.nq.gz
    ├── 45a1eac2a1ec4d87cc570054fab23596536c38ec.nq.gz
    ├── 45dfe81f83fcd7d089da777e75e4ddd0f6bfa6f5.nq.gz
    ├── 45fd3d07de966802726c84756be57e90477b76f0.nq.gz
    ├── 4756273a72247572a2883c2f47f41b22c2ecb494.nq.gz
    ├── 48952fbc08e3ae62e5e85ccec7a42fbbade07406.nq.gz
    ├── 48a207998a3402cf9392e07bb7db3c9e79a6bf8f.nq.gz
    ├── 48b502df50c4607e765308b1a87d3c038dd6cea6.nq.gz
    ├── 48fd9272f41c4a42964cc1fbf638d2b97f693a16.nq.gz
    ├── 4a5e3e51ebcef70d13b667f043e72f6b10926259.nq.gz
    ├── 4ac141ff226916c768941ab4ea582a436167eff8.nq.gz
    ├── 4b8451a0e306fdada182086f0e13442996f34c9f.nq.gz
    ├── 4c9a86640ddc8496b70428a73f4a8679c5bd8599.nq.gz
    ├── 4d216e7493c7343a6f57b9babea2c1ab09222809.nq.gz
    ├── 4d41fe79e72bbef4cb19da57d643a17dceb50acb.nq.gz
    ├── 4db2290bc080f5cd6afe6aa3ed2910f28deff9e8.nq.gz
    ├── 4e266973e53b6cd500e3abbc80851d55c2a9fc13.nq.gz
    ├── 4ea6a209db56d92f1c35f1002d096cfc3859f0f0.nq.gz
    ├── 4ec12694f1b27762bc553834680c28c4c3a78ec4.nq.gz
    ├── 4f0741f999c94b7acb5a8bf585a8fd9c9978868a.nq.gz
    ├── 5029abaee56225a12154177f4622bec40093c278.nq.gz
    ├── 507384975b0c9853b16db11122f0da096a96c134.nq.gz
    ├── 50fd03536b3e5d714b8910418c7f5de3d0f4a45e.nq.gz
    ├── 51359ff1f994a81f75649ec45a4999cde11e1719.nq.gz
    ├── 51565fd889ac1e6b8e62f390bffb24c5255a4a42.nq.gz
    ├── 51904b70366cc092f4e224e3fcea280f2a9248b8.nq.gz
    ├── 525ce1b9b56a5af381d0dbdc1d8ef316b5a64d69.nq.gz
    ├── 528b4f38951beb2a26c786928f378d166182aa40.nq.gz
    ├── 530956545dbd32f44589d5851f878bf179c30b66.nq.gz
    ├── 5358a949d024971411fe4cca793d44655c810f63.nq.gz
    ├── 53ac5016c8b4074142589f31e8495987b1197fb3.nq.gz
    ├── 55281fda900d726e18120f8cfeb139a3f7cc6504.nq.gz
    ├── 5547febbf9f1d82b9c20afd9eb8d87f09bfe81c6.nq.gz
    ├── 55a3b4900ccea5d1d088a2d1fe9e02a19d1e04a8.nq.gz
    ├── 56f9582da62826dd9a6374a219bf92a934d76005.nq.gz
    ├── 58174042cc841c92019654e17dab2e91e2e8cb74.nq.gz
    ├── 581f50b99ad7f30321da60ee79f20b1c92881fcc.nq.gz
    ├── 583ac3888d9ae7c0a238379d169e465509194521.nq.gz
    ├── 58695f6766cc721ac93939d7e28ec5d9b0ef7c3e.nq.gz
    ├── 58aaf3b192dafe53d8a4522dcd2db56efc9d6a78.nq.gz
    ├── 590419285f11cb597ff515d85f41a6d378fec1e6.nq.gz
    ├── 59d7890e960e183718e2c6d2da2136392c327d3f.nq.gz
    ├── 59ea3c75cc45a82831ddb2fa9e5ab1b7ca217139.nq.gz
    ├── 5a03eec0418a3af81a216b8e0d8fa656d15f2bf8.nq.gz
    ├── 5a03f5366ff627fbf2e32ce1704faa532ffe9efc.nq.gz
    ├── 5a9f1724cca8b84cf6d26bb6e43247d0d6085b1b.nq.gz
    ├── 5ad53c2cdac95c529aee2741074b0ccf6f0bda32.nq.gz
    ├── 5d3fc7abc0b667636e4f4814d08f887d976511a1.nq.gz
    ├── 5df85ee4a8a03fa0f93c39eb924274d08794ea4f.nq.gz
    ├── 5eb50b6958734abda0e39e969009f36b68e2c3b5.nq.gz
    ├── 5ed620898e648cc19bb6a633b382b430b0d578fc.nq.gz
    ├── 5f8d5ea17ce50fa772f084b5bcf4238a1d9666c2.nq.gz
    ├── 5faf2b8ea5d1286232864f9f7562e269faafce39.nq.gz
    ├── 5fdd05a3091ab789ef2e84d188b76a276c5e893a.nq.gz
    ├── 5ffb930ad82815103b31434bd527dfbd1291b14d.nq.gz
    ├── 600712655da694cd1a165bfaf48c07bda4585bcb.nq.gz
    ├── 610949dc3684c5db368372243e39db387bf89bc3.nq.gz
    ├── 6201491c41d2795600947c77996d6746899207dc.nq.gz
    ├── 6235236d6d14aba1341bcc8ba42b7a2942797d03.nq.gz
    ├── 62cea72e6fe23fd8fbebf207bbd9cd58e93941c5.nq.gz
    ├── 62e4bfc37e56ef04ebf086dd4cb3ac343b470e63.nq.gz
    ├── 6367486e4e9187cc4fee4daecea8209b945a68ac.nq.gz
    ├── 63c54be9d5682d578e11a52884e5a0000f8d5e81.nq.gz
    ├── 63f100404c41fc7a36551af4d32d0bbd35d6e1a0.nq.gz
    ├── 640f8ca5569442158a4544cff6aaad071d3b6564.nq.gz
    ├── 64afdac1c1cf57399a77feb9bb13f159f1b7d6c2.nq.gz
    ├── 6550a56eb4a41b2c301efaf95aad178f97fe6c57.nq.gz
    ├── 67d3b45f4533a2625eed0d239c279a38846da04b.nq.gz
    ├── 68c8ec3f9ff1103f40ea86b43b4cfed2f35f1d89.nq.gz
    ├── 68cce6615a90d41e9ea0d9df66c2220079b0b7b4.nq.gz
    ├── 6a90835f1ece0e8a8fd8f18eb60d8dc797fbc72c.nq.gz
    └── 6aa6202a96fab4236b0774cdad2c443a3b87b7ff.nq.gz

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

[modal-labs/deven-martian-sentry](https://github.com/modal-labs/deven-martian-sentry)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
