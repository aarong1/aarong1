Aarons Repo
==========
Containing mostly code snippets for niche topics, and workflows.

## RshinyHelpers
- Check out the **RshinyHelpers** package for [_#rstats_](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwiL8ra1gJL1AhWth_0HHVlEDKwQFnoECAIQAQ&url=https%3A%2F%2Fwww.r-project.org%2F&usg=AOvVaw1dEKAtw6XqNnWPRNby8Tne) users that accumulates helpful shiny elements and css helpers that 
I use only once or twice per shiny app.  Also contains misc data functions that I find intuitive but dont fit any tidy workflow.

- It is not available on CRAN. Install using

```R
  if(!require(devtools)) install.packages('devtools')
    devtools::install_github('aarong1/RshinyHelpers')
```

and load the package into global namespace

```R 
  library(Rpack)
```


*Due to my own mistake the git repo is miss named from the R package.* 

## Personal sites

Extensive use of statically rendered sites for personal sites,CVs and documentations were used to simplify html rendering and js interactivity Hugo and GatsbyJS were popular options in this instance and would recommend either for use and selection of pre built theming options.

## Table of Contents

Itemised repository
list
repo            | What is it            | Tech                |  Accompanying Docs                                |Access |  
-------------   | ----------            |---------            |--------------------                               |-------    |
RshinyHelpers   | R package             | R, shiny, js, html, css|https://aarong1.github.io/RshinyHelpers/index.html                             |   |
TCD_Ising_Model | Ferromagnetism sim    | Python              |                                                   |   |
Geospatial      | Pc stub shapefiles    | R                   |                                                   |   |
covid_ABM       | Agent based model     | Python              |                                                   |   |
persistent_store| Shiny w/aws backend| R, AWS, mysql       |                                                   |   |
epidemiology_model| Bayesian model  | R,stan              |https://aarong1.github.io/Epidemiology_forecast/  |   |
aarong1.github.io| gh pages site |Gatsbyjs, reactjs, html, css, js    |                                        |https://aarong1.github.io|
academic        |  professional site | Hugo, netlify       |  |https://quirky-mirzakhani-76fdc1.netlify.app/ |


_Aaron_

agorman2@sheffield.ac.uk
