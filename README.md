# Climate Change Award – Natural Disasters vs Secondary Homes

 ## Context
Contributed to a data analysis project with Data for Good for Reclaim France (Climate Change Award). Built a Python-based analysis to evaluate the relationship between natural disasters and secondary home distribution, finding no significant correlation.

## Problem Statement
Determine whether municipalities with a high proportion of secondary homes are more frequently affected by natural disasters.

## Data 
* DuckDB Table « catnat_gaspar » (CatNat de 1982 à 2025)
* DuckDB Table « Res2_INSEE » 
  (municipalities with secondary homes – Years 1968, 1975, 1982, 1990, 1999, 2011, 2016, 2022)
* Geographic data : <https://public.opendatasoft.com/api/explore/v2.1/catalog/datasets/georef-france-commune/exports/geojson>

## Methodology 
- Data cleaning and preprocessing (Python, pandas)
- Exploratory Data Analysis 
- Statistical analysis 
- Data visualization

## Results
The analysis suggests no significant correlation between the occurrence of natural disasters and the distribution of secondary homes.

## Limitation
Only years available in both datasets were analyzed (1982, 1990, 1999, 2011, 2016, 2022), limiting temporal consistency.



