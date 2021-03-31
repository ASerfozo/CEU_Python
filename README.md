# Term project of Fanni Kiss and Attila Serfõzõ
Coding 3: Python - Central European University (CEU)

Current project aims to explore the correlation among corruption and other indicators in the countries of the world. We used the Corruption Perceptions Index (CPI) to measure the corruption in countries. Transparency International makes a ranking based on the CPI in every year. The data is available here: https://www.transparency.org/en/cpi/2020/index/aus
To enrich our data set, we used the Human Development Report Office Statistical Data API from here: http://ec2-54-174-131-205.compute-1.amazonaws.com/API/Information.php

## Task 1: HDI & CPI correlation
Exploring the association between Human Development Index (HDI) and Corruption Perception Index (CPI). 
Hypothesis: A higher HDI value correlates to lower levels of corruption in a region.
Year: 2019

## Task 2: Success story
Are there countries, which managed to reduce corruption in the period of 2016-2019? If so, what indicators changed in the given country/countries in the period of 2016-2019? 
Examined indicators: 
- Employment to population ratio (% ages 15 and older)
- GDP per capita
- Women in parliament (%)

Note: we tried to examine further indicators measuring economy, employment, equality in the society, but other relevant indicators were not available in this period. 

## Repository
[Getting the data and enrich it with API](code/Term_Project_get_data.ipynb)
[Exported data in the code folder](https://github.com/ASerfozo/CEU_Python/tree/main/code)
[Final analysis](code/Term_Project_analysis.ipynb)
