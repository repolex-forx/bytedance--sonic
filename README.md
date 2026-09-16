# Repolex Knowledge Graph of bytedance/sonic

RDF knowledge graph data for [bytedance/sonic](https://github.com/bytedance/sonic), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download bytedance/sonic
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── afa2fcee563e04e912786ebd77b53760181fa622
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   ├── lsp
│   │   └── afa2fcee563e04e912786ebd77b53760181fa622.nq.gz
│   └── repolex
│       └── afa2fcee563e04e912786ebd77b53760181fa622
│           └── chunk-001.nq.gz
└── blob
    ├── 001ffbda19628bec489b3182b442b81bea87f85e.nq.gz
    ├── 002219df89bf15b44848073fd6c381dd25a49512.nq.gz
    ├── 003ebb117361b31e09dee8b8789f10ad3c123036.nq.gz
    ├── 004c09374eb2e366b7168d891e23b8d6c8d7d3ea.nq.gz
    ├── 009afe6b968720001d4a2818bc418385d42e1566.nq.gz
    ├── 00ff6ab17cc8325b9dbb3a34ff0b3bfff5657e06.nq.gz
    ├── 015e17c107ca7da965005ba22fa4fdc2085abcf4.nq.gz
    ├── 02019f756f13bd1ff93613dcffc0a9f013f74824.nq.gz
    ├── 022cd47b24ea87eae4398d46f4ba35765f790312.nq.gz
    ├── 026e064fe3c9bac78219a911824386b6d0747a6a.nq.gz
    ├── 0285f0f8f75b06b340c5c6b98be81414a1df83e3.nq.gz
    ├── 0353012fd559625787b52abf55d160323a682733.nq.gz
    ├── 03a8d0e896a497b6b375ccbadf6697cbcee72e23.nq.gz
    ├── 040e15a3dcd8b3aaf8ff051ee649a2ffcfd3ccb2.nq.gz
    ├── 04701ef5b3a29743d806d0ad73b3576123ba2d86.nq.gz
    ├── 048e48f75bd258e794ab8edcec5578de77603d10.nq.gz
    ├── 04c2baa819c540685e0344f1765479a146705d09.nq.gz
    ├── 04e6d934dc5daca73ebeeb121c6a1c3439d1e4b1.nq.gz
    ├── 06454ba61327fb40f3c3a941a353bb46e28fae1e.nq.gz
    ├── 0683f45ae0a43f237a2bf9e7fea11e87a85499d8.nq.gz
    ├── 06935a2c17286358a5e29f036226f6ba4742afb9.nq.gz
    ├── 0701557fea617eff6c9b329a0a168b4beb7213fe.nq.gz
    ├── 07a93ee8f98b21166e21a6128372ab180674b897.nq.gz
    ├── 07ca031585305349a81916795c4488415f4faab2.nq.gz
    ├── 07eff791a1508b01aa3f686dc604e6c084ce7765.nq.gz
    ├── 085e81102d096dde272a45602a04549748d177d8.nq.gz
    ├── 086279dbd869e3966f833b11070ad321d11fa1fe.nq.gz
    ├── 08abfb5a887462d8ed57b9a1c22614c71d7de53a.nq.gz
    ├── 08b82e5d95140b04bf57f53a80071765a1157a8f.nq.gz
    ├── 08eecf88b3b2b970144155755d0ce717e5e00321.nq.gz
    ├── 08f582f201e0d58b9231e7d63b5542d02bdf7908.nq.gz
    ├── 096351b310dcca47b38cff683c9b59d4d43aaf9c.nq.gz
    ├── 09855ec9a629f2025b8fba7d26b35fa9fe611319.nq.gz
    ├── 09c98e32e92500c0749263ae33dea96a5f9437f7.nq.gz
    ├── 0a1b3c1d6591f6a9e1cc3b9114b7ff07d9cf9901.nq.gz
    ├── 0a7a202892ba53abdda955ab8932c80cec5f0b93.nq.gz
    ├── 0ab376711ba23d9971b280ff150a72c51ec357a7.nq.gz
    ├── 0c051f8b82c02c9843b88a0ad9f005b481340b35.nq.gz
    ├── 0e10454d45691228a49a4e1c4787a49b37b914fa.nq.gz
    ├── 0e19a9ba9aa06eadb434742e63b910826b693b83.nq.gz
    ├── 0e3c665bd4fd353ba25b89569af1349ea44b0829.nq.gz
    ├── 0e8045a7423cc95db6072d6fa0b60b721018bdf4.nq.gz
    ├── 0e8594c2e515a3fc640aede3f13dc58fbc64a27f.nq.gz
    ├── 107dfb3cd63b949d3b6a15ddd8875f49b3e5b5f9.nq.gz
    ├── 1098a096c587b575c3bf3d2ee3496af73119464d.nq.gz
    ├── 109e26cbcc99984f980216e5d1942fcd8c720696.nq.gz
    ├── 10cbaf9dd3d141c2d4118337b7975ff55b2a9555.nq.gz
    ├── 11c37e44e790a813f3d5d3d4a92c8c19b6a57c2c.nq.gz
    ├── 124b46fd15caf82a71be0a3a43a0c05e9a941d30.nq.gz
    ├── 127a5bc39ba030c7cb99cc0aedc4f280ffe27310.nq.gz
    ├── 134794b711ba3f50873d2ca44451bd802bd5c53c.nq.gz
    ├── 137fb516252d6941523cdbd0d8acf81e5d286bab.nq.gz
    ├── 138c3a6e3404f8012c81e2b00ea5d7fb1cdb1581.nq.gz
    ├── 139df123e7426d3f86bc71b6f81e27f30e9d3834.nq.gz
    ├── 14ed140fde04b0bed49640a83668ca5f90fd7642.nq.gz
    ├── 151794d5251d96208cef32f90e475399fd82114b.nq.gz
    ├── 152c72ca1f2e510948bc4ec918475fdd886e166b.nq.gz
    ├── 15315d1d66f45b1cb069e36a6a62ac700a87e5d8.nq.gz
    ├── 15f55499419f6d22d885d2f5201de54b29d43f6c.nq.gz
    ├── 163279a0c6db5a86bb606011b58f24bd3a75f684.nq.gz
    ├── 16b0d3fb84936281bfc2d5e0e7460b856db7a724.nq.gz
    ├── 1760a71171e1ab0281c7b66a6efc7850904283d9.nq.gz
    ├── 176caa00eb7cc27a9c34423e5184e6e2e24ddd5b.nq.gz
    ├── 177bd1a2fe87b6fcf464fca3bce04ab1564e2faa.nq.gz
    ├── 178b4d8bb5d775c50268c944879f924f4f42fa2a.nq.gz
    ├── 1802f8421b97ec5c6c2ed43dd165b5f0c72e9d9d.nq.gz
    ├── 18b38d531fba516fcb140e28eb95b3080d0e431c.nq.gz
    ├── 19746a6fa542dbab7187a2ad19194cabfd9680a2.nq.gz
    ├── 19e4f2877e22447c15f17cbb7364fa28e3a0beda.nq.gz
    ├── 19fa2d0c0973befdde73a3b9a9c78b33da38d9f7.nq.gz
    ├── 1ae77195bebd0599d92614786f23a6e4bacd4983.nq.gz
    ├── 1b2514762ff4cdbb2cc7a9a192ec471c084a0c93.nq.gz
    ├── 1c0c7cc007cd03f3dbf608119a6978dd94eec428.nq.gz
    ├── 1c135540892d6a9d28cb4bef2f814663bfe86d21.nq.gz
    ├── 1cabcc2690ea78ae4c314ffba05bcc8461fa4c0e.nq.gz
    ├── 1cae2689822622411184575b3780dfc88b143f63.nq.gz
    ├── 1cb993e39851128dae19304aa27e60f0a6dbcdd2.nq.gz
    ├── 1ccef98d57e89546ee322d6b05ab57baece12ac8.nq.gz
    ├── 1d8412f81740e2afb87da30b8507563a52ef637e.nq.gz
    ├── 1d99c4b7b71ec196e9894c4f5b1ca9016e75f5db.nq.gz
    ├── 1e471ef2438f77f4a72dc0d833cb028269b3a44a.nq.gz
    ├── 1e624c14beec283c5f72dd4c5119174f60b95a51.nq.gz
    ├── 1e91f0207a6c080d95f8906cabff4b7a6dcf772e.nq.gz
    ├── 1ec6a8528158b7333c420627c6c5bf131409c991.nq.gz
    ├── 1ee97569472f253ee09d3d49701ea8ccc558d440.nq.gz
    ├── 201b707185ae7d64afa8c66ac4604a04dadf3e27.nq.gz
    ├── 20592cd33d54ea90b81e3e2dd706f60fadd0d6c3.nq.gz
    ├── 2063ad5c535005ee2b7e9745f78cf9f8d5ba6f8b.nq.gz
    ├── 206a9dd1a35c02adb216b26f5721747461a2d764.nq.gz
    ├── 217984e4cb694d95f1b910cd1289fef8fa83e23d.nq.gz
    ├── 21bb9bafc3ca13995ce843ffe9b3a8d112a831c5.nq.gz
    ├── 2203657d01f060812720bd7b052735c51facc212.nq.gz
    ├── 221996dfaf7e767d803c9a1c0acea30d1dc13dcc.nq.gz
    ├── 221e22d539a6b4cc35c610861078945498403f80.nq.gz
    ├── 22a0926cd36893ff1d00e504728813533291ad46.nq.gz
    ├── 22de274b5479ae88cdd4d4b408499ba324780dbc.nq.gz
    ├── 22ed3006a2297efb267144445f43ad2a6b2194db.nq.gz
    ├── 231b1a000d99c240556c39d730345ccb3b01487d.nq.gz
    ├── 232d64289e458cacf697293d24b7180801f27585.nq.gz
    ├── 241556780cea42330031c4dd39ffecc62e18c012.nq.gz
    ├── 2416c6f4c688757a38addd2bfc881641eb9cdf5f.nq.gz
    ├── 242ab04e23bbf3ecdd434225b55a9d472e7d7058.nq.gz
    ├── 2456ffbbb8ea8666e37b9019aae61cf9abec331f.nq.gz
    ├── 251907589408d49c501c09414c9db436bdfb0ecf.nq.gz
    ├── 251b1a6b7c0ee921da841566938ae730f9690e1a.nq.gz
    ├── 2558a7ef77b18ccdad766486f8e0310f798eeed9.nq.gz
    ├── 25b16638ce62ca1795ed672e9866bc5ed8fbf00c.nq.gz
    ├── 25bd2534486dfaec0501cede1e27b8ec4ac50b54.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 264e7665d03d3e7da382e9aa9b244fcf60074c48.nq.gz
    ├── 265575a267733863d8812ee98066d8c00dbbaa17.nq.gz
    ├── 268f5bf6daba6412c0c063cbb4dfe0f29f4e1b2c.nq.gz
    ├── 26bdb658493d152c8071d2079656abdf518f2b56.nq.gz
    ├── 27649681cc37602771a1bb25f301d13a0c02d098.nq.gz
    ├── 2830cdef4f23e8c173d89d9e9765ffb2bbbf5d17.nq.gz
    ├── 28660cf1d4562beea85d9b96285f7a636f4ea8b5.nq.gz
    ├── 28aebd60be5f1d36023fcdadd609a2efacdd5818.nq.gz
    ├── 28c203392d96cc2475a63c36bef9ed8e70fdf87f.nq.gz
    ├── 28fac56d5c58c011cb58b8bf004f232b219dd2d6.nq.gz
    ├── 29285e2e6865735fdf4704146464ccc6f29578da.nq.gz
    ├── 2934ae7a60f850fc289567367473fa3c8440d458.nq.gz
    ├── 2946fb12f12f7cf7e48ca2337eee7ebf58feb032.nq.gz
    ├── 2969c3bba3e7ff4f4d6e93c58c5476b109366114.nq.gz
    ├── 297cb9bef59dfba074127bb46f2b1e23bffad28e.nq.gz
    ├── 299205b7e7e202affce405b947acac166d092d35.nq.gz
    ├── 2a44a7b6f74b06a1303b2cb482ba523bd8d6c94b.nq.gz
    ├── 2a50cffb62a4b253d12981db6696ee8dca937690.nq.gz
    ├── 2a8bb01066ca1e27e61a98ae379e20d440b3d8dc.nq.gz
    ├── 2aa25d667f95982d19a67c70078cd52302da9836.nq.gz
    ├── 2aabaa8b803eaea7ac45c3e9df73fa3cf71c26e7.nq.gz
    ├── 2adb3e3168e281298fcef1b6eb824ffbe52a98ab.nq.gz
    ├── 2ae7162039ab00bc63cb85e47e6f0500757ff400.nq.gz
    ├── 2becd9d00a14c0e3edd1566845691f2a3f9e93af.nq.gz
    ├── 2c602f0055e7db8ea7e8f51ac291e290173d928e.nq.gz
    ├── 2c9aaa5830f0b6a37474cd389a5cffc77d1ffac0.nq.gz
    ├── 2dc5a50e516d1184683bb727e32ddbe65135fdb8.nq.gz
    ├── 2e251d64c283a58106ab3063a2d2b792564d0422.nq.gz
    ├── 2f6240bc25a5c403ccf2c513cf72517f8c7121cd.nq.gz
    ├── 2f6e17f91c24bd9d7402603f04be6b23351e0c9f.nq.gz
    ├── 2f6e26eb8b61e0957deb5b2fdaf0d1f4ab6d7291.nq.gz
    ├── 2f9e4561ccb86588442601ce9edffed2210ff994.nq.gz
    ├── 3016cb2484cbdced0c66b9db8274ce9520cbb058.nq.gz
    ├── 30402cd0e1b8ded8ea61657addad205f927673c3.nq.gz
    ├── 3045618e04eaa6fb3ed9d392b614d2a852e71c28.nq.gz
    ├── 30a119c3a55313f8a9d4d8c0b8a019d153d903fc.nq.gz
    ├── 312c609ad704b3b6cd8121328e0bb083478bccba.nq.gz
    ├── 31b5b8022c9674beee42c38fa051c6d59b3fe4eb.nq.gz
    ├── 32adc1c34e46c887df810784b662a041db261d42.nq.gz
    ├── 339a0234e865a6588f62d025e73f1b7fe77a3664.nq.gz
    ├── 33ccd77e4112036429d7e46c15bc5601ea634a8e.nq.gz
    ├── 33d787928ad12618baf1df5bfc4a711161d12c81.nq.gz
    ├── 33ea6db43f062f2914b9c39df974b83bf127cf3a.nq.gz
    ├── 346ef37ca7bd0d8bd0bf68e1f38f9ca9d49f5366.nq.gz
    ├── 3476a42584fc756d4ff7ad76c8111f67e12b88d3.nq.gz
    ├── 349daa8a012ea031982dc99c49b5dc827d5448ba.nq.gz
    ├── 34c99064670cf7e089d4b18e4f2df3bdec62f95c.nq.gz
    ├── 35b4c60837e74c97af01fffbd0b5220f61d1290b.nq.gz
    ├── 360c3f575e266d3cb6f8862607c998c44f1a66ae.nq.gz
    ├── 367a18c268b9b50245f73bbfd6df802fc08d27de.nq.gz
    ├── 3716e7a91bd0b1e3e42b08ba087e1fef0ca2ab30.nq.gz
    ├── 3790c8568fb013803ab8f4b598b5866f7d292647.nq.gz
    ├── 380d53c0a28e93411e54eb823842e1dbfc6b867f.nq.gz
    ├── 383393bab42d3f24d6a609f0f99e009bbfe02f07.nq.gz
    ├── 3858d9a8059b55fcd65aa98c2e09cab7e2f8d04e.nq.gz
    ├── 3928488fabc89a0a9bece59b1dd7ec3132756979.nq.gz
    ├── 3945f9935b2c96e2376fe8c5804ec96f45747f67.nq.gz
    ├── 3955b04474399cc5409cd628a09ce2564f478e22.nq.gz
    ├── 398ba8e33eabfa2b2207d649e2e96af874933cd2.nq.gz
    ├── 39b0010d0f13da0def7c74d4d64d8bd42eda5abc.nq.gz
    ├── 3a2845ec65a27805946cb1de82087a05c7472a87.nq.gz
    ├── 3a2f476e903448a6477c9d4b4c466671c559ff61.nq.gz
    ├── 3ae86267750f2fb10fc35327438d31561db78cca.nq.gz
    ├── 3b1ee6279422fbdf203d4bb227e0891cb33c4e8e.nq.gz
    ├── 3b891925f917a4b389cb7ba35d6a823c6f540925.nq.gz
    ├── 3bc24c4e402c0853319345715b25b1f2b8f5f6a1.nq.gz
    ├── 3bd4bf0f704c0d6d729a47e218bcd56265489328.nq.gz
    ├── 3cb49cb80b0091b377233346561d758349b068ab.nq.gz
    ├── 3d1fb65acfe3f383689b54d2239f6e7d062d3418.nq.gz
    ├── 3d59a8bb5361ad0c55f024f9c0785b89ba92dd72.nq.gz
    ├── 3e2a71733ce33ee05f33a027326766b6ea50533e.nq.gz
    ├── 3e99161fa8fd62417362d55edfebff8df08695e3.nq.gz
    ├── 3ee1e66c03c77d86c2c4ecfe8e56f492deffd126.nq.gz
    ├── 3f32dd659b810fe884b15a56edf17fe240c2eba4.nq.gz
    ├── 3fda09325bf79588d2d27e8ded08dcebec3e6d49.nq.gz
    ├── 404ab3f03e4b79d286930a8af8d318ff3b125f49.nq.gz
    ├── 405c490a24eaef2c2e5b96533d54990080a24140.nq.gz
    ├── 40b4de43c41499d7214592f2d2f94ae5b266db74.nq.gz
    ├── 41099cc897d2d7e577b38fa968328bc5b67f572d.nq.gz
    ├── 4113e3159678b4f1baadc96fed7111e3dfbb123e.nq.gz
    ├── 42d639e16ad211547d271a715628603e6ce4183a.nq.gz
    ├── 42f8f0e4abc7bd2a6fb63125afc367c3f72dc38e.nq.gz
    ├── 4303c6744d41f9e1efb9db4cafdd5de44dfd4fce.nq.gz
    ├── 4325ff7b7647749ffc8f03a906f93e20d0dd0ada.nq.gz
    ├── 437091e9b24ec716105761a8c231ad0dd6d06f70.nq.gz
    ├── 4377e2f98fc6cc8ef886d17ea91523ff224a0d95.nq.gz
    └── 437f56fa282363c9832662735eae854d4bdd7777.nq.gz

8 directories, 200 files
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

## Source repository

[bytedance/sonic](https://github.com/bytedance/sonic)

---
*Parsed on 2026-09-16 by [repolex](https://repolex.ai)*
