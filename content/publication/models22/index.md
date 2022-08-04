---
title: "Automatic Test Amplification for Executable Models"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Erwan Bousse
- Jean-Marie Mottu
- Gerson Sunyé
- Pablo Gómez-Abajo
- Pablo C.Cañizares
- Esther Guerra
- Juan de Lara

# Author notes (optional)
author_notes:
- IMT Atlantique, Nantes Université, École Centrale Nantes, CNRS, LS2N, UMR 6004, F-44000 Nantes, France
- IMT Atlantique, Nantes Université, École Centrale Nantes, CNRS, LS2N, UMR 6004, F-44000 Nantes, France
- IMT Atlantique, Nantes Université, École Centrale Nantes, CNRS, LS2N, UMR 6004, F-44000 Nantes, France
- IMT Atlantique, Nantes Université, École Centrale Nantes, CNRS, LS2N, UMR 6004, F-44000 Nantes, France
- Universidad Autónoma de Madrid, Madrid, Spain
- Universidad Autónoma de Madrid, Madrid, Spain
- Universidad Autónoma de Madrid, Madrid, Spain
- Universidad Autónoma de Madrid, Madrid, Spain

date: "2022-07-13"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 25th ACM/IEEE International Conference on Model Driven Engineering Languages and Systems*
publication_short: In *Proceedings of the 25th ACM/IEEE International Conference on Model Driven Engineering Languages and Systems (MODELS)*

abstract: 'Behavioral models are important assets that must be thoroughly verified early in the design process. This can be achieved with manuallywritten test cases that embed carefully hand-picked domain-specific input data. However, such test cases may not always reach the desired level of quality, such as high coverage or being able to localize faults efficiently. Test amplification is an interesting emergent approach to improve a test suite by automatically generating new test cases out of existing manually-written ones. Yet, while ad-hoc test amplification solutions have been proposed for a few programming languages, no solution currently exists for amplifying the test cases of behavioral models. In this paper, we fill this gap with an automated and generic approach. Given an executable DSL, a conforming behavioral model, and an existing test suite, the proposed approach generates new regression test cases in three steps: (i) generating new test inputs by applying a set of generic modifiers on the existing test inputs; (ii) running the model under test with new inputs and generating assertions from the execution traces; and (iii) selecting the new test cases that increase the mutation score. We provide tool support for the approach atop the Eclipse GEMOC Studio and show its applicability in an empirical study. In the experiment, we applied the approach to 71 test suites written for models conforming to two different DSLs, and for 67 of the 71 cases, it successfully improved the mutation score between 3.17% and 54.11% depending on the initial setup.'
#summary: 
tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
#links:
#- name: Preprint
#  url: ''
url_pdf: https://hal.archives-ouvertes.fr/hal-03745034
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
