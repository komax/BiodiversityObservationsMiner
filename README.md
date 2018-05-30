[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1036826.svg)](https://doi.org/10.5281/zenodo.1036826)

[![GitHub release](https://img.shields.io/github/release/Naereen/StrapDown.js.svg)](https://GitHub.com/fgabriel1891/BiodiversityObservationsMiner/releases/)

[![GitHub issues](https://img.shields.io/github/issues/Naereen/StrapDown.js.svg)](https://GitHub.com/fgabriel1891/BiodiversityObservationsMiner/issues/)

[![CC-0 license](https://img.shields.io/badge/License-CC--0-blue.svg)](https://creativecommons.org/licenses/by-nd/4.0)


# Biodiversity Observations Miner

A web application to unlock primary biodiversity data from published literature

## Running the application 

### In personal server: 

Use this [link](https://fgabriel1891.shinyapps.io/biodiversityobservationsminer/) to run the application online  (free)

### To run locally in your computer:  
 
 1.- Fork or download the repository to a directory on your computer
 
 2.- Open the R Project container file
 
 3.- Make sure you have all R packages installed and updated to run the app (see below) 
 
 4.- Run the app with RStudio. 
 
 
 >  Alternatively, you can run the `shiny::runGitHub()` function. Function arguments: `repo= "BiodiversityObservationsMiner", username= "fgabriel1891"`.
 
*Important!* 
 Before using Biodiversity Observations Miner locally we recommend to have [R](https://www.r-project.org/) and [Rstudio](https://www.rstudio.com/) installed and up to date. 

**Consider this before using the app in the server or locally**

>  For the moment I only have a Starter Shiny server account. This limits the app to a couple of running hours / users per month. Until I solve this issue (either financing a [pro](https://www.rstudio.com/products/shiny-server-pro/) server, or deploying my own (however, this will take me to do some more time)  please consider using the current server as a testing ground for the app functionalities. If you want to mine a considerable number of literature files please run the app locally at your computer. 


For comments, suggestions and bugs please open an [issue](https://github.com/fgabriel1891/BiodiversityObservationsMiner/issues/new)

--------

### About 

The idea to develop this web application is set in the context of increasing the digital mobility and interoperbility of biodiversity data wordwide. I developed Biodiversity Observations Miner with guidance and input from [W. Daniel Kissling](https://www.danielkissling.de/) and [Emiel van Loon](https://staff.fnwi.uva.nl/e.e.vanloon/) of the [Institute of Biodiversity and Ecosystems Dynamics (IBED)](http://ibed.uva.nl/) from the University of Amsterdam (UvA). 

#### R packages required

- shiny
- shinythemes
- shinydashboard
- stringi
- stringr
- taxize
- tidyverse
- tidytext
- tibble
- widyr
- fulltext
- tm
- DT

### Acknowledgements 

Biodiversity Observations Miner uses tools from GNA (GlobalNamesArchitecture) implemented in the taxize package. Thanks to Scott Chamberlain for modifications to taxize that improved the functionality of this application. Credits to the developers of the individual packages that Biodiversity Observations Miner is dependent on. Terms composing the pollination biodiversity dictionary were selected in collaboration with Joan Casanelles. 
