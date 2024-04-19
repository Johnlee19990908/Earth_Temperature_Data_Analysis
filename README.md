# Earth Temperature Data Analysis: Insights into Climate Change Effects

## Project Overview
- Preprocessed and aggregated global/domestic temperature dataset from Kaggle using Python libraries such as Pandas, Numpy, and Scikit-learn.
- Utilized linear regression models to forecast 30-year temperatures.
- Developed 2 interactive and 8 visual reports using Tableau dashboards, delivering data-driven insights and actionable recommendations.

## Data Source
The data, sourced from Kaggle, spans temperature trend data from 1740 to 2013 across 195 countries and their respective states, comprising approximately 600,000 entries of monthly temperature data in degrees Celsius.

## Data Cleaning
- Refer to `project data cleaning process.ipynb` for detailed cleaning steps:
  - Removed duplicate data.
  - Checked and handled missing values by forward filling.
  - Identified and removed outliers.
- Grouped dataset by country name, state name, and year.
- Converted dates into datetime format.

## Visualizing Data using Python
- Utilized Matplotlib for global temperature trend analysis. Refer to `final project analysis.ipynb` and `final project analysis 2.ipynb`.
- Identified trends:
  - Increase of 2 degrees Celsius since pre-industrial times (1850-1900).
  - Significant temperature rise post-1995, with a steep increase in the 20th century attributed to the industrial revolution.
  
![Image 1](https://github.com/Johnlee19990908/Earth_Temperature_Data_Analysis/raw/main/git_image/1.png)

## Top US States Analysis
- Analyzed temperature differences for 50 states from 1850 to 2013 using the global land temperatures by state dataset from Berkley Earth.
- Calculated temperature differences and plotted top 10 states' temperature differences using Matplotlib.
- 
![Image 2](https://github.com/Johnlee19990908/Earth_Temperature_Data_Analysis/raw/main/git_image/2.png)

## Top 10 Countries Analysis
- Conducted temperature difference analysis for 195 countries and plotted top 5 countries with significant temperature differences.

![Image 3](https://github.com/Johnlee19990908/Earth_Temperature_Data_Analysis/raw/main/git_image/3.png)

## Forecasting using Linear Regression
- Refer to `project linear regression.ipynb` for forecasting details.
- Used linear regression to forecast temperature data up to 2050.
- Analysis predicts an average temperature of 19.93 degrees Celsius by 2030, with 2050 projected as the hottest year on record, 3 degrees warmer than 1850.
- 
![Image 4](https://github.com/Johnlee19990908/Earth_Temperature_Data_Analysis/raw/main/git_image/4.png)

## Visualizing Data in Tableau
- The visualizations demonstrate a global land temperature rise of approximately 2 degrees Celsius from 1850 to 2013, with potential higher increases when including ocean temperatures.

### Insights
![Image 5](https://github.com/Johnlee19990908/Earth_Temperature_Data_Analysis/raw/main/git_image/5.png)

- **Global Land Temperature Rise:** The visualizations indicate a notable increase of approximately 2 degrees Celsius in global land temperatures from 1850 to 2013. If ocean temperatures were included in this analysis, the overall global average temperature rise would likely be even higher.
- **Significance of Temperature Rise:** While a 2-to-3-degree rise may seem minor, its implications are profound and wide-reaching, impacting both the planet and human societies significantly.
- **Impact on Climate-Sensitive Countries:** Countries situated farther from the equator, which typically experience a wider range of temperatures throughout the year, are most affected by global warming. The narrowing of temperature ranges due to global warming is particularly evident in these regions.

![Image 6](https://github.com/Johnlee19990908/Earth_Temperature_Data_Analysis/raw/main/git_image/6.png)

- **United States Temperature Trends:** The United States has experienced substantial temperature changes attributed to global warming. Northern states, traditionally averaging below 6-7 degrees Celsius, have seen their average temperatures rise above 8 degrees Celsius. Alaska, in particular, has witnessed a significant 4-degree increase over recent decades.

![Image 7](https://github.com/Johnlee19990908/Earth_Temperature_Data_Analysis/raw/main/git_image/7.png)

- **Monthly Temperature Trends:** Analysis of global average temperatures over the last 150 years reveals intriguing patterns. Winter months, such as December, January, and February, have experienced an average 2-degree rise. The plot also demonstrates a steady increase in temperatures from January to June, followed by a decline until December. This pattern underscores the impact of global warming on seasonal temperature variations, especially in regions situated away from the equator.

