+---
title: "Adapting TDL to Provide Testing Support for Executable DSLs"

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
- LS2N, IMT Atlantique, Nantes, France
- LS2N, Université de Nantes, Nantes, France
- LS2N, Université de Nantes, IMTAtlantique, Nantes, France
- LS2N, Université de Nantes, Nantes, France

date: "2021-06-23"
doi: "10.5381/jot.2021.20.3.a6"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Journal of Object Technology
publication_short: JOT

abstract: Testing is one of the most prevalent and successful verification and validation (V&V) techniques used in the field of software engineering. While a large number of testing frameworks exist for general-purpose programming languages, providing testing facilities for any given executable Domain Specific Language (xDSL) remains a costly and challenging task. In this context, a standard such as the Test Description Language (TDL) appears as a suitable foundation for the definition of a generic testing approach for xDSLs. Unfortunately, TDL does not provide the domain-specific concepts required to write test cases for a given xDSL and does not include any model execution facilities. Our contribution addresses these limitations and thereby provides a fully generic testing approach for xDSLs based on TDL. Required TDL domain-specific concepts are automatically inferred from the xDSL definition through a model transformation into TDL. Model execution facilities are provided through the definition of a refined operational semantics for TDL. The application of our approach on 5 different xDSLs shows its generality and that it can successfully be used for testing executable models.# Summary. An optional shortened abstract.
#summary: 
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
   url: http://www.jot.fm/contents/issue_2021_03/article6.html

url_pdf: https://hal.archives-ouvertes.fr/hal-03265196/document
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
slides: "ecmfaPresentation"
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).