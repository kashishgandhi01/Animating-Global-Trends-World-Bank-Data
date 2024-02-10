# Animating-Global-Trends-World-Bank-Data
In 2006, Hans Rosling delivered a groundbreaking TED Talk titled 'The Best Stats You've Ever Seen'. Using statistics, computer software, props, and his showmanship, Rosling illuminated facts and trends revealed by data in a series of captivating presentations. Inspired by the intersection of development economics and data analysis showcased in Rosling's work, this project seeks to reproduce the magic using statistical libraries in Python.

<h3>Project Overview</h3>
This project analyzes data from 264 countries across 7 regions spanning the years 1960 to 2016. The dataset includes key indicators such as life expectancy at birth, fertility rate, and country population. Leveraging Python libraries including NumPy, Pandas, and Plotly, the goal is to create compelling animated visualizations that offer insights into global trends in health, demographics, and development.

<h3>Dataset Information</h3>
Life Expectancy at Birth: The average number of years a newborn would live if the patterns of mortality at the time of birth remain the same throughout their life.

Fertility Rate: The average number of children a woman would give birth to during her childbearing years.

Country Population: The total number of residents regardless of legal status or citizenship.

<h3>Project Workflow</h3>
<h4>Data Exploration:</h4>

The dataset was loaded, and preliminary data exploration was conducted using functions like head(), tail(), shape, isna(), and sum() to understand its structure and contents.

<h4>Data processing:</h4>
Relevant dataframes were merged to create a comprehensive dataset for the animated scatter plot and bar graph.
A function preprocess_df was defined to remove unnecessary columns, filter out countries with missing values, and melt the dataframe to consolidate years into a single column.

<h4>Animated Scatter Plot:</h4>
An animated scatter plot was created to show fertility rate on the x-axis and life expectancy on the y-axis from 1960 to 2016.
Each bubble in the plot represented a country, with the bubbles moving from right to left, illustrating the decrease in fertility rate over time and the increase in life expectancy.

<h4>Animated Bar Chart:</h4>
An animated bar chart was developed to depict the increase in population across regions from 1960 to 2016.
Regions were plotted on the x-axis, while population counts were displayed on the y-axis.

<h3>Final Goals</h3>
The ultimate objective of this project was to create visually compelling and informative animated visualizations that offered insights into global development trends. By showcasing the evolution of key indicators such as fertility rate, life expectancy, and population over time, we aimed to provide a deeper understanding of the dynamics shaping our world.

