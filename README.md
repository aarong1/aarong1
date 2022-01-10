# <p align=center >Data Science Repo</p>
<!--# ========== -->
<p align=center >Containing code snippets for niche topics and workflows as well as formatting common design patterns into packages.</p>

<img align='right' src='https://github.com/aarong1/RshinyHelpers/blob/main/man/figures/logo.png'></img>
## RshinyHelpers
- Check out the **RshinyHelpers** package for [_#rstats_](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwiL8ra1gJL1AhWth_0HHVlEDKwQFnoECAIQAQ&url=https%3A%2F%2Fwww.r-project.org%2F&usg=AOvVaw1dEKAtw6XqNnWPRNby8Tne) users that accumulates helpful shiny elements and css helpers that 
I use only once or twice per shiny app.  Also contains misc data functions that I find intuitive but don't fit any tidy workflow.

- It is not available on CRAN. Install using `devtools`

```R
  if(!require(devtools)) install.packages('devtools')
    devtools::install_github('aarong1/RshinyHelpers')
```

and attach the package into global namespace

```R 
  library(Rpack)
```

*Due to my own mistake the git repo is miss named from the R package.* 

## Personal sites

Not really being a developer, extensive use of static rendered sites helped for CVs and documentation.  They were used successfully, and with a low overhead, to simplify html, js interactivity and deployment to Github Pages and Netlify.

Hugo and GatsbyJS were popular options in this instance and would recommend either for use, both with a selection of pre built theming options.

Gatsby in particular had a steep learning curve, being based on reactjs, but inevitably had the greatest reward.

## Table of Contents

###Itemised repo list

Repo            | What is it            | Tech                   | Access       |  
-------------   | ----------            |---------               |-----------   |
[RshinyHelpers](https://github.com/aarong1/RshinyHelpers)| R package             | R, shiny, js, html, css|[Documentation](https://aarong1.github.io/RshinyHelpers/index.html)                            |
TCD_Ising_Model | Ferromagnetic simulation    | Python                 |              |
Geospatial      | NI PC Shapefiles    | R                      |              |
Covid ABM       | Agent based Epi model     | Python                 |              |   |
Persistent Storage| Fullstack Shiny w/aws backend| R, AWS, mysql          |              |
Epidemiology model| Bayesian Epi Model      | R,stan                 |[Documentation](https://aarong1.github.io/Epidemiology_forecast/)                              |
aarong1.github.io| GH pages site        |Gatsbyjs, reactjs, html, css, js|[Personal Site](https://aarong1.github.io)|
Academic        |  Professional Site    | Hugo, netlify          |  [CV](https://quirky-mirzakhani-76fdc1.netlify.app/) |


_Aaron_
