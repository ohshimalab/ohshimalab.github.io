---
title: 人のパーソナリティと場所の特徴を用いたストレス推定と推定根拠の説明
summary: 人のパーソナリティと場所の特徴がストレスにどう影響しているのかを明らかにする．
tags:
  - 自然言語処理
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
## 人のパーソナリティと場所の特徴がストレスにどう影響しているのかを明らかにする．

本研究では，人のパーソナリティと場所の特徴を用いて
ストレスの推定と推定根拠の説明を行う．
提案手法を用いることで，ある人にとって落ち着く場所や，
ストレスを感じる場所を事前に把握することができる．
ストレスの推定には教師あり機械学習モデルを用いる．
ここで提案するストレス推定モデルは，
人のパーソナリティと場所の特徴を入力とし，
ストレス値を出力とする．
人のパーソナリティはTIPI-JとGHQ30と呼ばれるアンケートから
パーソナリティ分析手法を用いて取得する．
場所の特徴はTripAdvisorから得られるレビュー文を用いる．
ここで，レビュー文は場所の特徴を含む
テキストデータであるため，
BERTを用いて768次元の特徴ベクトルを取得し，
これを利用する．
ストレス値には心拍変動指数であるLF/HF値を用いる．
LF/HF値の算出には心拍間隔の時間差が必要となる．
そのため，心拍波形を取得しピークの検出を行う．
心拍波形の取得には耳朶脈波計を用いる．
ストレス推定モデルの説明にはLIMEやSHAP，
AttentionといったXAIの手法を用いる予定である．





