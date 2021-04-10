---
title: " Training Temporal Word Embeddings with a Compass"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Valerio Di Carlo
- admin
- Matteo Palmonari



# Author notes (optional)
#author_notes:


date: "2019-07-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-07-02T00:00:00"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Proceedings of the *AAAI Conference on Artificial Intelligence*.
publication_short: In *AAAI*.

abstract: Temporal word embeddings have been proposed to support the analysis of word meaning shifts during time and to study the evolution of languages. Different approaches have been proposed to generate vector representations of words that embed their meaning during a specific time interval. However, the training process used in these approaches is complex, may be inefficient or it may require large text corpora. As a consequence, these approaches may be difficult to apply in resource-scarce domains or by scientists with limited in-depth knowledge of embedding models. In this paper, we propose a new heuristic to train temporal word embeddings based on the Word2vec model. The heuristic consists in using atemporal vectors as a reference, i.e., as a compass, when training the representations specific to a given time interval. The use of the compass simplifies the training process and makes it more efficient. Experiments conducted using state-of-the-art datasets and methodologies suggest that our approach outperforms or equals comparable approaches while being more robust in terms of the required corpus size.

# Summary. An optional shortened abstract.
summary: We introduce a novel model for word embedding alignment and test it on temporal word embeddings obtaining SOTA results.

tags: ["NLP", "Meaning", "Temporal Word Embeddings", "Embeddings"]


# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)

links:
 - name: Blog Post
   url: https://medium.com/me/stats/post/732ab7427955


url_pdf: 'https://ojs.aaai.org/index.php/AAAI/article/view/4594'
url_code: 'https://github.com/vinid/cade/'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''



# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
