## E7: Team Extras Conceded (Medium)

Extras (wides, no-balls, leg-byes, byes) are free runs gifted to the batting team. 

### The Objective
Calculate the total and average extras conceded by each bowling team.

### Requirements:
1. Identify the extras columns in `deliveries.csv`. 
2. **The Gotcha:** You must fill `NaN` values with `0` before doing any column-based aggregations or summations! 
3. **(New)** Add a dimensional layer: We want to see the difference between extras conceded in the 1st innings vs the 2nd innings (Scoreboard Match Pressure).
4. Group the extras by `bowling_team` and `inning` (filtering out super overs, i.e., inning 3/4 if they exist).
5. **Visualization:** Create a **nested bar chart** (or side-by-side stacked bar charts) showing the breakdown of extra types (wides vs no-balls vs leg-byes) conceded by each team, explicitly contrasting their 1st innings discipline versus their 2nd innings discipline.

### Mandatory Submission Rule:
Submit your solution via a Pull Request. In your PR description, include a screenshot of your generated visualisation, a copy of the core logic code cell, and a **Markdown** summary. Your summary should look at your stacked bar chart and identify which team is the most disciplined (fewest extras on average) and which team's extras are primarily wide-based versus leg-bye based.
