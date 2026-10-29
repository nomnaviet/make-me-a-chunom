# Notice

This repository combines code, data and fonts from several sources under different licenses. There is no single license for the whole repository; each part keeps the terms it came with.

## Data

| Files | Derived from | License |
|---|---|---|
| `public/dictionary.txt` | [Unihan](https://www.unicode.org/charts/unihan.html) and [CJKlib](https://github.com/cburgmer/cjklib), via [makemeahanzi](https://github.com/skishore/makemeahanzi) | LGPL-3.0-or-later ([`LGPL`](LGPL), see [`COPYING`](COPYING)) |
| `public/graphics.txt` | Arphic PL KaitiM GB and Arphic PL UKai, via makemeahanzi | Arphic Public License ([`APL`](APL), see [`COPYING`](COPYING)) |
| `public/unihan/` | Unicode, Inc. | Unicode License ([`public/unihan/LICENSE`](public/unihan/LICENSE)) |
| `public/zydeo.txt` | Origin not recorded; no code in this repository uses it | Unknown — under review |
| `public/cjklib/*` except the two Shanghainese files | [CJKlib](https://github.com/cburgmer/cjklib) | LGPL-3.0-or-later ([`LGPL`](LGPL)), as stated in the headers of the `.csv` files; the `.sql` files are the same tables and carry no header |
| `public/cjklib/charactershanghaineseipa.*`, `public/cjklib/shanghaineseipasyllables.*` | Kellen Parker and Allan Simon (2010), [sinoglot.com](http://www.sinoglot.com/wu/tools/data/), via CJKlib | [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/) |

## Fonts

| Files | License |
|---|---|
| `public/arphic/` — Arphic PL fonts | Arphic Public License ([`APL`](APL)) |
| `public/nom-fonts/BabelStoneHan.ttf` — [BabelStone Han](https://www.babelstone.co.uk/Fonts/Han.html) | Original Arphic Public License ([`APL`](APL)) |
| `public/nom-fonts/NomNaTong-*` — [NomNaTong](https://github.com/nomfoundation/font), Vietnamese Nôm Preservation Foundation | MIT ([`public/nom-fonts/NomNaTong-LICENSE.txt`](public/nom-fonts/NomNaTong-LICENSE.txt)) |
| `public/nom-fonts/Plangothic*` — [Plangothic](https://github.com/Fitzgerald-Porthmouth-Koenigsegg/Plangothic_Project) | SIL Open Font License 1.1 ([`public/nom-fonts/Plangothic-OFL.txt`](public/nom-fonts/Plangothic-OFL.txt)) |

## Code

The editor is adapted from [skishore/makemeahanzi](https://github.com/skishore/makemeahanzi) and [MadLadSquad/make-me-a-hanzi-tool](https://github.com/MadLadSquad/make-me-a-hanzi-tool). Neither upstream project states a license for its code, and this repository's own changes to the editor are not licensed either for now: no rights are granted in the editor code beyond what applicable law allows. Third-party libraries vendored under `client/external/` and `lib/external/` are not listed here; each carries its own license header.
