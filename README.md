# Homework 3: Visualizing The Impact of the 2021 Winter Storm in Texas

### By Stephan Kadonoff

![Pipe Bursts in Freezing Texas](https://i.dailymail.co.uk/1s/2025/01/06/21/93801863-14256091-Subzero_temperatures_gripped_Texas_on_Feb_18_2021_as_power_was_r-a-31_1736198000246.jpg)

## Purpose
This repository was created to explore and visualize the impact of the 2021 Polar Vortex Storm that impacted many parts of Texas. Specifically, we will be focusing on the Houston Metropolitan area, and will utilize Raster based images to determine the change in night-time lighting due to the weather caused blackouts. Lastly, we will join this blackout data with census tracks to see the socioeconomic impact of the loss of power.

## Repository Contents
The file structure is formatted as a directory tree and may be seen below:

```         
├── .gitignore
│ ├── data
│   ├── ACS_2019_5YR_TRACT_48_TEXAS
│   ├── gis_osm_buildings_a_free
│   ├── gis_osm_roads_free
│   ├── VNP46A1
├── .Rhistory
├── 2021_Texas_Vortex_Blackout_Mapping.qmd
├── HW3.qmd
├── Mapping-Texas-Climate-Related-Outages.rproj
├── README.md
```

within this repository you will find the main analysis file "2021_Texas_Vortex_Blackout_Mapping.qmd" which contains all code for the analysis and description of the steps. The data folder, which due to the large files within has been added to the .gitignore, contains the relevant GIS shapefiles, the Raster data, and the census tract information. Finally, the ReadMe markdown file. 


## References and Citations
“Home - LAADS DAAC.” NASA, NASA, ladsweb.modaps.eosdis.nasa.gov/. Accessed 11 Nov. 2025. 

Planet OSM, planet.openstreetmap.org/. Accessed 11 Nov. 2025. 

“Download Openstreetmap for OpenStreetMap Data Extracts.” Geofabrik Download Server, download.geofabrik.de/. Accessed 11 Nov. 2025. 

Bureau, US Census. “American Community Survey (ACS).” Census.Gov, 29 Sept. 2025, www.census.gov/programs-surveys/acs/. 

## Data Access

All access for this analysis is readily available at the following links. For the VIIRS raster, this link can be used to download the relevant data https://ladsweb.modaps.eosdis.nasa.gov/

The Open Street Map data was sourced by a second party, Geofabrik, and this link may be sued to donwload the building and road data https://download.geofabrik.de/

Lastly, the socioeconomic information comes from the US Census Bureau's American Community Survey (ACS) across census tracts. https://www.census.gov/programs-surveys/acs
