# Visualizing the Impact of the Thomas Fire
 
## About
This repository is dedicated to visualizing the impact of the Thomas Fire, which burned over 280,000 acres in Ventura and Santa Barbara counties in December 2017, by utilizing satellite-based false color imagery from remote sensing data and air quality index (AQI) historical data. This project highlights the fire scar, burn severity, and the before and after analysis of the air quality time series.

## Repository Structure
The repository is organized as follows:
 
/data: Contains raw files of the Landsat satellite and AQ the exported shapefile of the Thomas Fire perimeter.
 
README.md: This file provides an overview of the repository and how to use it.

Thomas_Fire_Blog.ipynb: Process the satellite imagery and AQI historical dataset to assess the environmetal impact of the Thomas Fire 2017.

## Data
The data used in this project comes from: 

1. Microsoft Planetary Computer Data Catalogue - Landsat satellite imagery, used to create false color images
   
2. California fire perimeters - Contains all fire perimeters in the state of California.
   
4. EPA Air Quality Index - This dataset is key indicator of air pollution, which will help assess the short- and long-term impact of the fire
 
Data access: The raw Landsat dataset can be found in the data folder or downloaded from  Microsoft Planetary Computer Data Catalogue. The California fire perimeter shapefiles could not be included in the repository due to its large size, this file can be downloaded from https://catalog.data.gov/dataset/california-fire-perimeters-all-b3436. The air quality data can be extracted from the  U.S. Environmental Protection Agency (EPA): https://www.epa.gov/outdoor-air-quality-data.

## References
Microsoft. (2024). Landsat Collection 2 Level-2. Microsoft Planetary Computer Data Catalogue. Retrieved November 14, from https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2

Data.gov. (2024). California fire perimeters (all). CAL FIRE. Retrieved November 14, 2024, from https://catalog.data.gov/dataset/california-fire-perimeters-all-b3436

U.S. Environmental Protection Agency (EPA). (2017-2018). Air Quality Index (AQI). Air Now. Retrieved October 22, 2024, from https://www.epa.gov/outdoor-air-quality-data

 
**This project was created as part of the EDS 220: Environmental Data Science course at UCSB.**
 
