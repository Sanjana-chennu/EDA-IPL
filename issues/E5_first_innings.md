## E5: First Innings Average Score by Team (Medium)

Let's switch to the `deliveries.csv` file. You need to group ball-by-ball actions into a team-level aggregation.

### The Objective
Calculate the average 1st innings score posted by each team across the dataset.

### Requirements:
1. **The Gotcha:** You MUST filter the data to only include `inning == 1` in `deliveries.csv`. 
2. Group the data by match and batting team to get the total runs scored in the 1st innings of that match.
3. **(New)** Join this data with `matches.csv` to identify whether the match was a regular season game or a "Playoff/Final" game.
4. Calculate the 1st innings average score distribution.
5. **Visualization:** Create a **boxplot** for each team showing the distribution of their 1st innings scores, but split the boxplots by whether it was a regular season game vs a playoff game (using a `hue` parameter in seaborn is ideal here).

### Mandatory Submission Rule:
Submit your solution via a Pull Request. In your PR description, include a screenshot of your generated visualisation, a copy of the core logic code cell, and a **Markdown** summary. Look at the boxplots—which team has the highest median score? Which team has the widest variance (indicating inconsistency)? Share your observations.
