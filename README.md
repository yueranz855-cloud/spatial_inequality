# Overview
This code supports the results presented in the research paper "**Spatial segregation amplifies inequality in urban healthcare access**." The first four sections correspond to the main results (Sections 2.1–2.4) presented in the Main Text, while the fifth section contains analyses reported in the Supplementary Information (SI). The code structure is provided below.

```
code_final.ipynb
├── 1. Distribution patterns and within-city variation in healthcare accessibility
│   ├── Distribution across nationwide and provinces
│   ├── Correlation analysis
│   ├── Coefficient of variation (CV)
│   └── Fig.1
│
├── 2. Spatial clustering and segregation of healthcare accessibility
│   ├── Global Moran’s I
│   ├── Local Indicators of Spatial Association (LISA)
│   ├── Spatial segregation
│   │   ├── Dissimilarity index
│   │   ├── Inter-community distances
│   ├── Distance to city centers
│   ├── Shares of HH-type and LL-type communities
│   └── Fig.2
│
├── 3. Spatial embedding inequality in healthcare accessibility
│   ├── Spatial Embedding Inequality Index (SEI)
│   ├── Distribution of SEI
│   ├── Regional comparisons
│   ├── SEI and CV
│   ├── Regression analysis
│   └── Fig.3
│
├── 4. City typologies of healthcare accessibility and associated spatial embedding inequality
│   ├── Features
│   ├── Hierarchical clustering
│   ├── Kruskal–Wallis test
│   └── Fig.4
│
└── 5. Supplementary Information
    ├── S1
    ├── S4
    ├── S5
    ├── S7
    ├── S8
    ├── S9
    ├── S12
    ├── S13
    ├── S15
    └── S16

```

Note: To run the notebook successfully, place the input data file (`df.csv`) in the same directory as `code_final.ipynb`, or modify the file paths specified in the notebook accordingly.

### Additional data requirement

The code requires a China administrative boundary shapefile (`china.shp`) for spatial analysis and map visualization. 

Administrative boundary data for China were primarily obtained from the Institute of Geographic Sciences and Natural Resources Research, Chinese Academy of Sciences, and supplemented with the South China Sea nine-dash line from the Alibaba Cloud Data Visualization Platform for map visualization.

Users should obtain the boundary data from the original data providers and place the shapefile in the same directory as the code before running the scripts.

# System requirements
## Hardware requirements
This code requires only a standard computer with enough RAM to support the in-memory operations.

## Software requirements
### OS requirements
This code has been tested on *macOS*.

### Python version
This code was developed and tested using Python 3.12.3.

### Python dependencies
Required packages include:

- pandas
- geopandas
- numpy
- matplotlib
- seaborn
- statsmodels
- scipy
- shapely
- networkx
- libpysal
- esda
- pyproj
- scikit-learn
- scikit-posthocs

# Installation guide
This code is written using *Jupyter Notebook* and has no additional installation requirements.
