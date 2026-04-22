# Analysis of Scanning electron microscopy (SEM) and -energy dispersive X-ray spectroscopy (SEM-EDX) data

This repository contains the Quarto .qmd file, data, and generated figures related to analysis of scanning electron microscopy (SEM) data.
The samples were collected during the Synoptic Arctic Survey-2021. The collected seawater samples were first 1.2µm filtered to select prokaryotic fraction.
The samples were collected from 5 different stations at four different depths: Epipelagic (10m, Chl-a max) and Mesopelagic (Temp. max and 500m depth).
In the analysis, the samples were analysed using SEM and SEM-EDX to analyse cell shape, morphological features and elemental composition in both epipelagic and mesopelagic depth layers.
This provides the first electron microscopic analysis of natural prokaryotic communities from the Central Arctic Ocean (CAO).
Details about the expedition: https://www.polar.se/en/expeditions/previous-expeditions/arctic/synoptic-arctic-survey-2021/
The scanning electron micrographs has been uploaded at  https://doi.org/10.6084/m9.figshare.31158001


## View the rendered HTML report

Click the link below to view the full Quarto analysis report:
**[sas21-sem HTML Report](https://asve02.github.io/sas21-sem/sas21-sem.html)**

## System Requirements
-R (version 4.2.2)
-Quarto (https://quarto.org/docs/get-started/)
-R packages: readxl, tidyverse, ggplot2, broom, viridis, patchwork, 
  cowplot, rstatix, zoo, scales, ggpubr, magick, grid, FSA, dunn.test
-Tested on: Windows 11
-No non-standard hardware required

## Installation Guide
1. Install R: https://cran.r-project.org/
2. Install Quarto: https://quarto.org/docs/get-started/
3. Install required R packages:
   install.packages(c("readxl", "tidyverse", "ggplot2", "broom", 
   "viridis", "patchwork", "cowplot", "rstatix", "zoo", "scales", 
   "ggpubr", "magick", "grid", "FSA", "dunn.test"))
Typical install time: 2-5 minutes on a standard desktop

## Instructions for Use
Clone the repository and render the analysis in R terminal:
1. git clone https://github.com/asve02/sas21-sem
2. cd sas21-sem
3. quarto render sas21-sem.qmd

Expected output: sas21-sem.html with all figures reproduced
Expected run time: 2-3 minutes on a standard desktop
The data/ folder contains all input datasets required to run the analysis.


