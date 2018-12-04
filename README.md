# BostonHousingViz

## Group Member:

- MingFu Chou (mfchou2)
- Ruonan Zhang (ruonanz2)
- Shukai Yao (shukaiy2)
- Ni Lin (nilin2)

## Data Introduction

- Dataset: City of Boston Assessing Department
- File Name: ast2018full.csv
- Data Source: Analyze Boston (City of Boston's open data hub)
- Link: https://data.boston.gov/dataset/property-assessment
- License: Open Data Commons Public Domain Dedication and License (PDDL) - 
- Data usage: PDDL is a document intended to allow you to freely share, modify, and use this work for any purpose and without any restrictions. 
- File Size: 54.1 MB

**[Official description]** Gives property, or parcel, ownership together with value information, which ensures fair assessment of Boston taxable and non-taxable property of all types and classifications.

This dataset contains detailed information of real estates in Boston area. There are 172841 rows, each row of the dataset represents an unique building. There are 75 columns, each column provides descritive information for buildings. 
There are **classification features** such as type of land used `LU` or type of structural `STRUCTURE_CLASS`, those features are returned as categorical variable; **descriptive features** such as total number of rooms `R_TOTAL_RMS` or total number of bath `R_FULL_BTH`, those features are returned as numerical variable; **condition descriptions** such as overall condition `R_OVRALL_CND` or interior finish `R_INT_FIN`, returned as categorical variable; **assessment value** such as total assessed value for property `AV_TOTAL` or total assessed land value `AV_LAND`, those features are returned as numerical variables.

We are only using the residential properties of Boston in this dataset.
