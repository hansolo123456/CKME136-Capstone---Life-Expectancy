# CKME136-Capstone--Life Expectancy
Global Life expectancy has changed dramatically over the last 150 years or so. Yet some countries have changed more than others.  Using the World Development Indicators database from the World bank, I intend to evaluate the factors that affect life expectancy, by country and possibly by geographic region to determine if Life expectancy can be predicted based on the factors most closely correlated.  My initial hypothesis is that the various forms of health spending will be one of the most significant factors in determining life expectancy.  

The eventual use of this analysis is a potential  evaluation of government and health care spending, and determining policy for best allocation of resources to have the greatest impact on life expectancy

 
The full dataset, called, The World Development Indicators, was downloaded from Kaggle (https://www.kaggle.com/worldbank/world-development-indicators) and was originally sourced from The World Bank.  It contains thousands of annual indicators of economic development, social well-being, democracy, freedom, social evaluations, gender equality, age factors, health and quality of life among others, from 247 countries from 1960 – 2015.

The original raw data (available here) consists of 333,560 records(rows) and 60 attributes (Columns).  The records are broken out by by country, then sub-divided by Indicator. It is worth noting that while most countries have data from 1960 to 2015, not all the indicators have full data.  This will pose a challenge for correlation matrix analysis.

The Kaggle curated version of the data at the link above is a slightly transformed version of the data set into a “long form” with 5,656,458 records (rows) only 6 attributes (columns), to facilitate analytics.  None of the data has been removed.  This is the primary data set I will work with.


