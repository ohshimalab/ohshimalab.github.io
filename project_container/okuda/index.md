---
title: 画像認識によるウキクサ科植物の総枚数と表面積の推定
summary: 画像認識の植物への応用
tags:
  - 画像認識
  - 植物
  - ディープラーニング
date: "2022-11-22"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  # caption: これであなたも発明王
  focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example

type: project
---
## 画像認識の植物への応用

本研究では，水生植物であるウキクサ科植物の葉の総枚数と表面積を推定する問題に取り組む．
入力はウキクサ科植物の画像であり，出力は葉の総枚数と葉を垂直から見たときの表面積の2つである．
ウキクサ科植物は，親に当たる葉と子に当たる葉が水面に浮かんでいる水生植物である．
本研究ではたとえば，親に当たる葉と子に当たる葉を合わせて，全部で8枚ある場合，出力される総枚数は8枚となることを目指す．
さらに，入力された画像を垂直方向から見た時の葉の面積の合計も出力することを目指す．
表面積を出力するために，親に当たる葉と子に当たる葉のかたまりを領域認識する必要がある．
本研究では，ウキクサという1つのクラスに対して，葉のかたまりを領域認識した．
総枚数を出力するために，親に当たる葉と子に当たる葉のかたまりに対して，各枚数を推定する必要がある．
本研究では，
親に当たる葉と子に当たる葉を合わせたかたまりの形から，画像認識モデルを用いて，各枚数を推定した．




