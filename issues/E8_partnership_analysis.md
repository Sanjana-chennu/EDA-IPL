## E8: Partnership Analysis (Hard)

This is a difficult issue. It requires you to treat the `deliveries.csv` dataset not just as independent rows, but as a sequence of stateful events.

### The Objective
Identify the highest partnership for every match in the dataset.

### Requirements:
1. For every consecutive ball in a match, you need to track who the two active batsmen (`batsman` and `non_striker`) are.
2. A partnership is the sum of all runs scored (`total_runs`) while those specific two batsmen are on the pitch together. The partnership ends when a wicket falls or the innings ends.
3. Keep track of the running total until the state changes (a wicket falls or the innings concludes).
4. Find the largest partnership (in terms of runs) for each match.
5. **(New)** Find the single highest partnership in the entire dataset. Extract the total runs scored, and the names of the two batsmen involved.
6. **Visualization:** Plot a **histogram** showing the distribution of partnership lengths (in runs). 

### Mandatory Submission Rule:
Submit your solution via a Pull Request. In your PR description, include a screenshot of your generated visualisation, a copy of the core logic code cell, and a **Markdown** summary reflecting on the difficulty of this problem. What is the most common partnership score bracket? How rare are 100+ run partnerships according to your histogram?
