## E2: Load and Inspect the Deliveries Data (Easy)

The deliveries dataset is much larger than the matches dataset because it records the outcome of every single ball bowled in the IPL. 

### The Objective
Load `deliveries.csv` and validate its contents.

### Requirements:
1. **Load data:** Read `data/deliveries.csv`.
2. **Validation:** Check the primary keys. What is the maximum number of balls bowled in a single match? Has any match gone significantly over the standard 120 balls per innings?
3. **Exploration:** Identify the types of dismissals present in the `dismissal_kind` column.
4. **Visualization:** Create a **pie chart or bar plot** showing the overall distribution of the different dismissal types (bowled, caught, run out, lbw, etc.). Which type of dismissal is the most common?

### Mandatory Submission Rule:
Submit your solution via a Pull Request. In your PR description, include a screenshot of your generated visualisation, a copy of the core logic code cell, and a **Markdown** summary of your findings. Specifically mention if you found anomalies in the maximum deliveries per match and describe the leading causes of dismissal indicated by your chart.
