### Introduction
- This project analyzes data on GDP and life expectancy from the World Health Organization and the World Bank to identify the relationship between GDP and life expectancy of six countries.

### Scope

#### Goal
- Find the relationship between a country's life expectancy and its total GDP.

#### Actions
- EDA using Python libraries such as Pandas and Numpy
- Use hypothesis tests and data visulization to find association.

**If there is an association between total GDP and life expectancy:**
1. What further analysis can be performed to analyze the relationship.
2. What other possible factors can affect the country's life expectancy.
3. What data can be collected to further support the finding.
4. What other features can be considered in the analysis.
**If there is no association:**
1. What factors can affect on life expectancy.
2. If there is any type I or type II errors during the test.

#### Data
- The data is stored in a csv file and contains four columns: 'Country', 'Year', 'Life expectancy at birth (years)', 'GDP'
- There are six countries: 'Chile', 'China', 'Germany', 'Mexico', 'United States of America', 'Zimbabwe'
- There is no missing data in the dataset.
- There are 96 entries in total.

#### Analysis Performed:
- Used scatter plots to find any association between total GDP and life expectancy in each country over the 15 years.
- Applied correlation method to prove the finding from the scatter plots.
- Used line plots to find any trend for total GDP and life expectancy in each country during the 15 years.

### Conclusions:
- There is a strong linear association between total GDP and life expectancy for all six countries.
- Both total GDP and life expectancy show positive trend from 2000 to 2015 in all six countries.
- Overall, even though there is a strong relationship between total GDP and life expectancy, total GDP is not the only factor that affects life expectancy.

#### Further Actions for More Accurate Result:
More actions can be done for a more accurate result:
- Data from more countries
- Longer time frame in the data
- Total GDP divided into smaller categories (income, production, expenditure) and see if one category contributes more towards longer life expectancy.
- GDP per capita
