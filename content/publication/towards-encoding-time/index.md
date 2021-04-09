---
title: "Towards Encoding Time in text-based Entity Embeddings"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Matteo Palmonari
- Debora Nozza



# Author notes (optional)
#author_notes:


date: "2018-07-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2018-07-02T00:00:00"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In International Semantic Web Conference
publication_short: In *ISWC*

abstract: Knowledge Graphs (KG) are widely used abstractions to represent entity-centric knowledge. Approaches to embed entities, entity types and relations represented in the graph into vector spaces - often referred to as KG embeddings - have become increasingly popular for their ability to capture the similarity between entities and support other reasoning tasks. However, representation of time has received little attention in these approaches. In this work, we make a first step to encode time into vector-based entity representations using a text-based KG embedding model named Typed Entity Embeddings (TEEs). In TEEs, each entity is represented by a vector that represents the entity and its type, which is learned from entity mentions found in a text corpus. Inspired by evidence from cognitive sciences and application-oriented concerns, we propose an approach to encode representations of years into TEEs by aggregating the representations of the entities that occur in event-based descriptions of the years. These representations are used to define two time-aware similarity measures to control the implicit effect of time on entity similarity. Experimental results show that the linear order of years obtained using our model is highly correlated with natural time flow and the effectiveness of the time-aware similarity measure proposed to flatten the time effect on entity similarity

# Summary. An optional shortened abstract.
#summary: We investigate grounded language learning through real-world data, by modelling a teacher-learner dynamics through the natural interactions occurring between users and search engines.

tags: ["Semantic Web", "NLP", "KG", "Embeddings"]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)


url_pdf: 'https://link.springer.com/chapter/10.1007/978-3-030-00671-6_4'
url_code: 'https://github.com/vinid/time-aware'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'http://videolectures.net/iswc2018_bianchi_towards_encoding_time/'



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
