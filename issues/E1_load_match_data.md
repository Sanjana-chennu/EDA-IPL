## E1: Load and Inspect the Match Data (Easy)

Welcome to the first issue! Before any advanced analysis can begin, a Data Scientist must understand the structure, scale, and messiness of the data they are working with.

### The Objective
Load the `matches.csv` file into a Pandas DataFrame and perform an initial exploratory inspection. You need to answer basic questions about the structure of the tournament history.

### Requirements:
1. **Load data:** Read `data/matches.csv`.
2. **Metadata:** Output the `shape` of the dataframe and list all column names.
3. **Basic Summaries:** How many unique seasons are in the dataset? 
4. **Missing Values:** Identify which columns contain missing values (`NaN`).
5. **Visualization:** Plot a **bar chart** showing the number of matches played per season to ensure the data loaded correctly and isn't skewed.

### Mandatory Submission Rule:
Submit your solution via a Pull Request. In your PR description, include a screenshot of your generated visualisation, a copy of the core logic code cell, and a **Markdown** summary describing what you discovered (e.g., verifying how many seasons of data exist, which years had the most matches) and specifically referencing what your bar chart shows.
