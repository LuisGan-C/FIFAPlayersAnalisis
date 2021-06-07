# FIFACareerModePlayersAnalysis
This is a project that scrapes sofifa.com and analyses the players info to find which players are undervalued and are a good opportunity to buy on FIFA Career Mode.
Variables we'll take into account:
Value,
Wage,
Overall skill number,
Position,
Age,
Potential

The latest data from Sofifa is scraped (scraper build in-house using BeautifulSoup) and this data is stored in a pandas Dataframe, then the distribution of the players value is analyzed based on the variables mentioned, in order to find the outliers that could be undervalued and an opportunity to buy (The analysis is done with Pandas library). 
