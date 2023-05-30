## 6. Explain in detail the heat maps and scatter plot and how to create them with example (With the help of an example create one in tableau)

### Create Heat Map:

- Drag the desired dimensions and measures to the Rows and Columns shelves.
- Select two measures to plot on the x-axis(Avg(Profit)) and y-axis(Avg(Sales))
- Add `State` in detail.
- In marks card change `Automatic` to `Density'
- To create the heat map effect, drag a measure to the Color shelf. This measure will determine the color gradient for each cell.
- Tableau will automatically generate a heat map based on the selected dimensions, measures, and color gradient.

<img src="images/Profit vs Sales(Heat Map).png">

## Scatter Plot:

- Drag the desired dimensions and measures to the Columns and Rows shelves.
- Select two numerical measures to plot on the x-axis(Sales) and y-axis(Quantity).
- Add `Category` and `Region` in detail.
- In marks card change `Automatic` to `Circle`
- Tableau will automatically generate a scatter plot based on the selected measures.

<img src="images/Sales vs Quantity (Scatter Plot).png">
