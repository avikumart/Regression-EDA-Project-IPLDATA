# Regression-EDA-Project-IPLDATA
In this project I have done detailed EDA of IPL data set using pandas, matplotlib and seaborn. following EDA, I have built regression models using statsmodels and scikit-learn's API.

-----------------------------------------------------------------
## Overview of the project:
The Indian Premier League (IPL), also officially known as TATA IPL for sponsorship reasons is a professional men's Twenty20 cricket league, contested by ten teams based out of ten Indian cities. The league was founded by the Board of Control for Cricket in India (BCCI) in 2007. It is usually held between March and May of every year and has an exclusive window in the ICC Future Tours Programme.

The IPL is the most-attended cricket league in the world and in 2014 was ranked sixth by average attendance among all sports leagues In 2010, the IPL became the first sporting event in the world to be broadcast live on YouTube.

The 2020 IPL season set a massive viewership record with 31.57 million average impressions and with an overall consumption increase of 23 per cent from the 2019 season

In this notebook, I have taken dataset of players' statistics from 2008 to 2013 to analyse and visualize data. also, we will see what factors affect the sold price of players

## Feature descriptions:
1) PLAYER NAME - Name of the players in IPL
2) AGE - Age group of each players, there are 3 groups of players, 1/2/3
3) COUNTRY - Home country of each players
4) TEAM - IPL team they belong to
5) PLAYING ROLE - Players role, bowlers/batman/all-rounder/Wicket-keeper
6) T-RUNS - Run scored in test matches
7) T=WKTS - Wickets taken in test matches
8) ODI-RUNS-S - Run scored in ODIs
9) ODI-SR-B - Strike rate in ODIs
10) ODI-WKTS - Wickets taken in ODIs
11) ODI-SR-BL - Bowling strike rate in ODIs
12) CAPTAINCY EXP - whether the player has any captaincy experience or not
13) RUNS-S - Number of runs scored by a player
14) HS - Highest score by batman in IPL
15) AVE - Average runs scored by the batsman in IPL
16) SR-B - Batting strike rate in IPL
17) SIXERS - Number of six runs scored by a player in IPL
18) RUNS-C - Number of runs conceded by a player
19) WKTS - Number of wickets taken by a player in IPL
20) AVE-BL - Bowling average in IPL
21) ECON - Economy rate of a bowler
22) SR-BL - Bowling strike rate in IPL
23) AUCTION YEAR - Year of auction
24) BASE PRICE - Base price of a player
25) SOLD PRICE - Sold price of a player

## Objective or Tasks of this project
- Exploratory data analysis to find insights on IPL player 
- Build Regression model to see which factors effect a lot in players' sold price in auction

## Approches and techniques:
1) Descroptive and Exploratory data analysis using pandas, matplotlib and seaborn libraries. used groupby, for loops to visualize the insights
2) Outliers detection using box plot method
3) Data cleaning and feature engineering using pandas groupby(), merge() and get_dummies() methods
4) Model training using statsmodels API and calculated VIF(variation inflation factor) to remvoe multicollinear features
5) Comparared models like Ridge regression, Decision tree regressor and Linear regression to find best performing model on test dataset

## Results and outcomes:

1) After model comparisons Ridge regression gave accuracy of 96% which was highest among all three models.
2) By doing this project, I learned Linear regression modelling using statsmodels and how to use VIF to tackle multicollinearity problem.
