# Soccer Database Analysis
## by Nonso Udechukwu


## Introduction to the Soccer Dataset

The <a href="https://www.google.com/url?q=https://d17h27t6h515a5.cloudfront.net/topher/2017/November/5a0a4cad_database/database.sqlite&sa=D&source=editors&ust=1668684100257258&usg=AOvVaw0U6MA0aqljycP9xMYE-Vl7">soccer database</a> contains data for over 25,000 football matches played from 2008 to 2016 by 299 European football clubs.

The database contains seven datasets, namely: 
- Country (id, name) 
- League (id, country_id, name) 
- Match (id, country_id, league_id, home_team_goal, away_team_goal, and 100 other columns) 
- Player 
- Team 
- Player Attributes 
- Team Attributes

## Libraries Used
- Pandas: For storing and manipulating structured data. Pandas functionality is built on NumPy (upgrade to version 0.25.1)
- Numpy: For multi-dimensional array, matrix data structures and, performing mathematical operations
- Matplotlib: For all visualizations (including maps and graphs)
- PandaSQL: For querying pandas DataFrame using SQL syntax

## Project Methodology
The main steps for this project are as follows:

- Data Wrangling:
  - Data Gathering
  - Data Assessment
  - Data Cleaning
- Exploratory Analysis
- Conclusions/Results

## Key Insights
Based on the data and analysis carried out, I found that:

1. The best teams in each of the top 5 leagues, from 2008 to 2015, were:

   - Based on matches won: Man Utd (EPL), Real Madrid and Barcelona (La Liga), Bayern Munich (Bundesliga), Juventus (Serie A), PSG (Ligue 1)
   - Based on goals scored: Chelsea, Real Madrid, Bayern, Juventus, and Paris Saint-Germain

2. The teams that improved their goalscoring the most in each of the top 5 leagues (across the period) were Tottenham Hotspur, Real Madrid CF, Borussia Monchengladbach, Napoli, and Paris Saint-Germain.

3. I found zero to no correlation between the team attributes and goals scored or matches won.

## Limitations
Certain teams didn't have goal data in certain seasons.
