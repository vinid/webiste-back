---
title: "BERTective: Language Models and Contextual Information for Deception Detection"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Tommaso Fornaciari
- admin
- Massimo Poesio
- Dirk Hovy



# Author notes (optional)
#author_notes:


date: "2021-03-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-03-01T00:00:00"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In Proceedings of *The 16th Conference of the European Chapter of the Association for Computational Linguistics*
publication_short: In *EACL*

abstract: "Spotting a lie is challenging but has an enormous potential impact on security as well as private and public safety.
Several NLP methods have been proposed to classify texts as truthful or deceptive.
In most cases, however, the target texts' preceding context is not considered.
This is a severe limitation, as any communication takes place in context, not in a vacuum, and context can help to detect deception.
We study a corpus of Italian dialogues containing deceptive statements and implement deep neural models that incorporate various linguistic contexts.
We establish a new state-of-the-art identifying deception and find that not all context is equally useful to the task. Only the texts closest to the target, if from the same speaker (rather than questions by an interlocutor), boost performance.
We also find that the semantic information in language models such as BERT contributes to the performance.
However, BERT alone does not capture the implicit knowledge of deception cues: its contribution is conditional on the concurrent use of attention to learn cues from BERT's representations."

# Summary. An optional shortened abstract.
#summary: We investigate grounded language learning through real-world data, by modelling a teacher-learner dynamics through the natural interactions occurring between users and search engines.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)


url_pdf: ''
url_code: ''
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
