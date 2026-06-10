Late Holocene niche construction and carrying capacity in Tairona chiefdoms of the Río Frío Basin, Sierra Nevada de Santa Marta, Colombia
--------------------------------------------------------------
This repository contains the code and pre-built spatial data for a study of long-term terrain engineering and settlement dynamics in a tropical mountain landscape. It applies niche construction theory to examine how three successive occupations modified and inherited the topographic settlement niche of the Río Frío basin. The analysis combines multi-criteria land suitability modeling, anisotropic Tobler walking-cost catchments, household-based demographic reconstruction, and sequential spatial point-pattern diagnostics on stone-terrace structures. The protocol is applied to three chronological periods in the Río Frío basin, Sierra Nevada de Santa Marta, namely Neguanje (AD 100–700), Buritaca (AD 700–1000), and Tairona (AD 1000–1600).

Repository Structure:
----------------------------------
1. Rdata:
   - Contains the pre-built spatial objects used in the analysis (vector layers as sf objects and raster layers packed with terra::wrap):
     • struc_neg.RData, struc_bur.RData, struc_tai.RData (stone-terrace structures by period)
     • sites_neg.RData, sites_bur.RData, sites_tai.RData (archaeological sites by period)
     • survey_sf.RData (boundary of the 52.2 km² survey area)
     • dem.RData (12.5 m ALOS PALSAR digital elevation model)
     • soil.RData (agricultural soil-suitability raster)
2. R Code Files:
   - The main R Markdown notebook contains the code to:
     a) Load required packages.
     b) Download the spatial objects directly from GitHub.
     c) Derive terrain and hydrological variables and perform the niche-construction and carrying-capacity analyses.
     d) Generate the figures and tables as presented in the manuscript.

Software and Key Package Versions:
----------------------------------
- R version: R 4.5.2
- Key R packages used in this project include (with version numbers):
    •  car: version 3.1.5
    •  corrplot: version 0.95
    •  dplyr: version 1.2.0
    •  furrr: version 0.4.0
    •  future: version 1.70.0
    •  gdistance: version 1.6.5
    •  ggplot2: version 4.0.2
    •  ggspatial: version 1.1.10
    •  knitr: version 1.51
    •  parallelly: version 1.46.1
    •  patchwork: version 1.3.2
    •  raster: version 3.6.32
    •  scales: version 1.4.0
    •  sf: version 1.0.24
    •  sp: version 2.2.1
    •  spatstat: version 3.6.0
    •  spatstat.explore: version 3.8.0
    •  spatstat.geom: version 3.7.3
    •  spatstat.random: version 3.4.5
    •  stringr: version 1.6.0
    •  terra: version 1.8.93
    •  tibble: version 3.3.1
    •  tidyr: version 1.3.2
    •  viridis: version 0.6.5

Getting Started:
----------------------------------
1. Clone or download this repository.
2. Open the main R Markdown notebook in RStudio.
3. Ensure that you have an active Internet connection; the code downloads the spatial objects directly from GitHub.
4. Run the notebook from top to bottom to reproduce the analysis and generate all figures and tables as presented in the manuscript.
5. For any issues or questions, contact the corresponding author.

Manuscript Summary:
----------------------------------
This article examines how pre-Columbian communities cumulatively modified a tropical mountain landscape in the Río Frío Basin, Sierra Nevada de Santa Marta, Colombia, through long-term terrain engineering across a settlement sequence spanning c. CE 100–1600. Rather than treating terrain as a passive environmental backdrop, the analysis interprets topographic and hydrological gradients as enduring components of a humanly modified mountain landscape. Results show that Neguanje and Buritaca occupations shared essentially the same topographic niche, whereas Tairona settlement expanded toward gentler slope positions without a robust shift in mean elevation or moisture availability. Slope was the only terrain variable that consistently differentiated the Tairona period from earlier occupations, and this contrast operated within long-inhabited settlement zones rather than between site locations. Cultivable land expanded substantially through time, but population growth during the Tairona period outpaced that increase, tightening the relationship between demographic demand and accessible productive land. Rather than estimating an absolute agronomic ceiling, the analysis evaluates whether cultivable terrain expanded at the same pace as household-based demographic estimates. The Río Frío case indicates that carrying capacity in tropical mountain landscapes operated as a historically mediated threshold, shaped through cumulative terrain modification and increasingly intensive use of inherited landscapes, rather than as a predetermined limit imposed by the physical environment.

For questions or further information, please contact: lms313@pitt.edu
