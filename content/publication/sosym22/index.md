---
title: "Advanced Testing and Debugging Support for Reactive Executable DSLs"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Erwan Bousse
- Jean-Marie Mottu
- Gerson Sunyé

# Author notes (optional)
author_notes:
- IMT Atlantique, Nantes Université, École Centrale Nantes, CNRS, LS2N, UMR 6004, F-44000 Nantes, France
- IMT Atlantique, Nantes Université, École Centrale Nantes, CNRS, LS2N, UMR 6004, F-44000 Nantes, France
- IMT Atlantique, Nantes Université, École Centrale Nantes, CNRS, LS2N, UMR 6004, F-44000 Nantes, France
- IMT Atlantique, Nantes Université, École Centrale Nantes, CNRS, LS2N, UMR 6004, F-44000 Nantes, France

date: "2022-07-13"
#doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Software and Systems Modeling
publication_short: SoSym

abstract: Executable Domain-Specific Languages (xDSLs) allow the definition and the execution of behavioral models. Some behavioral models are reactive, meaning that during their execution, they accept external events and react by exposing events to the external environment. Since complex interaction may occur between the reactive model and the external environment, they should be tested as early as possible to ensure the correctness of their behavior. In this paper, we propose a set of generic testing facilities for reactive xDSLs using the standardized Test Description Language (TDL). Given a reactive xDSL, we generate a TDL library enabling the domain experts to write and run event-driven TDL test cases for conforming reactive models. To further support the domain expert, the approach integrates interactive debugging to help in localizing defects, and mutation analysis to measure the quality of test cases.We evaluate the level of genericity of the approach by successfully writing, executing, and analyzing 247 event-driven TDL test cases for 70 models conforming to two different reactive xDSLs.
#summary: 
tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
#links:
#- name: Preprint
#  url: ''
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
