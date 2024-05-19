# Border Crossing Data Analysis

### Introduction:
The Bureau of Transportation Statistics (BTS) Border Crossing Data collects data on inbound crossings at the U.S.-Canada and the U.S.-Mexico border at the port level every month. Data is available for trucks, trains, containers, buses, personal vehicles, passengers, and pedestrians.

Border crossing data are collected at ports of entry by U.S. Customs and Border Protection (CBP). The data reflects the number of vehicles, containers, passengers or pedestrians entering the United States.

### Task:
Which ports experience the most crossings by date and type?

*High Traffic Border Crossings*:
- Identified parts of the USA with high traffic border crossings.
- Created visualizations to depict the geographic distribution of traffic.

[Tableau Public Link](https://public.tableau.com/shared/6CGRKP6XN?:display_count=n&:origin=viz_share_link)

#### Custom Metric for Port Ranking:
- Upon EDA it is found that both US-Canada and US-Mexico has different traffic for different
- Determined the significance of each crossing type based on the total number of crossings
- Weights were assigned to each measure reflecting their importance
- For each port, calculated the weighted sum by multiplying the value of each measure by its corresponding weight.
- Aggregated these weighted values to get a total weighted sum for each port.
- Grouped the ports by border and calculated the total weighted sum for each port
- Ranked the ports within each border based on their total weighted sum in descending order (highest weighted sum gets the highest rank).
- Combined the weighted sums of ports from both borders.
  Ranked all ports overall, regardless of the border, based on their total weighted sum.

#### Methodology
1. *Data Cleaning*: Prepared the dataset for analysis.Converted date column to respective months and year.
2. *Exploratory Data Analysis*: Identified key features and patterns.
3. *Visualization*: Used charts and graphs to illustrate findings.Created a dashboard which can help visualize state wise ports with a given date and type of crossings.
4. *Metric Development*: Created and applied a composite metric to rank ports.
