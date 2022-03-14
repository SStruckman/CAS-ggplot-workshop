# ggplot Workshop
Built for EC Workshop March 2022
Soren Struckman

## Getting started
If you are participating in the workshop, you may either (a) work on the [ggplot-workshop-TEMPLATE.Rmd](https://github.com/sstruckman/EC-ggplot-workshop/blob/main/ggplot-workshop-TEMPLATE.Rmd), which leaves space for participants to type code with instruction, or (b) follow along along in the [ggplot-workshop-KEY.Rmd](https://github.com/sstruckman/EC-ggplot-workshop/blob/main/ggplot-workshop-KEY.Rmd), which has all of the information and code we will be working with. Download the [ggplot-workshop-KEY.html](https://github.com/sstruckman/EC-ggplot-workshop/blob/main/ggplot-workshop-KEY.html) for a knitted (and much easier to read) version of the KEY.

Outline

1. Brief Reminder: How do we use the tidyverse?
2. Overview of the "grammar of graphics" philosophy behind ggplot
3. What is ggplot? - Useful functions and concepts for making publication-quality figures
4. Making multi-panel figures with `patchwork`
5. Some tips for saving plots to disk
* Bonus: intro to plotting spatial data with `sf`

## Data source
All [dragon data](http://search.r-project.org/R/R/library/DALEX/html/dragons.html) is from the `DALEX` package. Bonus `sf` content also uses EPA air quality data, wrangled by Ellie Smith-Eskridge and Dakoeta Pinto.

## Species of interest
We'll be wrangling and plotting data for a subset of chromatic dragons:

|     Common name     |      Scientific name      |
|---------------------|---------------------------|
|     Common black     |     *Jaggermeryx ozzyi*    |
|     Scaley longtail    |    *Jaggermeryx whido*    |
|     Sharptoothed flier    |     *Jaggermeryx strummeri*    |
|     Fiery blue     |    *Sauroniops naida* |
|     Four-toed scale-back   |     *Sauroniops reike*    |

## Attribution
The code and materials in this repository are adapted from and heavily inspired by those compiled by [Britta Schumacher](https://github.com/blschum/CAS-ggplot-workshop) and [Simona Picardi](https://ecorepsci.github.io/reproducible-science/ggplot2.html). 
