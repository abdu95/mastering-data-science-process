This is is the assignment project for the course [*Mastering the Process of Data Science*](https://courses.ceu.edu/courses/2020-2021/mastering-process-data-science) at CEU [Master of Science in Business Analytics](https://courses.ceu.edu/programs/ms/master-science-business-analytics) program. 

The goal of the assignment is to get some practical experience working with noisy data and to draw conclusions based on the insights.

There are 3 input files in **data** folder:

- Drinks.csv: number of alcohol servings per capita per year for 15 years of age or older (for beer, wine and spirit) across various countries
- LifeExpectancy.csv: life expectancy and other health factors across various countries
- CountriesOfTheWorld.xlsx: geographical and socio-econometric data across various countries

 

`Objective:` explore data and find relationship between life expectancy, alcohol consumption and other data available in the provided files. Draw conclusions and write a short summary (circa 1 page) of the most important factors.

`Output:`

4 Python3 notebooks with summary (text and charts)

`Steps taken:`

- Read and prepare Drinks.csv
- Calculate total liters of pure alcohol using the following information:
    - 1 ounce = 0.0295 l
    - Beer serving: 12 ounces, 5% alcohol
    - Wine serving: 5 ounces, 12% alcohol
    - Spirit serving: 1.5 ounces 40% alcohol
- Read, understand and prepare LifeExpectancy.csv (use only last available life expectancy information)
- Merge drinks and lifetime data by country
- Calculate correlation between expected lifetime and total liters of pure alcohol
- Read and prepare CountriesOfTheWorld.xlsx
- Merge countries of the world data and the previously prepared data (containing total liters of pure alcohol and expected lifetime)
- Find factors that are highly correlated to the expected lifetime
- Summarize the insights, explain the most important factor
