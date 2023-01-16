---
title: 特許を用いた重要な特許の発見
summary: 特許の被引用数の予測
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
## 特許の被引用数の予測

本研究では特許のデータを用いて重要な特許を発見する研究を行っている。重要な特許とは、例えば、山中伸弥教授の iPS 細胞の特許、トヨタ自動車株式会社の電気自動車の特許や、株式会社日立製作所のウェアラブル端末の特許などが挙げられる。しかし、特許は日本で年間 30 万件ほど出願されており、すべての特許からこれらの特許を発見するのは現実的ではない。そのため、私は重要な特許を発見することで企業が必要な特許を効率的に発見出来るようにしたいと考えている。本研究では重要な特許を、社会に大きな影響を与えている特許としている。 基本的には重要な特許を見つける際に、被引用数に注目する。しかし、被引用数は特許が公開されてから数年は増えにくいという問題がある。そこで、被引用数以外の特徴も用いて、公開されてから 2 年以内に5年後の特許の被引用数を予測する手法の提案を行う。本研究の手法としては、重要な特許には様々な特徴がみられる。現状、重要な特許の特徴を 3つ考えている。その 3 つの特徴とは、初めての技術用語が含まれているという特徴、汎用性があるという特徴、技術用語が初めての組み合わせであるという特徴である。ここで、挙げている特徴を特許中の情報からテキストマイニング等の手法を用いて抽出していく。そして、抽出した特徴を用いて重要な特許の分類を行っていく。





