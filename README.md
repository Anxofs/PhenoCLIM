[<img align="left" width="150" height="150" src="https://github.com/CLIMtools/PhenoCLIM/blob/master/www/picture2.png">](https://rstudio.aws.science.psu.edu:3838/aaf11/PhenoCLIM/ "PhenoCLIM")

# [PhenoCLIM](https://rstudio.aws.science.psu.edu:3838/aaf11/AraCLIM/ "AraCLIM")
[**PhenoCLIM**](https://rstudio.aws.science.psu.edu:3838/aaf11/AraCLIM/) (https://rstudio.aws.science.psu.edu:3838/aaf11/AraCLIM/)is an SHINY component of [**Arabidopsis CLIMtools**](http://www.personal.psu.edu/sma3/CLIMtools.html) (http://www.personal.psu.edu/sma3/CLIMtools.html) that provides an interactive spatial analysis web platform using Leaflet. Data points represent the sites of collection of sequenced *Arabidopsis thaliana* accessions in an interactive world map. [**AraCLIM**](https://rstudio.aws.science.psu.edu:3838/aaf11/AraCLIM/). The user can choose an environmental variable that is displayed on the map using a color gradient within the ranges and units detailed in the color palette within the map. Clicking on any of the data points on the map provides information on the selected accession, including its curation details, and the value of the chosen environmental variable for the selected accession.

[**PhenoCLIM**](https://rstudio.aws.science.psu.edu:3838/aaf11/AraCLIM/) allows allows the inspection of two environment variables simultaneously using the ggvis package in SHINY. The more than 200 environmental variables that can be selected on the map can be compared with a second environmental variable that is user-specified; the two variables are displayed with a linear correlation provided based on data for the local environments of the 1,131 accessions. We also provide an interactive tabulated database describing the environmental variables available at [**AraCLIM**](https://rstudio.aws.science.psu.edu:3838/aaf11/AraCLIM/), including their source, units and period of data collection using the DT package in SHINY.

## [Data availability](https://github.com/CLIMtools/AraCLIM/tree/master/data)

The environmental data compiled in our study is available in the data/ folder. One of the data files contains the data, and the second one contains the description and the source of each of the environmental parameters used. For a more detailed description of these, please check the SI of our study.

The phenotypic data described here, was downloaded from AraPheno [**PhenoCLIM**](https://arapheno.1001genomes.org/). If you use it, please cite Arapheno, and refer to the description file to acknowledge the appropiate originators of the data you used.
## [Citation](https://www.nature.com/articles/s41559-018-0754-5)
**Ferrero-Serrano, Á & Assmann SM.** Phenotypic and genome-wide association with the local environment of Arabidopsis. Nature Ecology & Evolution. doi: 10.1038/s41559-018-0754-5 (2019)

