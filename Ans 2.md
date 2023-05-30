## 2. What are the different steps in grouping fields and combining tables in tableau ? Explain with examples. (With the help of an example create one in tableau)

Dataset Used: [World Cup](Datasets/world_cup_results.xlsx)

### Grouping the fields:
- Right-click on the selected fields and choose "Group."
- A new group will be created with the selected field values.

In this example we took teams that how many times these teams are qualified to the world cup

<img src="images/Countries qualified to the World Cup(original).png">

in here we grouped the coutries `Argentina` and `Brazil` together.

<img src="images/Countries qualified to the World Cup(Grouping).png">

### Join the tables:
- In the Data pane, locate the common field in one table.
- Click on the field and drag it to the common field in the other table.
- Tableau will automatically detect the join type based on the data.
- If needed, you can edit the join type by right-clicking on the join line in the Data pane and selecting the desired join type (e.g., Inner Join, Left Join).

<img src="images/Combining Tables.png">
