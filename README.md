# Exploring the variability of tropical savanna tree structural allometry with terrestrial laser scanning

This repository contains the analysis scripts of [Exploring the variability of tropical savanna tree structural allometry with terrestrial laser scanning](https://???). 

## System Requirements

#### R statistical freeware:
R version 3.6.0
  
#### R dependencies (packages):

* AICcmodavg_2.3-0
* car_3.0-8
* caret_6.0-86
* chngpt_2020.5-21
* devtools_2.3.1
* dplyr_1.0.0
* ggplot2_3.3.2
* ggpubr_0.4.0
* gridExtra_2.3
* nlme_3.1-139
* PairedData_1.1.1
* praise_1.0.0
* RColorBrewer_1.1-2
* tidyverse_1.3.0
* visreg_2.7.0
  
>_note: the code was written on a Windows 10 (V 1909) machine_

## Scripts

#### spatial_dist_survey_types
This script produces Figure 5, a spatial distribution map and histogram for manual and TLS survey.

#### paired_t-test
This script supports Figure 6, the difference in tree counts in the manual and TLS survey in simulated grid cells. The t-test evaluates the statistical difference between the manual and TLS survey.

#### DBH_field_vs_LiDAR
This script produces Figure 7, comparing the DBH measured for individual trees in the manual and TLS survey.

#### DBH_vs_Crown 
This script produces figure 8, exploring the relationship between DBH and tree crown size.

>_note: the working directory will need to be specified by the user_
