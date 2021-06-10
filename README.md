# FIFAPlayersAnalysis
This is a project that scrapes sofifa.com and analyses the players info to find which players are undervalued and are a good opportunity to buy if you were a football club (FIFA Career Mode).
Variables taken into account:
Value,
Wage,
Overall skill number,
Position,
Age,
Potential

The latest data from Sofifa is scraped (scraper build in-house using BeautifulSoup) and this data is stored in a pandas Dataframe and stored into a csv file.
Then the csv file is opened by another notebook the data is Wrangled, explored and analyzed.
All varaibles are normalized.

Then the optimal players (best cost-benefit opportunities) are obtain for each position by creating a final index that weights in all variables, giving different importance to each variable. The players with the lowest index are the optimal.  
