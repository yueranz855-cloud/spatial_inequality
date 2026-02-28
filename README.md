# Overview
This code supports the results presented in a research paper "**Spatial segregation amplifies inequality in urban healthcare access**." The first part relates primarily to the results in the Main Text (including sections 2.1-2.6), and the second part is for the Supplementary Information (SI) sections. The detailed correspondence is shown in the table below.

## Structure of `main_analysis.py`

```
main_analysis.py
├── 1. Part 1
│   ├── Distribution across nationwide and provinces
│   ├── Correlation analysis
│   ├── CV
│   └── Fig.1
│
├── 2. Part 2
│   ├── Global Moran’s I
│   ├── Local Indicators of Spatial Association
│   ├── Spatial segregation
│   │   ├── Dissimilarity index
│   │   ├── Inter-community distances
│   │
│   ├── Distance to city centers
│   ├── Shares of HH-type and LL-type communities
│   └── Fig.2
│
├── 3. Spatial autocorrelation
│   ├── Global Moran's I
│   └── LISA analysis
│
├── 4. City clustering
│   ├── Feature construction
│   └── Hierarchical clustering
│
└── 5. Regression analysis
    ├── Multivariable models
    └── Province fixed effects
```

Note that for the code to work properly, please put the data (df.csv) in the same file directory as the codes, or modify the file paths in the codes.



# System requirements
## Hardware requirements
This code requires only a standard computer with enough RAM to support the in-memory operations.

## Software requirements
### OS requirements
This code has been tested on *macOS*.

### Python dependencies
This code mainly depends on the Python scientific and visualization packages：
```
pandas
geopandas
numpy
matplotlib
seaborn
statsmodels
os
networkx
itertools
scipy
shapely
libpysal
esda
pyproj
scikit-learn
scikit-posthocs
```


# Installation guide
This code is written using *Jupyter Notebook* and has no additional installation requirements.
