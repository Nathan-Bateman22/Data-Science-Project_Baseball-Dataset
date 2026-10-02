# MLB Offensive Trends & Winning Analysis

## Overview

This project analyzes historical MLB data to investigate trends in offensive performance, player profiles, and the statistics most closely associated with winning.

The goal was to use data science and statistical analysis to answer questions that could be relevant to professional baseball organizations, including scouting, player evaluation, and game strategy.

## Key Analyses

* **Player Power by Country:** Compared slugging percentage across players' countries of birth to identify differences in offensive power.
* **Batting Average vs. Slugging:** Examined the relationship between batting average and slugging percentage and identified players with contrasting contact and power profiles.
* **Changes in MLB Offense:** Analyzed home runs, walks, strikeouts, and stolen bases per team game across MLB history to identify long-term changes in offensive strategy.
* **Statistics Associated with Winning:** Used Pearson correlation to examine relationships between team statistics and winning percentage.

## Key Findings

* Slugging percentage varied across countries of birth, suggesting potential differences worth investigating further in player evaluation.
* Batting average and slugging percentage showed a strong positive relationship, while individual players demonstrated distinct contact and power profiles.
* MLB offensive strategy has changed substantially over time, including major increases in home runs and strikeouts.
* **Run differential per game had a .94 correlation with winning percentage across 2,482 team-seasons**, making it the strongest relationship examined in the project.

## Technical Approach

* Grouped player batting data by `playerID`
* Calculated batting average and slugging percentage
* Filtered players to at least 100 at-bats
* Used boxplots, scatterplots, line charts, and a correlation matrix for visualization
* Converted counting statistics to **per-game rates** to account for differences in season length
* Used Pearson correlation to compare team statistics with winning percentage
* Used R for data analysis and visualization

## Data

The dataset contains historical MLB player, demographic, revenue, award, and team statistics. The analysis focused primarily on individual batting performance, player demographics, and team performance.

## Why This Project Matters

This project demonstrates how historical sports data can be transformed into interpretable insights for questions involving **player evaluation, offensive strategy, and team performance**. It also highlights my experience with statistical analysis, data visualization, and working with large sports datasets.

## Future Work

Future analysis could incorporate additional factors such as league era, ballpark dimensions, and other qualifying statistics to provide more context around differences in player and team performance.

---

**Tools:** R • Data Analysis • Statistics • Data Visualization • MLB Data

---

Project made by Nathan Bateman and Zach Maughan
