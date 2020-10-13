# Metis-Onl20-Ds4-MLB-Salary-Prediction

The following repository contains code and data used to predict Major League Baseball Salaries for offensive players during the year 2019.

Methods:

For this project I utilized Linear Regression on various features in order to predict a specific player's salary (target variable).

We used BeautifulSoup to scrape:
1. Offensive player stats (such as AB, RBI, etc....) from https://www.baseball-reference.com
2. Offensive player salaries from https://www.spotrac.com/mlb/rankings/salary


Models were built using Linear Regression packages in Scikit-Learn, while visuals were created using Matplotlib. 

A presentation of the findings is included in this repository.

The major finding in this analysis was the the highest correlated feature to Salary during the 2019 season was GIDP (grounds into double play). Historically this is not the case as RBI and are the highest correlated features with salary.

Next Steps:
1. Perform the same analysis on 2017 and 2018 data to see if we see the same pattern (GIDP being the highest correlated feature)
2. Use Sean Lahman's website (http://www.seanlahman.com/baseball-archive/statistics) on historic data to understand the differences on how manager's managed the game during 1995-2010 compared to more recent years.
3. Use Regression methods, in particular polynomial regression, on the most correlated features for more recent years. 
4. Include cateogorical features (such as league and team) within the model.
5. Try to understand if arbitration affects a player's salary.
6. Extend this methodology to understand pitcher salaries.
