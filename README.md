This project performs EDA on sales data to uncover insights and trends that can guide business decisions. 
Each analysis addresses a specific question, and visualizations are used to present the findings effectively.

Dependencies
Ensure you have the following Python packages installed:

1. pandas
2. numpy
3. matplotlib
4. seaborn
   
Questions and Visualizations:

EXPLORATORY DATA ANALYSIS
1. What is the distribution of sales across different regions?
Visualization: Bar chart or pie chart showing the total revenue per region.
Goal: Identify regions contributing the most to revenue.

2. Which product types contribute most to total profit?
Visualization: Horizontal bar chart of Item Type vs. Total Profit.
Goal: Determine which product types drive profitability.

3. How does the sales channel (Online/Offline) impact total revenue?
Visualization: Boxplot comparing Total Revenue by Sales Channel.
Goal: Analyze revenue distribution for different sales channels.

4. What are the trends in sales over time?
Visualization: Line chart of Order Date vs. Total Revenue.
Goal: Explore revenue trends over time to identify peaks and patterns.

5. Which country generates the highest revenue, and how do other countries compare?
Visualization: Horizontal bar chart of Country vs. Total Revenue.
Goal: Identify top-performing countries in revenue generation.

6. How do different order priorities impact profits?
Visualization: Stacked bar chart or boxplot of Order Priority vs. Total Profit.
Goal: Evaluate how order priorities affect profitability.

7. What are the relationships between Units Sold, Unit Price, and Total Profit?
Visualization: Scatterplot with Units Sold on the x-axis and Total Profit on the y-axis, sized or colored by Unit Price.
Goal: Understand correlations between these variables.

8. What are the shipping delays across regions?
Visualization: Bar chart showing average shipping delay (Ship Date - Order Date) by Region.
Goal: Highlight regions with potential shipping inefficiencies.

ADVANCED ANALYSIS
9. Seasonality of Sales
Question: Are there specific months or seasons with higher sales?
Visualization: Line chart showing monthly Total Revenue trends.
Goal: Uncover seasonal trends to optimize planning.

10. Impact of Unit Price on Sales
Question: Does reducing the Unit Price increase the Units Sold?
Visualization: Scatterplot with regression line for Unit Price vs. Units Sold.
Goal: Understand the price elasticity of demand.

11. Top-performing Product in Each Region
Question: Which Item Type performs best in each region?
Visualization: Grouped bar chart of Item Type vs. Total Profit for each Region.
Goal: Identify region-specific bestsellers.

12. Time to Deliver Orders
Question: What is the average delivery time for each priority level?
Visualization: Boxplot of Order Priority vs. delivery time (Ship Date - Order Date).
Goal: Assess delivery efficiency across priorities.
