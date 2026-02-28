# Overview
This code supports the results presented in a research paper "**Spatial segregation amplifies inequality in urban healthcare access**." 
The first four components correspond to the results (Sections 2.1–2.4) in the Main Text, whereas the fifth component contains analyses reported in the Supplementary Information (SI). The code structure is provided below.

```
code_final.py
├── 1. Distribution patterns and within-city variation in healthcare accessibility
│   ├── Distribution across nationwide and provinces
│   ├── Correlation analysis
│   ├── CV
│   └── Fig.1
│
├── 2. Spatial clustering and segregation of healthcare accessibility
│   ├── Global Moran’s I
│   ├── Local Indicators of Spatial Association
│   ├── Spatial segregation
│   │   ├── Dissimilarity index
│   │   ├── Inter-community distances
│   ├── Distance to city centers
│   ├── Shares of HH-type and LL-type communities
│   └── Fig.2
│
├── 3. Spatial embedding inequality in healthcare accessibility
│   ├── SEI
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
└── 5. Supplementary information
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
