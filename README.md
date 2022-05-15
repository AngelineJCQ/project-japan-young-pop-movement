# Japan Young Population Movement Analysis from 2016 to 2021

## Project Description

In this project, we want to focus on Japan's youth (age 15-29) movement. Primarily, we are interested in the city/county difference, gender difference and age group difference.

Using the regression model, we find that industry category and university number cannot fully explain the city's attractiveness to young people.

After normalizing the raw number by the scale of the city (in this case, we use 2020 population data), we decided to focus on Kobe: among all the cities having more than 1 million pop, Kobe is the only one losing young population in six years. While it has a relatively high percentage of female university students, it keeps losing young people in the age group of 25-29. Although the government has conducted several policies, for instance, collaborating with 500 start-ups since 2016, no strong effect can be seen from the demographic data. Some experts suspect it might be due to the economic and cultural reasons: while many female students from smaller cities will be attracted to many female colleges in Kobe, they are not intended to stay here, as there are not many job opportunities and childcare services; also, as most families in Japan still hold conservative views, women are more likely to relocate to their husbands' working place.


## Dataset

- [2016-2021 Annual Report on Internal Migration in Japan](https://www.e-stat.go.jp/stat-search/database?page=1&layout=datalist&toukei=00200523&tstat=000000070001&cycle=7&tclass1=000001148746&tclass2val=0)
- [2017 School Basic Survey](https://www.mext.go.jp/b_menu/toukei/chousa01/kihon/1267995.htm)
- [2017 Employment Status Survey](https://www.e-stat.go.jp/dbview?sid=0003222943)

## Repo Guide
[Pre-pitch Repo](https://github.com/code4journalism/regressions-pre-pitch-naokatoh)
[Exploratory Notebook](https://github.com/AngelineJCQ/project-japan-young-pop-movement/blob/main/Clean-and-Exploratory-Data-Analysis.ipynb)
[Final Data Diary Notebook](https://github.com/AngelineJCQ/project-japan-young-pop-movement/blob/main/Data-Diary-for-Final-Project.ipynb)



The introduction of dataframes in the last two notebooks:

- `city_data_2017`: this contains 2017 young pop movement data for 21 major cities in Japan, as well as the univerisity student data, city population data.
- `six_year_data`: this contains six-year young pop movement data for all the counties and cities in Japan (2016-2021), as well as the total/male/female pop data in 2020.
- `city_pct`: this is the 2017 city data devided by the 2017 population, so this is a percentage dataframe
- `df_pct`: this is the six-year raw data devided by the 2020 population, so this is a percentage dataframe

