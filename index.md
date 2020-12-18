--- 
title: "Course Workflows [HU OSIRIS: tlsc-dsfb26v-20_workflows]"
author: "Alyanne de Haan, PhD; Bas van Gestel, PhD; Rene van der Ploeg, PhD; Chris van Oevelen, PhD; Marc Teunis, PhD"
date: "2020-12-17 09:53:33"
site: bookdown::bookdown_site
output:
  bookdown::html_book:
    theme: darkly
bibliography: [references.bib]
biblio-style: apalike
link-citations: yes
always_allow_html: yes
github-repo: "uashogeschoolutrecht/tlsc-dsfb26v-20_workflows"
description: "This is the course on managing and setting up workflows for collaboration, data analysis pipeline and reporting"
params:
  geo_id: NL BE
  month: February March April May June July August September October November December
  year: 2020
---










# Course introduction

<mark>[   write general introduction on the course contents, we do not need a list because the contents can be derived from the table of contents, which will be the ground truth for the course contents]</mark>
 
<global setup of the course - REMOVE> 
scrum: hoe moet dat en hoe gaan we dat deze cursus ondersteunen. scrum moeten ze toepassen op projecticum.

Lesson 2 

## Uitleg en opzetten eigen github

o basic git workflow in commandline
o Start github
o Push en pull
o clone
o koppelen Rstudio

git: toepassen: voorbeeld-cases, koppelen aan Rstudio
o branching per fix en merging, braches pushen
o backtracking?

git: toepassen: groepsproject met bestanden projecticum
o teamwork: hoe samenwerken met git (wijs hoofd merge requests aan)
o github merge requests

Rmarkdown: Uitleg en zelf doorwerken voorbeelden (let op aansluiting met eventuele rmarkdown in daur1)
o Overzicht Formats (pdf, websites, books, dashboards)
o Basic syntax

o website online zetten via github 6. Rmarkdown: toepassen: o Meer syntax o rapporten (tekstbestanden) genereren (reproducible reports) 7. Rmarkdown: toepassen: o opzetten eigen Rmarkdown-homepage met informatie over ontwikkeling van student tijdens deze cursus. (projecticum, opdrachten SQL en GIT deze cursus)

SQL: Uitleg en zelf doorwerken voorbeelden
o mySQL?
o syntax basics
o toepassing basics
SQL: toepassen:
o SQL binnen Rstudio
o voorbeeld-cases uit life sciences
SQL: toepassen
o op data projecticum (of indien ongeschikt zelf in te brengen casus) en online presenteren op Rmarkdown-homepage


## Purpose of this website
This website is a `{bookdown}`project that forms the reader and learning content for the course 


## Course contents & materials

<p style="font-size:18px">The complete source code for this reader can be found here:

[1] "https://github.com/DataScienceILC/tlsc-dsfb26v-20_workflows"


## Getting the materials
To compile this website locally, first clone the website repository from 

```
## # A tibble: 1 x 1
##   url                                                        
##   <chr>                                                      
## 1 https://github.com/DataScienceILC/tlsc-dsfb26v-20_workflows
```

then run `devtools::install(".")` from within the cloned repo directory. This will install all the dependent R-packages.

To compile the book-site locally run `bookdown::render(".")` from inside the cloned repo. This repository can also be used to access the course materials directly in RStudio during the workshops.

Last, you can also access all the functions that are associated with this project by running `devtools::build(".")`, to share or store the package `{workflows}` as a binary archive file.
 
## Getting R and RStudio
During the course you can work on a Cloud Computing Environment which provides web access to R and RStudio via a Virtual Machine. This machine runs a server edition of RStudio and has the latest R version and all the required packages available. In order to access the server you will need credentials, which you will recieve before the course starts. This is a convenient way to use R in a course and during the course we will only be using this environment. This is to ensure reproducibility and prevents a lot of trouble shooting from your side and the teacher's side.

The server can be found here https://datascience.hu.nl/rstudio/tlsc-dsfb26v-20/. You will get credentials for the server, before the course starts.

If you want to use R and RStudio locally on your laptop, this is where you can download the software from:

[RStudio](https://www.rstudio.com/products/rstudio/download/) 

[R](https://cran.r-project.org/)

## The `{bookdown}` package
This website was created using the `{bookdown}` [@R-bookdown] package written by Yihui Xie. The package can be downloaded from CRAN. For more information see the [documentation](https://bookdown.org/yihui/bookdown/).

The `{bookdown}` package can be installed from CRAN or Github:


```r
install.packages("bookdown")
# or the development version
# devtools::install_github("rstudio/bookdown")
```