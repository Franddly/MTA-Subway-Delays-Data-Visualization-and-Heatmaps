# MTA Subway Delays(2020-2024): Data Visualization and Heatmaps

## Project Overview
For my first project, I chose Subway delays as it is a contributing factor to my everyday travels, i wanted to visually picture and depict how often delays happened within my area among others. The goal of this is to visualize the data and detect any trends in delays across local train lines within your area.

## Dataset

Source of data: https://data.ny.gov/Transportation/MTA-Subway-Trains-Delayed-2020-2024/wx2t-qtaz/about_data
This dataset contains records of subway delays across 2020-2024 including its month, weekday/weekend, line, and reported cause of delay.

Columns: 7

The data was cleaned and compacted by:
 - Removing any empty rows of values

## Tools Used and Libraries
 - Language: Python
 - Environment: Jupyter Notebook (via Anaconda)
 - Libraries:
       - pandas -> used for data cleaning
       - matplotlib/seaborn -> used for visualizations
       - numpy -> used for data manipulation

## Visualizations
  1. Red Heatmap: Sum of Monthly delays across each specific train line from 2020-2024
  2. Green Heatmap: Delays across train lines between Weekdays/Weekends from 2020-2024
  3. Blue Heatmap: Cumulative reported reasons of delays amongst months from 2020-2024

## How to Run the Project
### Clone the repository:
 git clone (https://github.com/Franddly/MTA-Subway-Delays-Data-Visualization-and-Heatmaps)
### Navigate inside the project folder
 cd MTA-Subway-Delays-Data-Visualization-and-Heatmaps
### Install dependencies
 pip install -r requirements.txt
### Open it on Jupyter Notebook and run it
 jupyter notebook

## Findings
1) It can be depicted from the Red Heatmap that train lines A, F, 6, and N follow a trend of having the highest average monthly delays throughout the year, with a minimum of 10,000 reports per month.

2) It can be depicted from the Green Heatmap that the N train has the highest average number of reports on weekdays compared to its close competitors, the F and 6 trains. This can be assumed to be due to high demand and a lack of infrastructure durability, which may cause higher levels of malfunctions. Additionally, all trains show an ongoing trend of more than a 33% turnover rate of reported delays during the weekends. This may be attributed to lower transit demand, resulting in less wear on infrastructure.

3) The Blue Heatmap depicts that during holiday months such as June–August and November–January, all categories of reports show the highest total across the year. Infrastructure and equipment also have the highest number of reports throughout every month.

### Learning Outcomes
1) Gained Hands-on experience cleaning real-world datasets, including handling missing values and compacting data that can be used for further analysis
2) Developed a better learning for the use of pandas through filtering, transforming and preparing datasets for visualization.
3) Developed a better understanding of creating insightful visualizations using matplotlib and seaborn, those being heatmaps that depict trends over time.
4) Learned to interpret visual patterns in data through heatmaps, such as peak delay times and high traffic train lines.
5) Improved my ability to communicate analytical findings clearly through written summaries and visual representations 




