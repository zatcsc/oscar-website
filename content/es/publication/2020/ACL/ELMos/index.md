---
title: "A Monolingual Approach to Contextualized Word Embeddings for Mid-Resource Languages"
authors:
- pedro
- Laurent Romary
- Benoît Sagot
date: "2020-07-06T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *The 58th Annual Meeting of the Association for Computational Linguistics*
publication_short: In *ACL 2020*

abstract: Wikipedia is one of the most widely used datasets to train standard and contextualized word embeddings. However, even for mid-resource languages, the amount of data found in Wikipedia might be too small to train high-quality embeddings. Moreover,  Wikipedia data covers a single specific genre and style. Conversely, Common Crawl is a source of much larger and much more diverse data, although at the expense of some level of noise. We use the multilingual OSCAR corpus, extracted from Common Crawl via language classification, filtering and cleaning, to train monolingual contextualized word embeddings (ELMo) for several mid-resource languages. We then compare the performance of OSCAR-based and Wikipedia-based ELMo embeddings for these languages on the part-of-speech tagging and parsing tasks. We show that, despite the noise in the Common-Crawl-based OSCAR data, embeddings trained on OSCAR perform much better than monolingual embeddings trained on Wikipedia. They actually equal or improve the current state of the art in tagging and parsing for all five languages. In particular, they also improve over multilingual Wikipedia-based contextual embeddings (multilingual BERT), which almost always constitutes the previous state of the art, thereby showing that the benefit of a larger, more diverse corpus surpasses the cross-lingual benefit of multilingual embedding architectures.

# Summary. An optional shortened abstract.
summary: We explore the impact of the training corpus on contextualized word embeddings in five mid-resource languages.

tags:
featured: true

links:
- name: ACL 2020
  url: https://acl2020.org/
#url_pdf: https://ids-pub.bsz-bw.de/frontdoor/deliver/index/docId/9021/file/Suarez_Sagot_Romary_Asynchronous_Pipeline_for_Processing_Huge_Corpora_2019.pdf
#url_code: 'https://github.com/pjox/goclassy'
#url_dataset: 'https://traces1.inria.fr/oscar/'
#url_poster: '#'
#url_project: ''
#url_slides: '/files/CMLC_7_slides.pdf'
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---
