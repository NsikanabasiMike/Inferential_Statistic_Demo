## Table of Contents
- [Installation](#install)
- [Problem statement](#statement)
- [About this File](#describe)
- [Analysis and Results](#results)
- [Licensing, Authors, and Acknowledgements](#acknowledge)

<a id='install'></a>
### Installation
1. Python 3.6 and latest from [here](https://www.python.org/downloads/)
2. Anaconda distribution of Python from [here](https://www.anaconda.com/blog/anaconda-distribution-2022-10#).
3. Pingouin Library. You can pip install it by running this line on your command prompt >> _pip install pingouin_

<a id='statement'></a>
> ### About Project
This project is self-motivated. The aim is to horn my skill in inferential statistics for data analysis.

### Problem Statement

Maternal mortality and Infant mortality are the groups of interest in this project. I want to uncover the top 5 countries by mean value and further investigate whether there is any population mean difference between them. 

#### _Concepts Used_:

Bi-Variate Analysis 2-sample t-test: testing for difference across populations ANOVA and pairwise tests. 

<a id='describe'></a>
### About this file
There are 7 variables and 6756 observations. The variables include:

1. `Region`: Region where a country or Area belongs
2. `Country/Area`: Country or Area	
3. `Year`: Year (2010, 2015, 2020, 2022)
4. `Series`: Categorical variable (Population annual rate of increase (percent),
       Total fertility rate (children per women),
       Infant mortality for both sexes (per 1,000 live births),
       Maternal mortality ratio (deaths per 100,000 population),
       Life expectancy at birth for both sexes (years),
       Life expectancy at birth for males (years),
       Life expectancy at birth for females (years)
       )	
5. `Value`: Numerical values for variables in Series	
6. `Footnotes`: Additional information	
7. `Source`: Source of information

<a id='results'></a>
### Analysis and Results
I analysed the data and made inferences based on the results obtained from f_oneway ANOVA and Pingouin's pairwise_tests. The code and the results are in this jupyter notebook _Inferential_Statistics_Demo_.

<a id='acknowledge'></a>
### Licensing, Authors, Acknowledgements
The data used for this analysis is [here](https://data.un.org/_Docs/SYB/CSV/SYB66_246_202310_Population%20Growth,%20Fertility%20and%20Mortality%20Indicators.csv)