This directory contains R scripts for the MaxEnt-ETRHEQ-WET model, including both the core modelling workflow and the scripts used to generate all figures presented in the manuscript.

####################################################################################################
Folder Descriptions:

MaxEnt-ETRHEQ-WET/
Contains the core R scripts for implementing the MaxEnt-ETRHEQ-WET model to estimate surface energy fluxes (LE, H, G, Ts, RHs) in wetland ecosystems at half-hourly, hourly, daily, weekly and monthly timescales.

ERA5_friction_velocity_download/
Includes a R script for downloading ERA5 friction velocity data (u*) via the ECMWF Climate Data Store API, specifically for the wetland study sites.

Distance_from_coast/
Contains an R script and data for calculating the distance of each study site from the nearest coastline.

Tutorial/
Provides a step-by-step guide for implementing the MaxEnt-ETRHEQ-WET model at an hourly timescale, incorporating ERA5 friction velocity data. This tutorial includes detailed explanations of required data inputs and each key modeling component.

##############
If you have any questions, please feel free to reach out to Yi Wang (yi.wang1@uwaterloo.ca).

