# Chicago_Crime_Data
This repository contains an exploratory data analysis of crime, socio-economic, and school performance data in Chicago.

# Project Overview
The goal of this project is to explore trends in crime in Chicago, and how these trends relate to socio-economic conditions and school performance in different areas of the city.

# Data
The analysis is based on three datasets:

- Chicago Crime Data: This dataset contains information about reported incidents of crime in Chicago from 2001 to present. The data is extracted from the Chicago Police Department's CLEAR (Citizen Law Enforcement Analysis and Reporting) system.

- Chicago Census Data: This dataset provides a selection of socioeconomic indicators from the US Census Bureau's American Community Survey. The data is indexed by community area and includes variables such as percent of housing crowded, percent households below poverty, percent aged 16+ unemployed, percent aged 25+ without high school diploma, per capita income, hardship index.

- Chicago Public Schools Data: This dataset provides information about performance metrics for each public school in Chicago.

# Methodology
The analysis consists of several steps:

- Data Loading: Load the crime, socio-economic, and school performance data.

- Data Merging: Merge the three datasets based on the common COMMUNITY_AREA_NUMBER attribute.

- Exploratory Data Analysis: Explore the distributions of various attributes, relationships between variables, and trends over time.

- Hypothesis Testing: Conduct a Chi-square test of independence to test whether the rate of arrests is independent of crime type.

# Key Findings
Here are some of the key findings from the exploratory data analysis and hypothesis testing:

- The most common types of crimes in Chicago are theft and battery.
- The rate of arrests varies significantly by crime type, indicating that certain types of crimes are more likely to result in an arrest than others.
- There are significant differences in the number of crimes across different community areas in Chicago, suggesting that socio-economic conditions and school performance may play a role in crime rates.

# Tools Used
- Python: The analysis is conducted using Python, which provides a wide range of libraries for data manipulation and analysis.
- pandas: Used for data manipulation and analysis.
- matplotlib and seaborn: Used for data visualization.
- scipy and statsmodels: Used for statistical analysis.
