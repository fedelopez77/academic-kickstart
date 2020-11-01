+++
title = "A Fully Hyperbolic Neural Model for Hierarchical Multi-Class Classification"

# Date first published.
date = "2020-10-05"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Federico López**", "Michael Strube"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "In Findings of EMNLP, 2020"
publication_short = "In *Findings of EMNLP 2020*"

# Abstract and optional shortened version.
abstract = "Label inventories for fine-grained entity typing have grown in size and complexity. Nonetheless, they exhibit a hierarchical structure. Hyperbolic spaces offer a mathematically appealing approach for learning hierarchical representations of symbolic data. However, it is not clear how to integrate hyperbolic components into downstream tasks. This is the first work that proposes a fully hyperbolic model for multi-class multi-label classification, which performs all operations in hyperbolic space. We evaluate the proposed model on two challenging datasets and compare to different baselines that operate under Euclidean assumptions. Our hyperbolic model infers the latent hierarchy from the class distribution, captures implicit hyponymic relations in the inventory, and shows performance on par with state-of-the-art methods on fine-grained classification with remarkable reduction of the parameter size. A thorough analysis sheds light on the impact of each component in the final prediction and showcases its ease of integration with Euclidean layers."
#abstract_short = "A short version of the abstract."

# Featured image thumbnail (optional)
image_preview = "model.png"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#projects = []

# Links (optional).
url_pdf = "https://arxiv.org/pdf/2010.02053.pdf"
url_preprint = "https://arxiv.org/abs/2010.02053"
url_code = "https://github.com/nlpAThits/hyfi"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
# image = "model.png"
# caption = "Overview of the proposed model to predict types of a mention within its context."

+++
