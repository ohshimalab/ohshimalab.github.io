---
title: "A Fast Algorithm for Unsupervised Feature Value Selection"
authors:
  - Kilho Shin
  - Kenta Okumoto
  - David Shepard
  - Tetsuji Kuboyama
  - Takako Hashimoto
  - admin
date: "2015-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-02-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Source Themes, 1*(1)"
publication_short: ""

abstract: The difficulty of unsupervised feature selection results from the fact that many local solutions can exist simultaneously in the same dataset. No objective measure exists for judging the appropriateness of a particular local solution, because every local solution may reflect some meaningful but different interpretation of the dataset. On the other hand, known accurate feature selection algorithms perform slowly, which limits the number of local solutions that can be obtained using these algorithms. They have a small chance of producing a feature set that can explain the phenomenon being studied. This paper presents a new method for searching many local solutions using a significantly fast and accurate algorithm. In fact, our feature value selection algorithm (UFVS) requires only a few tens of milliseconds for datasets with thousands of features and instances, and includes a parameter that can change the local solutions to select. It changes the scale of the problem, allowing a user to try many different solutions and pick the best one. In experiments with labeled datasets, UFVS found feature value sets that explain the labels, and also, with different parameter values, it detected relationships between feature value sets that did not line up with the given labels.

# Summary. An optional shortened abstract.
summary: ""

tags:
  - Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.scitepress.org/Link.aspx?doi=10.5220%2f0008981702030213
url_code: ""
url_dataset: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% alert note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the _Slides_ button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
