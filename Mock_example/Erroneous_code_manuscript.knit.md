---
title             : "The effect of erroneous R code on student performance"
shorttitle        : "Erroneous R code"

author: 
  - name          : "James Bartlett"
    affiliation   : "1"
    corresponding : yes    # Define only one corresponding author
    address       : "62 Hillhead Street, Glasgow"
    email         : "james.bartlett@glasgow.ac.uk"
    role:         # Contributorship roles (e.g., CRediT, https://casrai.org/credit/)
      - "Conceptualization"
      - "Writing - Original Draft Preparation"
      - "Writing - Review & Editing"

affiliation:
  - id            : "1"
    institution   : "University of Glasgow, United Kingdom"

authornote: |
  Enter author note here.

abstract: |
  Blah blah blah. 
  
keywords          : "learning, R, statistical programming, error-full learning"
wordcount         : "1200"

bibliography      : ["references.bib", "r-references.bib"]
csl               : apa7.csl

floatsintext      : no # 
linenumbers       : yes # Add line numbers? 
draft             : no # Add draft watermark on every page? 
mask              : no # Hide author details for blind submission? 

figurelist        : no # Add figure list? 
tablelist         : no # Add table list? 
footnotelist      : no # Add footnote list? 

classoption       : "man"
output            : papaja::apa6_pdf # Can change ending to _word to knit to Word
---





Data skills are increasingly recognised as a key component of psychological literacy. To promote reproducible data preparation and analysis workflows, educators have highlighted the role of teaching students how to use statistical programming languages instead of point-and-click software [@mcaleer_embedding_2022]. However, programming is rare in UK psychology curricula [@targ_meta-research_group_statistics_2022] and offers unique challenges such as how to prepare students to debug their code. Debugging code is a separate problem solving skill to learn alongside statistics, so it is important to understand how best to teach students debugging skills. 

@hoffman_students_2021 reported a small pilot study using SAS where they compared a traditional error-free course structure to an error-full course focusing on debugging errors alongside key concepts. 80% of students preferred the error-full course but the study only included 18 participants and just 4 students completed assignments following each course, meaning they could not compare performance. Therefore, in our study, we want to apply these methods to the programming language R and recruit a larger sample. 

We hypothesise that students who complete the error-full lecture will score higher on a data skills assignment than students who complete the error-free lecture. 

# Methods

## Participants



Before collecting data, we performed an *a priori* power analysis to calculate how many participants we would need. @hoffman_students_2021 did not report any performance data, so we used @bebermeier_creating_2019 to set our smallest effect size of interest. They investigated the effect of creating statistics exercises based on research article. The researchers found students performed better on a class assignment when they completed these exercises than when students did not complete the exercises (*d* = 0.55). The authors did not comment on the effect size, so we chose a more conservative estimate based on the small telescopes approach [@simonsohn_small_2015] for the effect size the original study had 33% power to detect. Using an effect size of d = 0.38, we aimed to recruit 149 participants per group for an independent samples t-test (\alpha = 0.05, power = 0.90). 

We finished with two groups of 145 and 130 participants, slightly fewer than our initial target. 

## Material

## Procedure

## Data analysis

We used R [Version 4.1.2\; @R-base] and the R-packages *dplyr* [Version 1.0.7\; @R-dplyr], *forcats* [Version 0.5.1\; @R-forcats], *ggplot2* [Version 3.3.5\; @R-ggplot2], *papaja* [Version 0.1.1\; @R-papaja], *purrr* [Version 0.3.4\; @R-purrr], *pwr* [Version 1.3.0\; @R-pwr], *readr* [Version 2.1.0\; @R-readr], *shiny* [Version 1.7.3\; @R-shiny], *stringr* [Version 1.4.1\; @R-stringr], *tibble* [Version 3.1.6\; @R-tibble], *tidyr* [Version 1.1.4\; @R-tidyr], *tidyverse* [Version 1.3.1\; @R-tidyverse], and *tinylabels* [Version 0.2.3\; @R-tinylabels] for all our analyses.

# Results






# Discussion


\newpage

# References

::: {#refs custom-style="Bibliography"}
:::
