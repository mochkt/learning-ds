# Learning Data Science

The following repository is just a compilation of Jupyter notebooks I used while learning about data preparation and data analysis. I included links to data sources, but I did not include the dataset files in the repository.

## Contents

### Titanic 🚢
`numpy`, `pandas`, `matplotlib`, `seaborn`
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
    - Spotted outlier 3rd class passengers, who were recorded with the same `Ticket` and were listed with higher `Fare` (50+):
        - Sage family:
            - Listed with 8 `SibSp`
            - Did not survive
        - Male passengers of Asian descent:
            - Many of them survived