# dashboard_with_python
Dashboard using dash

The script provides a web-based dashboard for analyzing video game sales using the Dash and Plotly libraries. Here's a detailed breakdown:

## Data Exploration with Pandas:

The data is loaded from a CSV file named "vgsales.csv" containing video game sales data.
The script contains commented-out code snippets for initial data exploration, such as viewing the first five rows, checking unique genres, and examining the years of game releases.

## Data Visualization with Plotly:

The code includes sections (currently commented-out) that generate various visualizations, such as pie charts and bar plots, to showcase sales across different genres and in specific regions like Japan.

## Interactive Graphs with Dash:

The main section of the script utilizes the Dash library to create an interactive web dashboard.
The dashboard contains a dropdown menu for users to select a specific game genre.
Based on the user's selection, a bar plot is generated, showcasing the sales in Japan for games of that genre over the years.
The interaction is managed using Dash's callback mechanism.
