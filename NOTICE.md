# Third-party notices · 第三方内容说明

The MIT License in [LICENSE](LICENSE) covers the code written for this project. It does **not** cover the third-party material below, which is embedded in `index.html`.

[LICENSE](LICENSE) 里的 MIT 授权只覆盖本项目自己写的代码，不覆盖下面这些嵌在 `index.html` 里的第三方内容。

## Inter (font)

- Inter Variable 4.002 — Copyright (c) 2016 The Inter Project Authors (<https://github.com/rsms/inter>)
- Licensed under the SIL Open Font License, Version 1.1. Full text: [licenses/OFL-Inter.txt](licenses/OFL-Inter.txt)
- Embedded base64-encoded as the `INTER` constant. The file is the subset build (about 108 KB) that polymarket.com serves; its name table still carries the original copyright and licence fields.

## Polymarket name, wordmark and icons

- The Polymarket wordmark (the `LOGO` constant) and the small interface icons (the `ICONS` constant) were taken from polymarket.com. They are trademarks or works of their owner.
- They appear in generated images only to credit the source of the data and to keep the card recognisable as Polymarket market data.
- No licence to them is granted by this repository. If you reuse this code for another purpose, replace them.
- This project is not affiliated with, endorsed by, or sponsored by Polymarket.

Polymarket 的字标（`LOGO`）和界面小图标（`ICONS`）取自 polymarket.com，是其所有者的商标或作品，在生成的图片里只用于标明数据来源。本仓库不对它们授予任何授权；把这份代码用到别处时请替换掉。

## Data and images

- Market data and price history are fetched at run time from Polymarket's public APIs (`gamma-api.polymarket.com`, `clob.polymarket.com`). Nothing is stored in this repository except the two sample images in `examples/`.
- Outcome and event images are loaded from Polymarket's image host at run time and belong to their respective owners.
- During PNG export, images are requested through the public image proxy <https://wsrv.nl> (the open-source [weserv/images](https://github.com/weserv/images) service).
