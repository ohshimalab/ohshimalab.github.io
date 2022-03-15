---
title: Micro Geocoding
summary: 場所の説明文から、その場所の緯度経度を推定するシステム
tags:
  - Deep Learning
date: "2021-07-14"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
#   caption: 場所の説明文から、その場所の緯度経度を推定するシステム
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
## 場所の説明文から、その場所の緯度経度を推定するシステム

<!-- 文で研究紹介 -->
ある場所を説明する文章から、その場所の緯度経度を推定する。[OpenStreetMap](https://www.openstreetmap.org/)から地理情報を取得し、説明文に応じた処理をすることで場所の推定を行う。

<!-- コレ使ったらね！こんなことが嬉しいよ！ -->
言葉を使って、現在地を説明しなければならない状況がある。例えば、交通事故に遭ったとき、警察や保険会社に電話をし、事故が発生した場所を伝えなければならない。言葉による説明から場所を特定するためには、聞き手に知識やスキルが必要である。聞き手の能力によって、推定の正確さに差が出ることもあるだろう。このシステムは、聞き手に代わって場所を推定し、聞き手の能力差によって生じる問題を解決する。

![fig2_geocoding](fig2_geocoding.png)