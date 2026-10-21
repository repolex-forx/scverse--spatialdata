# Repolex Knowledge Graph of scverse/spatialdata

RDF knowledge graph data for [scverse/spatialdata](https://github.com/scverse/spatialdata), parsed by [repolex](https://repolex.ai).

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
rlex download scverse/spatialdata
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1d5dcbebcfff610e2db2ab807b2076ac749eae94
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1d5dcbebcfff610e2db2ab807b2076ac749eae94
│           └── chunk-001.nq.gz
├── blob
│   ├── 00ad6a6ea9418df96256615a564065e38c8332ea.nq.gz
│   ├── 00c6408c710dc92b82b4e999d75661f8d4d5e5d6.nq.gz
│   ├── 00ca6494aa076d345f1aba939d2a78031319bd7b.nq.gz
│   ├── 01db9dc2d9448aae100bdb10af99df9bfc8d91ad.nq.gz
│   ├── 031f1e4805797686ab5df202f2ae23e0cb58c905.nq.gz
│   ├── 032c89c13fe6157bbf97d796a7777abfd4674dcd.nq.gz
│   ├── 03d6e6d999f29c2e0725d1ffa004b37eb838744b.nq.gz
│   ├── 0475811114e5f4632901306945a945a908ba6dd8.nq.gz
│   ├── 07d232559eb0272305c285bcc16539ce76c78147.nq.gz
│   ├── 07dff152cf59eab008ec7ba89cbbdd478d9a9ba8.nq.gz
│   ├── 0b117a7a8810ac703e4c65dec045d83ea34ab67b.nq.gz
│   ├── 11957ee1c0ee9e590ae4c3e8b64e7aa926379bc9.nq.gz
│   ├── 15a0096e18b703d7d94d9c0987dbbf9a0e317968.nq.gz
│   ├── 1758159bf22717d58495cd8edc50c5754f514df3.nq.gz
│   ├── 186d7c9743aafb5b75bdf4a1c582daafcd60c339.nq.gz
│   ├── 19c70897725430efdaabf25afa3b1be0a3c13ba2.nq.gz
│   ├── 1a672eefc11f3aa15a4965a59b38268f74054301.nq.gz
│   ├── 1d85ee8b84029e99e3a82fdf7be53ff765d3f1bf.nq.gz
│   ├── 1ee2c98d6a2b4db95258c260374da32df3046622.nq.gz
│   ├── 22dc511e536fb198dbee2a9679ac064ea3532237.nq.gz
│   ├── 28a19d0630b826c31dd13515600cda9c1fdd6b72.nq.gz
│   ├── 2a68ab7a26f9c0815785783183b2b13a1e1a7eab.nq.gz
│   ├── 2bdb68b55b38db4761ce0c448337063c5d06efd0.nq.gz
│   ├── 2be5f256f66a16b4bed3c39cb883d4dca481e0c3.nq.gz
│   ├── 2da0903a86da72aece6ef0cb726e45f10dc377bf.nq.gz
│   ├── 2dd453fc486e767d7e9e2e6f223871ef53db4e2b.nq.gz
│   ├── 2f14a7802679f365926652b856ed59e0f01686f7.nq.gz
│   ├── 322793040792b8440f6bb6db6e29660b8e54b266.nq.gz
│   ├── 322b6ad502343ca01df5f5ca1dcb3996eebf1613.nq.gz
│   ├── 32b81b1bec529afd7ca143c58bbd56cc7c775746.nq.gz
│   ├── 32f05834b7433bc3b5046dca4277cc50ab4fde07.nq.gz
│   ├── 3314508087154f324217e3b0dfab71167b18cb68.nq.gz
│   ├── 33c3807c3f5575af941f511e81c82dda567bda77.nq.gz
│   ├── 341f66872f3cdc548e1a7fca924d9860cbd202b1.nq.gz
│   ├── 35b96e5f75e421ddac5dcdc3c5308ae58494082c.nq.gz
│   ├── 36d1874618b1d0099c4d192c8a90500d69bcc723.nq.gz
│   ├── 37e011e821eb10c33747bfa7a1adc1e45900393f.nq.gz
│   ├── 3806fabf768801197f7c0b2ee6530166019286f3.nq.gz
│   ├── 38ff8c6bbf277f24b5dee4d49fc68babb3147e47.nq.gz
│   ├── 3b6ff358190804b18b67ff4a99eed66e28dfc370.nq.gz
│   ├── 4070fe995018e1197f073504cd3679ed32defe7b.nq.gz
│   ├── 410e92fc3763438b6a1b0d192a120c1219bcdeb5.nq.gz
│   ├── 431bdbd17c679872974625b6c071ec2d5804da5c.nq.gz
│   ├── 474b658ba3d75d3431c41739e36e6b609428a37e.nq.gz
│   ├── 492cda8d278c2c193a21fff68754976370eca96c.nq.gz
│   ├── 4cc02bcb41b881f6894569e2a536452d9e747a7c.nq.gz
│   ├── 4e7a902b7c88a42799f3ff3c58be48371136f219.nq.gz
│   ├── 4ee3210b7f2353ece8e8eb0cc1692ca3f3db8cbe.nq.gz
│   ├── 5277f5d7827f89f7a835397b6de9aa10029b72f3.nq.gz
│   ├── 53d362d1561531ad5e9a60f1e1eb38d747d110d1.nq.gz
│   ├── 549574164a4e17e3213ffa89433da02321231fea.nq.gz
│   ├── 5683233e5e86b478e62495b93ce16d32d635f36f.nq.gz
│   ├── 57216b9bd5d5fd3c3c27d9895249dd8024370cd3.nq.gz
│   ├── 5774a30cfc02f2928824d69a6dbc972d5ac7e366.nq.gz
│   ├── 5af8369c5566820678390a917edef4099848b110.nq.gz
│   ├── 5b62547f9aef3da3a38806baf365ea8c059675d6.nq.gz
│   ├── 5d5e96086996efdcca3f6fd729a919150e0c4c51.nq.gz
│   ├── 5eefc02a6bd8d47fc4415639da8b3f37e1a21674.nq.gz
│   ├── 600dbed753a4033331219c6a9b9e3b02ac022541.nq.gz
│   ├── 62e151d458691629cd48ba3768f7359fd842bf2e.nq.gz
│   ├── 639d1051eb84797dc09c2bc3d3e77330a1035994.nq.gz
│   ├── 66f5802b7ac47e87fc068e4878ba21a83995a290.nq.gz
│   ├── 691ed765b8074880cbc7b8cace927ccb7f4d84e5.nq.gz
│   ├── 69bd48cd9fe48c450b3a758ab170825d23e9be58.nq.gz
│   ├── 6a8fd47a0cc47f372c577ea35114e8aab0a7dd08.nq.gz
│   ├── 6b6607e8090af9df9c6ddc6ab14d89fdda66c572.nq.gz
│   ├── 6cca7d4d7e6abb71f96dcedb6fb5ebbb8ea0eb66.nq.gz
│   ├── 6d15de398c4c93d69b9c8d40d5a61b1abd026300.nq.gz
│   ├── 7051f3646a3c5714a7207f37946261c584710a5b.nq.gz
│   ├── 714f4ab22fe51422c98c195eaa4e48e8a6a3b334.nq.gz
│   ├── 731044ba34695c7650683584b57719ee3ef8eceb.nq.gz
│   ├── 744ecec5262e86149799d1894356c1dc7e6bf1e0.nq.gz
│   ├── 77acf437c79afefab321cca2cefe663fb84f8a27.nq.gz
│   ├── 7a61d237f3236e61153a699fc7785d1b8e64c5c7.nq.gz
│   ├── 7f92f751b55e0c568fea54cb8664b838732fa47f.nq.gz
│   ├── 816382508c8f80e1d7e62dfafcb5f6aca80adcb4.nq.gz
│   ├── 833406d3949b406c451ab367aac78671dea6c5f8.nq.gz
│   ├── 846b8b0560236ce5d02fe2c21c7e58ef48968c09.nq.gz
│   ├── 84e7e598b7bcd59f69c70bfc79b295b835f792e9.nq.gz
│   ├── 89658c92a5ca1b0e669c0bcee95989a8ea6e9279.nq.gz
│   ├── 8a150071a417737a98ab1e6c2533f6460847350e.nq.gz
│   ├── 8cee13cbac7e0d20a4db10d5fc2ae031ecdddab1.nq.gz
│   ├── 8ea535bb37dbdab422fe3716515389ed15612e0c.nq.gz
│   ├── 9091cec381124065fe7da858d0e61723fe94d931.nq.gz
│   ├── 937fc18e8eed4a380beae2f155a6764064aaf19a.nq.gz
│   ├── 94107c9379c4724d860992def9b10df87a3c3dc3.nq.gz
│   ├── 94f2feaedc9c4478ae6859b18f21ac6cd3946e37.nq.gz
│   ├── 955333fed611c591e275fc6317fb5add6c719a03.nq.gz
│   ├── 96e7032dd0f30cf593034242b78b26b9ef09810c.nq.gz
│   ├── 972e2d9be628268c9cadf5daf5e1120e5d3c3303.nq.gz
│   ├── 9830ed4ebcabac06609576494c6239d54e8c5830.nq.gz
│   ├── 9979b9f20f54d916c16580dc19269368099ac264.nq.gz
│   ├── 99eb383aaeab549bed68d9e024354185d0b3c889.nq.gz
│   ├── 9d48db4f9f85e1752cf424c49ee18a6907c3f160.nq.gz
│   ├── 9dfd613b3c48c1eea68dcdc7aee5bf0f6e5e1fde.nq.gz
│   ├── 9f5c91c7a3dbd244457aa690db4055c0688e64c7.nq.gz
│   ├── a0086b7b283ead8f738f9059d35d5b9f376cc4bb.nq.gz
│   ├── a07af27021bcf31ccc901690ef80bb17374c31e4.nq.gz
│   ├── a0faf14ccb8162c5fa8ac588db66ceacec4ebc73.nq.gz
│   ├── a2af02515ed9c510443abf6c64adef8d46d4d053.nq.gz
│   ├── a450ec66432fa901de7379bdb878187bb350455b.nq.gz
│   ├── a5ce9024775ff8180b2fa5721fc13429c9a8ffd3.nq.gz
│   ├── a9aa21ad3babcf4147ba8fd47adef8c4f35eda62.nq.gz
│   ├── ae1412fcc270f5d03a131e8b5452d931e99b8cf3.nq.gz
│   ├── ae6e531f66fae357bbe8a5b6bb30b290c8af59a8.nq.gz
│   ├── afd80765783a175dae81a7603146aa21b7d6230c.nq.gz
│   ├── b0368a12a097432879372b35baddfd6b9c67f354.nq.gz
│   ├── b0738dbffd562b946225517c1001619e0cddc51e.nq.gz
│   ├── b0a6c16f6b088af0cc00177cea08911d60e52581.nq.gz
│   ├── b273a916ed0c42d0a4915f1b5e9984ca19d9d36d.nq.gz
│   ├── b34ad5bf546fe150f6468454d9ab453e2c7e6786.nq.gz
│   ├── b4772df1b6dd5faecb8adfab7528e0d0fd69fc2b.nq.gz
│   ├── b63b43616ecdaca453c9d6632810f23523f38634.nq.gz
│   ├── b7cc4ba3adac2cbede1023d0cba7829b6c253858.nq.gz
│   ├── ba10405bd2e2a889b6f903953df040e2834e5137.nq.gz
│   ├── bb5a0bbf75ed13815df9ef15a792b781a4061d4a.nq.gz
│   ├── bb612a4e32f8a37636b780bee0f2e6a0227be0a5.nq.gz
│   ├── bef7dfb3ee92510bb66d12ae6c53416c6fccf325.nq.gz
│   ├── c0365a239f49429fc21f93817d3a6268ecd4968d.nq.gz
│   ├── c07f026c0d3d78d93b2bf2647ec1fd19b4a4aab6.nq.gz
│   ├── c21d7a0d39a688d662289949c4d919f042f43c83.nq.gz
│   ├── c2a5fdd8eda4931a4dc8d5d9c05e0fa0cf51aaaf.nq.gz
│   ├── c2a74803b37fb4db0cccaf4dad51eee27303841f.nq.gz
│   ├── caaeb4f73220343cf55564c4b747c6434c231fd8.nq.gz
│   ├── ccb03c7388ba5b7a821f9a7be92a6fabf42c3c58.nq.gz
│   ├── cd78bbd6b32e290e247557c6e11b9e6741f7dcaf.nq.gz
│   ├── cde00fd314855750319ac0ac4d8100b61afea41e.nq.gz
│   ├── d0c0e2917651ab1d38f689317e32f463c392c3d2.nq.gz
│   ├── d0c43b56c8c184a5f073e048a955eecfc5a8cf6e.nq.gz
│   ├── d157ddaae1b24ef0c53e2d20794eb51b499e01ef.nq.gz
│   ├── d3d0a998f5e8ec1747d9d407b9aa04558fb92ebe.nq.gz
│   ├── d471b79cca01c666d612a65f46c947e0e6e21af2.nq.gz
│   ├── d47f4bfcaa6fd217d262997e119a17bd87f2f512.nq.gz
│   ├── d6606e62519b2e21d3befbf345d7e18f5ddf05e4.nq.gz
│   ├── d71afedd20355d2381c03ab736c14c8db8a4e258.nq.gz
│   ├── d79ac1e5312689f8526a3f92d199a539d97539b1.nq.gz
│   ├── d87f5819dee2a7d8191b275d22be3b4b8ce39244.nq.gz
│   ├── dac0694302b8eba820b614e1125cadcfcf72b970.nq.gz
│   ├── dad5ba9777fd19356a4d589fa307b40119de4dbc.nq.gz
│   ├── dafa228b6c28bcb9f109538d3beef5678ab9530b.nq.gz
│   ├── db6d6dfb6573a4adf3baf2355775baec1e380e3b.nq.gz
│   ├── dc2e4bf65ff98b9679833358fd5068ae9a002682.nq.gz
│   ├── dc5f884b92a1ae67f12c557268c9b9afd4c607e8.nq.gz
│   ├── dd5b52dbad33e2c6268a5ea6a0bf1dfd6a8f78a9.nq.gz
│   ├── e034b91f7a78ad40b1349f103363131423841d61.nq.gz
│   ├── e1a47ea8ba00477ab626c019cd30d9aeb23c0060.nq.gz
│   ├── e41de9fe781468dc7c03f2939da32b7b48e0a14d.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e95a92766ccab6ac9f8044d2bccaa0cd370acec9.nq.gz
│   ├── eba096e3e4c2c59379f91d3f8b57e38a302dc0fd.nq.gz
│   ├── ef307ac7bdd135af12daef8f69d96f1fe9ac6ad6.nq.gz
│   ├── f0360c310622fc2eb0143ca6b920cd0cc3482385.nq.gz
│   ├── f699d2e1cf107d1d7867178bcaf7b0aeb4dc7065.nq.gz
│   ├── f8c8be1dac93d3fd5ea6a2d8df574fd91a2837bd.nq.gz
│   ├── faf888858031b7c7946d1ea5d701b68b38e04c12.nq.gz
│   ├── fb57a28b1a95604bbace3e6e583bf4f90dfcdb05.nq.gz
│   ├── fb5a24882482d758e3c79fed3495f59f2fbff51f.nq.gz
│   ├── fba8894e3a917f7fc4785dc4aedfa3f0cdd3ba12.nq.gz
│   ├── fd287b6d0e357506cbb5f3836c52c59504e6a3f4.nq.gz
│   └── fe70bbe32ce6f1776221e678926b9da8416ec05f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1d5dcbebcfff610e2db2ab807b2076ac749eae94.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 168 files
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

[scverse/spatialdata](https://github.com/scverse/spatialdata)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
