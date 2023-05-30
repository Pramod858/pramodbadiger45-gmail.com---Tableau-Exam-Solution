## 1. Explain in detail the area graphs and line graphs in tableau and how to create them with examples. (With the help of an example create one in tableau)

Dataset Used: [World Cup](Datasets/world_cup_results.xlsx)

### Area Graphs:
- Area graphs are used to display quantitative data over time, typically representing cumulative totals or proportions.
- The graph consists of filled areas bounded by lines, with the area between the lines filled with color.
- Area graphs are useful for comparing the overall values and relative proportions of different categories over time.

Create the area graph:
- Drag the time-related field (Year) to the Columns shelf.
- Drag the quantitative field (Away Goal, Home Goals) to the Rows shelf.
- Tableau will automatically aggregate the values based on the time period.
- To create the area graph, click on the "Show Me" panel on the right side of the interface and select the "Area" chart type.

<b>Area Graph</b>
<img src="images/Home and Away Goals.png">

## Line Graphs:
- Line graphs are used to show the relationship between two continuous variables, typically representing trends, changes, or comparisons over time.
- The graph consists of data points connected by straight lines.
- Line graphs are effective for illustrating the magnitude and direction of change in data.

Create the line graph:
- Drag the time-related field (Year) to the Columns shelf.
- Drag the quantitative field (Goals Scored, Matches Played) to the Rows shelf.
- Tableau will automatically aggregate the values based on the time period.
- To create the line graph, click on the "Show Me" panel on the right side of the interface and select the "Line" chart type.

<b>Line Graph</b>
<img src="images/Matches Played v_s Goals Scored.png">

