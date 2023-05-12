# Learning Data Science

The following repository is just a compilation of Jupyter notebooks I used while learning about data preparation and data analysis. I included links to data sources, but I did not include the dataset files in the repository.

## Contents

### Titanic 🚢
<a href="https://numpy.org/"><img alt="numpy 1.23.5" src="https://img.shields.io/badge/numpy-1.23.5-blue.svg"/></a>
<a href="https://pandas.pydata.org/pandas-docs/version/1.5.3/"><img alt="pandas 1.5.3" src="https://img.shields.io/badge/pandas-1.5.3-blue.svg"/></a>
<a href="https://matplotlib.org/3.7.1/index.html"><img alt="matplotlib 3.7.1" src="https://img.shields.io/badge/matplotlib-3.7.1-blue.svg"/></a>
<a href="https://seaborn.pydata.org/whatsnew/v0.12.2.html"><img alt="seaborn 0.12.2" src="https://img.shields.io/badge/seaborn-0.12.2-blue.svg"/></a>
- **Data Source**:
    - https://www.kaggle.com/c/titanic/data
- **Goals**:
    - Explore the `train.csv` data set using `pandas`
    - Practise imputing missing data based on existing data
    - Identify outliers in the data to be handled differently
    - Visualize quantitative and qualitative features using libraries such as `seaborn`
    - Determine which passengers had higher survival rates
- **Observations**:
    - `Sex`: Female passengers were more likely to survive than male passengers
    - `Pclass`: 1st class passengers were more likely to survive than 3rd class passengers
    
### Toronto Fire Incidents 🚒
<a href="https://numpy.org/"><img alt="numpy 1.23.5" src="https://img.shields.io/badge/numpy-1.23.5-blue.svg"/></a>
<a href="https://pandas.pydata.org/pandas-docs/version/1.5.3/"><img alt="pandas 1.5.3" src="https://img.shields.io/badge/pandas-1.5.3-blue.svg"/></a>
<a href="https://matplotlib.org/3.7.1/index.html"><img alt="matplotlib 3.7.1" src="https://img.shields.io/badge/matplotlib-3.7.1-blue.svg"/></a>
<a href="https://anaconda.org/conda-forge/geopandas"><img alt="GeoPandas 0.12.2" src="https://img.shields.io/badge/GeoPandas-0.12.2-brightgreen.svg"/></a>
- **Data Sources**:
    - City Wards. Retrieved May 8, 2023 from https://open.toronto.ca/dataset/city-wards/
    - Fire Incidents (January 1, 2011 - December 31, 2021). Retrieved May 8, 2023 from https://open.toronto.ca/dataset/fire-incidents/
- **Goals**
    - Use `GeoPandas` to correct for inconsistent ward labels due to the change from 44 to 25 city wards
    - Plot geographic data using `matplotlib`
    - Correcting data set inconsistencies to prepare for data exploration