# EDS 220: True and False Color Imaging - Eaton and Palisades Fires 

### Purpose:
Practice utilizing false color imagery to visualize the Eaton and Palisades fire scars from February 2025. 

### Repo Structure: 
```
eds220-hwk4
├── README.md
├── data
│   ├── Eaton_Perimeter_20250121
│   ├── Palisades_Perimieter_20250121
│   └── landsat8-2025-02-23-palisades-eaton.nc
└── hwk4-task2-false-color.ipynb
```
### Authors: 
Mark Oregel

### Highlights:
- Utlizing rioaxarray to load in data and wrangle raster data (fire perimeter data)
- Matching and writing CRS of relevant data
- Maniuplation of data for the purpose of visualization 
- Creating true and false color images with comparison 
- Exploring how to plot and combine raster data

### About the data: Datasets description: 
The first dataset that we utlize in this notebook comes from the Landsat 8 satellite, courtesy of the Microsoft Planetary Computer data catalog. This dataset consists of color bands (red, green, blue, shortwave infrared, and near-infrared). 

The second dataset consists of perimeter data of the Eaton and Palisades fires from February of 2025. This dataset was retrieved from the official ArcGIS page of Los Angeles County. This data was access November 21, 2026. 

### References:

Microsoft planetary computer. (2024). Microsoft.Com.[Dataset] https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2. [Accessed: Nov 20, 2026]

Los Angeles Couny. (2025). Palisades and Eaton dissolved fire perimeters (2025). Arcgis.Com.[Dataset] https://egis-lacounty.hub.arcgis.com/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about. [Accessed: Nov 21, 2026]

