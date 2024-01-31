# MaxEnt-ETRHEQ-WET
R scripts and datasets for the study by Wang et al., "An effective formulation for estimating wetland surface energy fluxes from weather data"
The "MaxEnt-ETRHEQ for FLUXNET and AmeriFlux wetland sites" directory contains five subfolders. These subfolders are dedicated to modeling energy fluxes at four temporal resolutions—Subdaily (half-hourly), daily, weekly, and monthly—and to calculating the proximity of the sites to the coastline.

##############
In each timescale folder, there are four R scripts files:
method_ns.R (MaxEnt-ETRHEQ function to model H and LE, assuming constant soil thermal inertia (Is):1300 tiu)
method_theta.R (MaxEnt-ETRHEQ function to model H and LE, using soil moisture (theta) to calculate Is.
timescale_no_theta.R (applying method_ns.R to wetland sites)
timescale_theta.R (applying method_theta.R to wetland sites)

Data at each time scale at each site are provided in each timescale folder. These datasets were directly obtained from the FLUXNET and AmeriFlux websites without any alterations.
For each timescale, ensure that the four R scripts along with the corresponding data for that scale are placed within the same folder.
When executing the script for modeling half-hourly energy fluxes, the process may require up to 3-4 hours to complete for each site. However, for other time scales, the modeling typically takes less than 3 minutes for each site.

##############
In the "Distance from coast" subfolder, there are one R script file entitled "Distance_from_coast" and one data file entitled "Global_sites". Global_sites.csv contains the coordinates of the study sites.

##############
If you have any questions, please feel free to reach out to Yi Wang (yi.wang1@uwaterloo.ca).
