---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 65

title: Projects
subtitle: 研究室で取り組んでいるプロジェクト

content:
  # Page type to display. E.g. project.
  page_type: project

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
  - name: All
    tag: '*'
  - name: ディープラーニング
    tag: ディープラーニング
  - name: 自然言語処理
    tag: 自然言語処理
  - name: 画像認識
    tag: 画像認識
  - name: 情報検索
    tag: 情報検索
  - name: コンテンツ自動生成
    tag: コンテンツ自動生成
  - name: 過去のプロジェクト
    tag: 過去のプロジェクト


design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '1'

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view: 3

  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
---