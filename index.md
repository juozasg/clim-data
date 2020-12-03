# Juozas Gaigalas

## Introduction

This project investigates the connection between El Nino, the Arctic Oscillation and Arctic Surface Albedo. Since Both ENSO and AO effect air temperature and precipitation, both phenomena should have an impact on albedo measured in the arctic. Colder temperatures and increased precipitation would yield more snowfall and less melting of ice. This project attempts to demonstrate that by simple correlation of monthly averages of albedo reflectance and the two indeces. The Arctic System Reanalysis dataset was selected because it contains a many variables that could be used for physical modeling of changes in arctic surface reflectance - a critical climate feedback dynamic.



## Data

Arctic System Re-Analysis (Version 2) data from National Center for Atmospheric Research and Ohio State University was selected. The dataset is available at UCAR Research Data Archive: https://rda.ucar.edu/datasets/ds631.1/. It was produced from Polar Weather Research and Forecasting Model (PWRF) and High Resolution Land Data Assimilation (HRLDAS) weather research models. 

ASR contains multiple products. This project uses ASRv2 15km monthly means of analysis products. The data product is presented on a 15km irregular grid. For analysis, it's regridded 0.1 degree grid using the ESMF 'bilinear' method.

ASR `ALBEDO` variable is used. Albedo is a fractional values from 0.0 to 1.0. It represents solar radiation reflection with 1.0 representing maximum reflection of solar energy. Real snow and reflects energy unevenly across the EMF spectrum - albedo is a powerful single number approximation of physical reflectivity.  

Arctic Oscillation (or Northern Hemisphere Annular Mode) index is correlated with albedo anomalies to explore the feedback between atmospheric circulation and land. AO  the primary atmospheric mode in the Arctic and has many effects that are detailed here: https://www.ncdc.noaa.gov/teleconnections/ao/

"The Arctic Oscillation (AO) is a large scale mode of climate variability, also referred to as the Northern Hemisphere annular mode. The AO is a climate pattern characterized by winds circulating counterclockwise around the Arctic at around 55°N latitude. When the AO is in its positive phase, a ring of strong winds circulating around the North Pole acts to confine colder air across polar regions. This belt of winds becomes weaker and more distorted in the negative phase of the AO, which allows an easier southward penetration of colder, arctic airmasses and increased storminess into the mid-latitudes."

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/14/Arctic_Oscillation_II.svg/1200px-Arctic_Oscillation_II.svg.png" width="200" />

Nino34 index is also used. It describes the intensity of El Nino/La Nina modes in terms of gradient in sea surface temperature of two locations in the Pacific Ocean.


## Code Description

## Results

## Summary
