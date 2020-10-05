# International Debt with The World Bank Data

## Summary
Analyzing international debt(in USD) data collected by [The World Bank](https://datacatalog.worldbank.org/dataset/international-debt-statistics) from 1970-2019
with SQL queries and visualizing analysis with Tableau

## Questions
- What are the top common debts? For 2019?
- What is the top debt for each country?
- What country has the most debt? The least debt?
- International incidents that affected debts?
- Are there differences in low-income, lower middle income, middle income, upper middle income?




## Tableau Visualizations
<!-- [Tableau Public Workbook](https://public.tableau.com/profile/diannejardinez#!/vizhome/InternationalDebtwithTheWorldBankData/Map?publish=yes) -->


![](https://github.com/diannejardinez/SQL-World-Bank-International-Debt/blob/master/images/Tableau-Map.png)
> Countries in the international debt dataset

<!-- ![](https://github.com/diannejardinez/SQL-World-Bank-International-Debt/blob/master/images/Tableau-Map_country-debt.png) -->
<!-- > Total Debt for each country -->

## SQL Analysis
**Income Level**
> Income levels were Low income, lower middle income,  middle income, upper middle income

**Cumulative debt(1970-2019)**
- Total amount of debt for years between 1970-2019 ordered from highest to lowest. Middle income seems to be affected by debt the most. Data in this analysis only include debt owed. 

Income Level| Total Debt
------------|-----------
Middle income	| $24,380,791,876,999
Upper middle income | $16,784,801,480,679
Lower middle income | $7,595,990,396,319
Low income | $737,290,715,956


**Debt in 2019**
- "PPG, Private Creditors (AMT, Current US$)" was the top type of debt owed with middle income being affected the most in 2019 - [PPG defined Source: The World Bank](https://datacatalog.worldbank.org/ppg-private-creditors-amt-current-us-0)
- Middle Income Countries have per capita gross national income of US$1,026 to $12,475 (2011) - [Source: The World Bank](https://www.worldbank.org/en/country/mic/overview#:~:text=The%20world's%20Middle%20Income%20Countries,%244%2C046%20and%20%2412%2C535%20(2021))



<br><br>

**Countries**
> Only 122 countries in dataset out of 195 countries
- "PPG, official creditors (DIS, current US$)" was the top type of debt owed in 2019 - [PPG Defined Source: The World Bank](https://datacatalog.worldbank.org/search?query=%20ppg-official-creditors-dis-current-us-1)
- Mexico has the highest debt and Timor-Leste in Southeast Asia had the lowest debt


