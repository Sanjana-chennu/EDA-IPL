## E6: Powerplay Economy Rates (Medium)

The first 6 overs of a match (the Powerplay) have fielding restrictions, making it extremely difficult for bowlers to maintain a low economy rate.

### The Objective
Find the top 10 most economical bowlers during the Powerplay.

### Requirements:
1. Filter the `deliveries.csv` to only include the Powerplay (overs 1 through 6).
2. Calculate the Powerplay Economy Rate for each bowler (Total Runs / Total Powerplay Overs). Remember that wides and no-balls do not count as legal deliveries for the over calculation!
3. **(New)** Now, do the exact same calculation, but filter for the **Death Overs** (overs 16 through 20).
4. Filter your final joined dataset to only include bowlers who have bowled a minimum of 20 Powerplay overs AND 20 Death overs.
5. **Visualization:** Plot a **scatter plot** for these qualifying bowlers. Put Powerplay Economy on the X-axis and Death Overs Economy on the Y-axis. Add a diagonal reference line (x=y) to see who excels where!

### Mandatory Submission Rule:
Submit your solution via a Pull Request. In your PR description, include a screenshot of your generated visualisation, a copy of the core logic code cell, and a **Markdown** summary. Do bowlers who bowl more overs in the powerplay tend to get hit for more runs, or does experience bring their economy rate down? Reference evidence from your scatter plot.
