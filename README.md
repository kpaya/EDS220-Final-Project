# Visualizing the Impact of the Thomas Fire Using False Color Imagery
 
## About
This repository is dedicated to visualizing the impact of the Thomas Fire, which burned over 280,000 acres in Ventura and Santa Barbara counties in December 2017. By utilizing satellite-based false color imagery from remote sensing data, this project highlights the fire scar, burn severity, and vegetation health.
 
## Repository Structure
The repository is organized as follows:
 
/data: Contains raw files of the Landsat satellite and the exported shapefile of the Thomas Fire perimeter.
 
README.md: This file provides an overview of the repository and how to use it.
 
hwk4-task2-fire-perimeter-Paya.ipynb: Creates the Thomas Fire perimeter polygon and saves the .shp in the data folder.

hwk4-task2-fire-scar-Paya.ipynb: Process the satellite imagery and assess the environmetal impact of the Thomas Fire 2017.

## Data
The data used in this project comes from: 

1. Microsoft Planetary Computer Data Catalogue - Landsat satellite imagery, used to create false color images
   
2. California fire perimeters. Contains all fire perimeters in the state of California.
 
Data access: The raw Landsat dataset can be found in the data folder or downloaded from  Microsoft Planetary Computer Data Catalogue. The California fire perimeter shapefiles could not be included in the repository due to its large size, this file can be downloaded from https://catalog.data.gov/dataset/california-fire-perimeters-all-b3436.

## References
Microsoft. (2024). Landsat Collection 2 Level-2. Microsoft Planetary Computer Data Catalogue. Retrieved November 14, from https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2

Data.gov. (2024). California fire perimeters (all). CAL FIRE. Retrieved November 14, 2024, from https://catalog.data.gov/dataset/california-fire-perimeters-all-b3436

 
**This project was created as part of the EDS 220: Environmental Data Science course at UCSB.**
 
