#  Documentation of my findings

Working on the EDA and Visualization on Video Game Sales I took the following steps:

#### Importing the necessary python library modules

I started by importing the relevant python library modules like:
- `<Pandas>`: for loading and reading the Video Game Sales csv files
- `<Matplotlib>`: For Visualization
- `<Seaborn>`: for creating an appealing barplots
- `<Plotly>`: tp serve the same function as <seaborn>

#### Data Reading

I read through the files checking:
- The dataset shape
- The column information
- The missing data
- The dataset descriptions

#### Data Cleaning

I changed the data type of the Year Columns to datetime data type. Meanwhile, I did not drop or fill any missing data since they are not much. After that I copied the dataset for exploration

#### Data Exploration

The dataset was explored ahead the analysis. The following analysis were performed:

- Single Variable Analysis: Top 10 games were analysis to view which game was most bought by the people globally. On the barchart, it is discovered that the "WII SPORT" was the most acquired game with 80% of the global sale. Additionally, top 10 platforms were also plotted to detected which game's platform attratced the most sales globally. Statiscally, it was discovered that the "DS" game platform tops the chart with "800 millions" sales globally. Finally, on the single variable analysis, top 10 genres of games were plotted to discover which genre of video game is the highest in the dataset. Then, "Action" games occurs as the highest on the chart with "3000" game count in the dataset.

- Relationship Analysis: This analysis features:
1. Sales by Year where 2010 witnessed the highest sales of game of around "700" million and in ten years after, which was 2020,  the sales of games hit its lowest of "0 - 20" million.

2. Sales by Genre where "Action" was the highest game sold  with "1750" global sales record and "Strategy" game fell between "0 - 200" global sales.

3. Sales by Platform in North America was plotted to check type of game platform was acquired most in the North America. It was discovered that the "X360" was the most acquired with "600" sales record in the region while "PS2" followed with "580" sales record.

- Regional Analysis: Three regions were plotted to check where Video Game made the highest sale. It was discovered that VG sales witnessed the highest sales in the North America with "4000" game sales in the region while Europe comes second with less than "3000" sales on the bar chart.

- Publisher Analysis: Top 10 VG Publishers were plotted to check which publisher has the highest sales globally and "Nintendo" occurred to top the list with "1750" global sales.
- Correlations Analysis: This shows how strongly related the sales in different regions are to each other. The possitive correlation is plotted with warm red while the negative correlation is plotted with cold blues.