---
title: "From Coverage Computation to Fault Localization: A Generic Framework for Domain-Specific Languages"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Erwan Bousse
- Antonio Garmendia
- Jean-Marie Mottu
- Gerson Sunyé
- Manuel Wimmer

# Author notes (optional)
author_notes:
- IMT Atlantique, Nantes Université, École Centrale Nantes, CNRS, LS2N, UMR 6004, F-44000 Nantes, France
- IMT Atlantique, Nantes Université, École Centrale Nantes, CNRS, LS2N, UMR 6004, F-44000 Nantes, France
- Johannes Kepler University Linz (JKU)
- IMT Atlantique, Nantes Université, École Centrale Nantes, CNRS, LS2N, UMR 6004, F-44000 Nantes, France
- IMT Atlantique, Nantes Université, École Centrale Nantes, CNRS, LS2N, UMR 6004, F-44000 Nantes, France
- Johannes Kepler University Linz (JKU)

date: "2022-12-06"
doi: "10.1145/3567512.3567532"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 15th ACM SIGPLAN International Conference on Software Language Engineering*
publication_short: In *Proceedings of the 15th ACM SIGPLAN International Conference on Software Language Engineering (SLE 2022)*

abstract: "To test a system efficiently, we need to know how good are the defined test cases and to localize detected faults in the system. Measuring test coverage can address both concerns as it is a popular metric for test quality evaluation and, at the same time, is the foundation of advanced fault localization techniques. However, for Domain-Specific Languages (DSLs), coverage metrics and associated tools are usually manually defined for each DSL representing costly, error-prone, and non-reusable work. To address this problem, we propose a generic coverage computation and fault localization framework for DSLs. Considering a test suite executed on a model conforming to a DSL, we compute a coverage matrix based on three ingredients: the DSL specification, the coverage rules, and the model's execution trace. Using the test execution result and the computed coverage matrix, the framework calculates the suspiciousness-based ranking of the model's elements based on existing spectrum-based techniques to help the user in localizing the model's faults. We provide a tool atop the Eclipse GEMOC Studio and evaluate our approach using four different DSLs, with 297 test cases for 21 models in total."
#summary: 
tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
#links:
#- name: Preprint
#  url: ''
url_pdf: https://hal.archives-ouvertes.fr/hal-03815772v1
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
