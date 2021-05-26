---
title: "Analyzing the sensitivity of multi-objective software architecture refactoring to configuration characteristics"
authors:
- Vittorio Cortellessa
- admin
date: "2021-05-16T00:00:00Z"
doi: "10.1016/j.infsof.2021.106568"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-05-16T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Internation Journal of Information and Software Technology*
publication_short: In *InfSoft*

abstract: "**Context:**

Software architecture refactoring can be induced by multiple reasons, such as satisfying new functional requirements or improving non-functional properties. Multi-objective optimization approaches have been widely used in the last few years to introduce automation in the refactoring process, and they have revealed their potential especially when quantifiable attributes are targeted. However, the effectiveness of such approaches can be heavily affected by configuration characteristics of the optimization algorithm, such as the composition of solutions.
</br>
**Objective:**
In this paper, we analyze the behavior of EASIER, which is an Evolutionary Approach for Software archItecturE Refactoring, while varying its configuration characteristics, with the objective of studying its potential to find near-optimal solutions under different configurations.
</br>
**Method:**
In particular, we use two different solution space inspection algorithms (i.e., NSGA−II and SPEA2) while varying the genome length and the solution composition.
</br>

**Results:**
We have conducted our experiments on a specific case study modeled in Æmilia ADL, on which we have shown the ability of EASIER to identify performance-critical elements in the software architecture where refactoring is worth to be applied. Beside this, from the comparison of multi-objective algorithms, NSGA−II has revealed to outperform SPEA2 in most of cases, although the latter one is able to induce more diversity in the proposed solutions.
</br>
**Conclusion:**
Our results show that the EASIER thoroughly automated process for software architecture refactoring allows to identify configuration contexts of the evolutionary algorithm in which multi-objective optimization more effectively finds near-optimal Pareto solutions.

"
# Summary. An optional shortened abstract.
summary: 

tags:
- 
featured: true

#links:
#- name:

url_pdf: 'https://doi.org/10.1016/j.infsof.2021.106568'
url_code: 'https://github.com/SEALABQualityGroup/EASIER'
#url_dataset: '#'
#url_poster: '#'
#url_project: 'megamart'
#url_slides: 'https://speakerdeck.com/danieledipompeo/performance-driven-software-model-refactoring'
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'EASIER process'
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

