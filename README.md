*American Forests - Technical Exercise*
# Exploring Environmental, Demographic, and Educational Indicators Across Florida
**Author:** Nicole Pepper

**Date:** 11/21/25

This repo contains my materials for the Technical Exercise with American Forests including:
1) Code: A Python script stored as a Jupyter Notebook
2) Output: CSV & table of results (located in the /data/processed folder)
3) Documentation: describing my process (located at the bottom of the Jupyter Notebook)

### Repo Structure:

```
af-census-activity/
│
├── README.md
├── af-census-activity.ipynb
├── environment.yml
├── .gitignore
│
└── data/
    ├── raw/ # (not pushed to GitHub, included in .gitignore)
    └── processed/
        └── florida_summary.csv

```
### Dependencies & Running the Code:
The original, raw data for the project was not pushed to GitHub, raw files can be downloaded [here](https://amfor.sharepoint.com/sites/GISTech/Shared%20Documents/Forms/AllItems.aspx?id=%2Fsites%2FGISTech%2FShared%20Documents%2FGeneral%2FAdmin%2FHiring%2FFY26%5FGeospatialDataScientist%2Ftechnical%20exercise%2Fdata%5FNPepper&p=true&ga=1) and should be stored in a /raw subfolder within the /data folder.

To run the code locate the `af-census-activity.ipynb`. This project uses a conda environment defined in `environment.yml` in the primary project folder.

### Data Sources *(Provided by American Forests)*
- U.S. Census Bureau *TIGER/line Shapefiles: Census Tracts*
- U.S. Geological Survey (2021) *National Land Cover Database (NLCD) 2021*
- National Center for Education Statistics (2021-2024) *EDGE Geocoded Public Schools and Private School Universe Survey (PSS)*
