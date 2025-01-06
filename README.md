# Football Data Analysis Project using SAS

## Overview

This project analyzes over a century of international football matches (1902-2024) using data cleaning, transformation, and visualization techniques. The objective is to provide key insights on team performances through an interactive dashboard designed for upper management. You can find our presentation [here](https://www.canva.com/design/DAGRaCek5b4/c_Fv03uMc3prXiSjF7ZBqQ/view?utm_content=DAGRaCek5b4&utm_campaign=designshare&utm_medium=link&utm_source=editor).

## Table of Contents
1. [Project Structure](#project-structure)
2. [Dataset Information](#dataset-information)
3. [Data Cleaning](#data-cleaning)
4. [Visualizations](#visualizations)
5. [Insights](#insights)
6. [Conclusion](#conclusion)
7. [How to Run](#how-to-run)

## Project Structure

The project is divided into two main phases:
1. **Data Integration**: Cleaning and transforming the dataset for consistency and accuracy.
2. **Visualization**: Creating dashboards that provide insightful visualizations using SAS Visual Analytics.


## Dataset Information

The dataset contains international football match records from 1902 to 2024, including:
- Date of match
- Home and away teams
- Goals scored by each team
- Venue information (neutral/away/home)
- Tournament name
- Match outcomes (win, loss, or tie)

## Data Cleaning

Several transformations were applied to standardize and enrich the data:
- Convert all dates to `Date9` format.
- Translate all non-English city, tournament, and country names into English.
- Add a `Winner` column that indicates the match result: Home Team, Away Team, or Tie.
- Validate and remove rows with missing values.
- Final dataset saved as `results_table.csv` in `/data/cleaned/`.

## Visualizations

The project uses SAS Visual Analytics to create the following key dashboards:
1. **International Games – General Information**
   - Top 10 countries by number of wins (excluding ties)
   - Number of games per tournament (excluding friendly matches)
   
2. **International Games – City**
   - Top 30 cities by number of games played.
   - Filterable by tournament.

3. **International Games – Country**
   - Drop-down list of countries, showing goals scored vs. received per year.
   - Goals scored vs. received by team.

4. **International Games – Map**
   - Number of matches played in each country, with filters for different tournaments.

5. **Mystery Chart**
   - Wins, losses, and ties by team.
   - Network analysis of frequently competing teams.

## Insights

- **Top Performing Teams**: Identifies the countries with the highest number of wins across all tournaments.
- **Tournament Trends**: Highlights which tournaments have the most structurematches and which locations host the most games.
- **Team Performance by Year**: Shows the number of goals scored and received by country over time, useful for tracking trends in performance.
- **Performance in Neutral Venues**: Evaluates team performance when no home advantage is present, useful for neutral-ground tournament planning.
- **Network Analysis**: Visualizes team rivalries and frequently played matches.

## Conclusion

This project successfully cleaned and transformed over a century’s worth of football match data. The interactive dashboard provides upper management with key insights on team performance, match outcomes, and venue trends, empowering data-driven decision-making for future tournaments.

## How to Run

1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/football-data-analysis.git](https://github.com/MariamAmy/Football-Data-Analysis/)

