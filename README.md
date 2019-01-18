This is a project to showcase my SQL/Excel/Tableau skills using Olympic Historical Dataset. 

I would like to look at countries' olympic successes from GDP perspective and to have a closer look at USA Female Gymnastics Olympic Team members if there is a significant change over time in terms of their biometric measurements.

In this project, I used SQL to extract data and excel to clean data. Tableau was used for visualizations and analyzing the data.

## Olympic Data:  
These files are historical Olympic Data (1896-2016).

This dataset is publicly available at [www.kaggle.com](https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results).

The data contains 120 years of Olympic history: athletes,results and basic bio data (age, height and weight) on athletes and medal results from Athens 1896 to Rio 2016. This "Olympic" data consists of 2 parts: Summer Olympics and Winter Olympics.

## Historical GDP Data: 
GDP per capita is a measure of a country's economic output that accounts for its number of people. It divides the country's gross domestic product by its total population. That makes it the best measurement of a country's standard of living. GDP Per Capita is measured in US Dollars and the higher is dollar amount, shows a higher quality of life.For more information, [link](https://www.google.com/search?ei=sU88XMuTOtrC0PEP__WG0AU&q=gdp+per+capita+definition&oq=gdp+per+capita+&gs_l=psy-ab.1.0.0i67l7j0j0i67l2.13402.13402..15110...0.0..0.82.82.1......0....1..gws-wiz.......0i71.NSd4EQsxHEg).

For GDP_Per_Capita, I used the United Nations publicly available data sets ([link](https://www.un.org/en/development/desa/population/publications/database/index.shtml)).

# Calculations using Excel:
# Olympic Data: 
In order to calculate the Sum of Medal Counts, I created a "Dummy Variable", named as "Medal" in Excel using "IF/Condition"function.
# GDP Data:
I would like to use GDP Per Capita amounts together with its ranking amoung other countries. Therefore, I used the "Rank" function in Excel to calculate the Rankings.


## SQL Import and Data Files:

1. [Loading in Data](https://github.com/culhaci/Project/blob/master/Loading%20Data)

## SQL Queries: 

2. [SUM, AVG,MIN SUBQUERY, ORDER BY and GROUP BY](https://github.com/culhaci/Project/blob/master/SUM%2C%20AVG%2CMIN%2C%20SUBQUERY%2C%20ORDER%20BY%20and%20GROUP%20BY)
3. [ALTER TABLE](https://github.com/culhaci/Project/blob/master/ALTER%20TABLE)
4. [CASE](https://github.com/culhaci/Project/blob/master/Loading%20Data)
5. [WHERE and HAVING](https://github.com/culhaci/Project/blob/master/WHERE%20AND%20HAVING)
6. [JOIN](https://github.com/culhaci/Project/blob/master/JOIN)
7. [UNION](https://github.com/culhaci/Project/blob/master/UNION)


## Excel Data: [Excel Data]

* [LOOKUP] (googledrive)
* [Pivot table] 


## Visualizations: 

* [A](https://public.tableau.com/profile/aydin.culhaci#!/vizhome/Olympics_214/Dash5-USAFemaleGymnasticTeam?publish=yes)

## Notes:

A. [I had 2 assumptions for the calculations:]
     [1. Data has correct and complete information]
     [2. I did not make any calculation mistakes]
B. [Some Recommendations for the future study:]
     [1. We might add "Pupulation" metrics in our calculations]
     [2. We might include "Government Budget" and detailed "Spending" on Olympic Division]
    [ 3. We might look into the "Spending of Olympic Division" on each "Event"]
     
