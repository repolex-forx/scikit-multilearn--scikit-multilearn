# Repolex Knowledge Graph of scikit-multilearn/scikit-multilearn

RDF knowledge graph data for [scikit-multilearn/scikit-multilearn](https://github.com/scikit-multilearn/scikit-multilearn), parsed by [repolex](https://repolex.ai).

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
rlex download scikit-multilearn/scikit-multilearn
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2ea8c414d6e11ab2b5b5d03cceb3f56ce8fe4215
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2ea8c414d6e11ab2b5b5d03cceb3f56ce8fe4215
│           └── chunk-001.nq.gz
├── blob
│   ├── 03bfbaad7155af18aef397db027ec2804814d2fb.nq.gz
│   ├── 06e585743855a30a1f03c8ae0a965375c8e76b96.nq.gz
│   ├── 089cd8019e3dc87c5d7154804375c1e0c9235354.nq.gz
│   ├── 0a4b97db9e7bb0bfedc0a965e112363cb00cfe39.nq.gz
│   ├── 0b9144f1ae06df415745a582b1630f359c19e458.nq.gz
│   ├── 1081dc1439fb984dfa7ef627afe3c7dc476fdbce.nq.gz
│   ├── 1169f7f7b8df98479b438689fe3a47cb22901497.nq.gz
│   ├── 1298063788fc8bb897c8b5b767e3252194fd2cc5.nq.gz
│   ├── 1300f2dd1c0a7d87649ca922fcaca90981b3b7c8.nq.gz
│   ├── 13bc5b765aeef20e00df74e9c5cf04334e54d261.nq.gz
│   ├── 14c028fdca8908c563270678f538343286447a93.nq.gz
│   ├── 14f508c613d3af352c307a73393db142abd3b648.nq.gz
│   ├── 16fb47a493decd0ccc2bf4abc880e7baa61ac94d.nq.gz
│   ├── 18bc4939147eb981c294eb945d70fa770edcda31.nq.gz
│   ├── 1a28f43a807c0b087d020ae353d06f858d617387.nq.gz
│   ├── 1a662db9ba8ac2a74dec6f50e546dbd16e5f5850.nq.gz
│   ├── 1b08d7b1c8b5737283acdfb354c7004e2ec72330.nq.gz
│   ├── 1c80bf9643ce8496561ce6ce9accc05a643a83c9.nq.gz
│   ├── 1cfa71ee0a923a801ad157915882574f19edc93d.nq.gz
│   ├── 1fab2042b9a91a304a3f65e8f740b51d914927fe.nq.gz
│   ├── 1ffc2ef58c727a360fcd43a25da52981d2ea88eb.nq.gz
│   ├── 20fbfbc7cf9c25e160359b520ddb46dde65d6ea0.nq.gz
│   ├── 212b6779b9dcd8b125ae9d9c92c3ba8a01fb331a.nq.gz
│   ├── 21af0751292aacae5d01544f7c1ad363a1a674ca.nq.gz
│   ├── 238097b094eb0543e08646890f515cc73da4939e.nq.gz
│   ├── 284a6ff900323ae3167c0b4b3531f6d242430d84.nq.gz
│   ├── 2a06fb044db3c88ebf89382e414ef92b622eb5e8.nq.gz
│   ├── 2b0a41ac734d2dfab67a8bc490ba0f85aab006b8.nq.gz
│   ├── 2d0822c3b623551991066f0365ba50cb1d8192b9.nq.gz
│   ├── 2d9631f9f0539281b9a4b3a3bcfa293649c3a680.nq.gz
│   ├── 2e1ded71cf8e49b801f4510efb8e7585fb6fc980.nq.gz
│   ├── 30346aef89eefc2b57c839c23a8e382100941961.nq.gz
│   ├── 31fefe67362396bc6b2322ae01a9d1f1957f5a30.nq.gz
│   ├── 3237be8aee98c72f2031db93f34d2f4f1b3849b6.nq.gz
│   ├── 323b73c6e73b7ce9a3e8b9527482a8ecdda5db9d.nq.gz
│   ├── 33f7ffe2a5f49bdab22e735b0880ae84c0ccc636.nq.gz
│   ├── 34792e66c6ccdef25f01d7b4941adf8cd64a6758.nq.gz
│   ├── 35251685d07def2904766dac29630dade4372726.nq.gz
│   ├── 362b25e0a3f23a2934370a7993de44247955d27e.nq.gz
│   ├── 36510e39acbb01e581545c605888377e2a39ed7c.nq.gz
│   ├── 38abe924680010e0cb10c6f7b5a2f508ea845f4f.nq.gz
│   ├── 3ae7becc7e58cf66f1fe089a612effe521243842.nq.gz
│   ├── 3aecf77d8984a6c1fffb3ebade36631675125c0c.nq.gz
│   ├── 3b61fd006647ffef5dce991dbf520453a287998c.nq.gz
│   ├── 3f8b67fe7b33d9b060caf3f8defa8a89cbdbfc3a.nq.gz
│   ├── 41350c223ceee76244ce728cdaab2a135dd2ecc7.nq.gz
│   ├── 44c59c5c41bb54b73485843953edff9f76547a63.nq.gz
│   ├── 4576359cb8cfa4cbdbfda0248f6889ea518db651.nq.gz
│   ├── 45a3e80bfc7b29a6d3347a7e452257dc89fe3de8.nq.gz
│   ├── 46546d01de8662c0aebe72ead27b822dab0aac19.nq.gz
│   ├── 480d2486ac198a987a9746702a669be675389867.nq.gz
│   ├── 486bc81545653475df2fdcdb4bad6690758aa8be.nq.gz
│   ├── 4887dfbbdd656f0bddc57ce956c4b5e9adb2b6ee.nq.gz
│   ├── 49b45afa6d3817570f576539e5d68fb035d10c31.nq.gz
│   ├── 4c2ff3f9f402c694de42ed7fbb6726db9baa6243.nq.gz
│   ├── 4c70c7ba1202c593e7a7180e3a3acc711260974e.nq.gz
│   ├── 4d9b3a258759c53e7bc66b6fc554c51e2434437c.nq.gz
│   ├── 4ddb8182c121ee15d6ce3d948199808705d62d08.nq.gz
│   ├── 4f4be476daed44fe2defb0e2804bee55d15b3fd4.nq.gz
│   ├── 544341a5b9d17643ab7bbec2a94367903a55b605.nq.gz
│   ├── 596369c682c6ff251676277d782346f2c4a77ba3.nq.gz
│   ├── 5a9eb5d0815680b478a64206e9ac0cb5ecac084b.nq.gz
│   ├── 5c6c81cf4552d2c4ca0a8e84e80555693766ac38.nq.gz
│   ├── 5e056400aff60a2541e91e5a8cccb9c75f00ba41.nq.gz
│   ├── 5e712a2ab52540b47396493cdd28d150cee32407.nq.gz
│   ├── 62a701a97cef5b26e122d0452f68d759f35c18ce.nq.gz
│   ├── 62a8902ba94a574b42418b10624e817266395272.nq.gz
│   ├── 6955636ea112b79cc86ec257050849064d038375.nq.gz
│   ├── 700191343f27a441755ef29a874c0749a1d28bfa.nq.gz
│   ├── 709da1da083dcf18c9fc1bbf89074531ba4648e9.nq.gz
│   ├── 724ecaf8bf0022f86654dab450671070bdb88d8d.nq.gz
│   ├── 755bc5af28ebf8e0689852bfa9600cbf72a72a4c.nq.gz
│   ├── 766817500951e5275b4bbe513a15c7d4421e39ac.nq.gz
│   ├── 78c742198e500155a7e248a0b6e440ba89ba5285.nq.gz
│   ├── 790c10e9f940f6218d55f2120d3897455f6c9305.nq.gz
│   ├── 7a5669dba3cc2a83fc5b1b3fd6eb9848806645eb.nq.gz
│   ├── 7a86e0bb61d949a33176a76fa2b5d56b65b74f91.nq.gz
│   ├── 7ba1493e92894bf1343751889fa57473987d8bd1.nq.gz
│   ├── 7bad047fe12b1bd276da0d6929490c6d1392c79e.nq.gz
│   ├── 7c4d03768899fd7e99a68cb61d43b16c25a1da07.nq.gz
│   ├── 7ecaffda11d911b35644276348164dd9070f70d6.nq.gz
│   ├── 7fb82154a1748d507925865d3fbf7508d62483e5.nq.gz
│   ├── 89f478117097aeb284eeda7fcb8297ab0c764fe7.nq.gz
│   ├── 8a265a03e5458ebcebcdf2c26540c5c1abfa5c65.nq.gz
│   ├── 8abe27b97fff27f2e7ea274d8bd8e91592c2f906.nq.gz
│   ├── 8d822267cab0b0c56681d413f38fe63d7a43d47d.nq.gz
│   ├── 8ec57fe74b4c29bb507a8248804ddc2086a27974.nq.gz
│   ├── 8ecba8669476f755dde6df800d09f2e1c5a5e3b1.nq.gz
│   ├── 92036977a8c0fe6162fabec10a9548a0b54d5ca9.nq.gz
│   ├── 925d44f743a429a1eadea0b82c0a370aaec8a7f7.nq.gz
│   ├── 95756a6237c3674ed68c86e7be052dcc39eadc68.nq.gz
│   ├── 966bd38e890d766a1420a268763463d517288688.nq.gz
│   ├── 96737e664e223edd1da0a3e2c8d4f899097f9b59.nq.gz
│   ├── 976339fb667245b4ce091f20f421789f6637518d.nq.gz
│   ├── 980f2068a3a158dd047ac776b922b353b38afc06.nq.gz
│   ├── 9873377c94e0f122d3baac347f73664194345eb1.nq.gz
│   ├── 9a950c6e87732635380de161a11275acc5065a3b.nq.gz
│   ├── 9ac37fc4234d167cef000c52fe9721c65a97b7eb.nq.gz
│   ├── 9b41ad601ba047080c09b623bfe9d92530a17bac.nq.gz
│   ├── 9b600acd3ba32c9d2456e4f36cdd9e2020e1398b.nq.gz
│   ├── a06c21bc8432e5c4660aaea35a19b3e35cdda8f7.nq.gz
│   ├── a165133f3ed1b95acde685e1ae3cda720a5c3ca0.nq.gz
│   ├── a1dc30179527567d36a0b4b8ec5517f347ea9f68.nq.gz
│   ├── a31bbebd46de7a6a49a009fb51f2f27cd5bfb718.nq.gz
│   ├── a6024b07b843174600954c194422d904e6324266.nq.gz
│   ├── a78ef3f3d8d755647dd1e4f28c7285eaa39a1f38.nq.gz
│   ├── ad69b5c9f01fdd925ef46d37bf09fbd9053d790f.nq.gz
│   ├── ad8e27242fa60dfa9bab8553804fde6e09ca1a14.nq.gz
│   ├── adfc3673c9fdc000b3d49fccb52a97633632ad41.nq.gz
│   ├── b065f027d54ed9772ccfc88436a1b886671ee61d.nq.gz
│   ├── b197d9ea151d598a034c04b9ae48d5c7303a49d0.nq.gz
│   ├── b2e3615778f60829f06cd502b1e73339efb47259.nq.gz
│   ├── b43b521763c61027a217ceb81c17ca30616780d8.nq.gz
│   ├── b6360db5a36b9276cd78d437b74bb861b03d831e.nq.gz
│   ├── b680a957103cebb61a37e94b55e4f27261567e69.nq.gz
│   ├── b945094b691ed0aa5c477cf396a0cb8bc0f42c86.nq.gz
│   ├── bdf7d0d5b5a2cf2aeae2bf43537175aa027b55cc.nq.gz
│   ├── bfd9c221a57692c6cef406a1b2ef8f19324b21cd.nq.gz
│   ├── c15cdb80a300592844603a14bcb5f35545e9f433.nq.gz
│   ├── c48eace989395b06c1fcea47a1855ea43312a655.nq.gz
│   ├── c6b1cb7dbfb642da6188fbabe61fc2ad47ec2ed9.nq.gz
│   ├── c6d85bf9e0895a0a5c7d2ff64554ba7c6063af9c.nq.gz
│   ├── c7e04cd2fb11c1428cdeee30db37e862de7de99e.nq.gz
│   ├── cbc63672ed0da4d61862bc0dd4dfaceee0b43f6b.nq.gz
│   ├── ccba3d9f151562a3d131ddd8008df296375eb30d.nq.gz
│   ├── cf8eca73f3fdf1412b605e496c4451c0f82ce7cb.nq.gz
│   ├── d38a9f95b9ba40df915e8c85e25583ab7b3ecc7a.nq.gz
│   ├── d5f125edcd474ea163c55fcaf98d56e905537efd.nq.gz
│   ├── d8a37d24e41e752179bf612b37601a8ddd0cd9ad.nq.gz
│   ├── dd29f38ff58ff33daafcf12bace185298fd71024.nq.gz
│   ├── dd9b9286b0fa6865c352eeb64040aa76c6edc729.nq.gz
│   ├── deeec6e17cb055c9354d7a18e8bea249a9182021.nq.gz
│   ├── dfcf3898a4caa7e8e4aad1c82c871268eb97900a.nq.gz
│   ├── e0b575cdaf01aa31e10bfcfeec8cde30b24f5e32.nq.gz
│   ├── e1a96e49c3085ed803de64432dc57a5320135d24.nq.gz
│   ├── e1ec4e525d7ff053171d2430d895e65517affd6f.nq.gz
│   ├── e2883939a9902c941ad3cbe756dbc7faeddd8325.nq.gz
│   ├── e34763968c262de5bfa4cf0e0bc33d6edaddc9be.nq.gz
│   ├── e36ddacee4a1dff844505420abf6f67920f0fc1a.nq.gz
│   ├── e455d6d7c17a4014b02d6a79cfebd2173903bb79.nq.gz
│   ├── e4e909d99a77c1b2561a10623300f7622a25443b.nq.gz
│   ├── e61b5746a4cd098b84ef51fb7965470b46fd9176.nq.gz
│   ├── e623858bb936e38d78d3114b2ad8354f83451abf.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e841cd2def21debbaeea6d74cf602b4c95061546.nq.gz
│   ├── ead9b3dbb0ac7045001b5bd4475d6542d113abb3.nq.gz
│   ├── ebbf4850ceff9c84cb9cc5a1cb9c0f740b4415ab.nq.gz
│   ├── ec119bc845f4cf2447c14f25a03e013d8b70ce8d.nq.gz
│   ├── ec7299653cc366b19faa516fe16a49f8358c5814.nq.gz
│   ├── f021fe30ae52ce81dd56eba8354a94aa21828072.nq.gz
│   ├── f2a21592d11d1d538ee974333dc44131b1f5f7c8.nq.gz
│   ├── f45ea544357e949c41e198a418addf90b5328669.nq.gz
│   ├── f6bb35837b324e0d64f8378aaf89c8cb76110153.nq.gz
│   ├── f78cbe41d0da219a85b4d61b251fb8725dd20b7c.nq.gz
│   ├── fc7156065e93135829433bc5006b36edb255b408.nq.gz
│   ├── fd6299661d46f80e6d3f487dd1fe3f810a4fd5e7.nq.gz
│   └── ff7a81eb728ce50870e97f915cdb1632e129255c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 2ea8c414d6e11ab2b5b5d03cceb3f56ce8fe4215.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 165 files
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

[scikit-multilearn/scikit-multilearn](https://github.com/scikit-multilearn/scikit-multilearn)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
