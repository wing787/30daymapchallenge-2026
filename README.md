# 30DayMapChallenge 2026

[#30DayMapChallenge](https://30daymapchallenge.com/) 2026 の地図と、その作り方。

Thirty maps for the 2026 challenge, all drawn inside the same two map frames — Japan and the Kanto region.

## 趣向

- **同じ図郭を 30 回描く。** 図郭は「全国図」と「関東図」の 2 つだけ。枠と目盛の位置は変えず、データだけを替える。
- **整飾にデータの素性を 1 行書く。** データ名と版、件数、CRS、処理の道具と時間。数字は実測値。
- 見た目は自作のデザインシステム [geo-ui](https://github.com/wing787/geo-ui) の「図葉」。UI は無彩色で、色はすべてデータに使う。

## 地図

| 日 | テーマ | 地図 | データ |
|---|---|---|---|
| — | — | まだありません | — |

## 作り方

データ処理は Python（uv）、描画は Vite + MapLibre GL JS、画像の書き出しは Playwright。
手順はコードが入った時点で書く。

## データと出典

使用許諾が CC BY 4.0 か商用可のデータだけを使う。各地図の出典は、地図の出典欄と上の表に書く。
元データはコミットしない（取得スクリプトで再現する）。

## AI の使い方

公式の行動規範に従って開示する。図葉の部品と雛形は AI（Claude）が書いた。
各日の説明に、その日 AI を何に使ったかを書く。Day 10（Prompting only）は全部 AI で作る。

## ライセンス

- コード: MIT（[LICENSE](LICENSE)）
- 地図の画像（`out/`）: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.ja)
- 元データと配色には、それぞれの配布元の条件がある。各地図の出典欄に書く。
