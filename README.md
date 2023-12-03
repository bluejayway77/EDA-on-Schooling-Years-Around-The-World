# EDA-on-Schooling-Years-Around-The-World

## Synopsis
This repository focuses on analyzing trends and patterns on schooling years in 193 countries to check key gaps and differences, based on Human Develpment Groups, UNDP Regions, Continent and HDI Rank. The initial dataset was retreived from Kaggle. I am providing the link to its source, besides, I am attaching the code I developed for this work.

## Data Load and Transformation
Since the data was presented in pivot shape, it was essential to perform some transformations in order to get some aggregations. Then, the year for each, initially, column and then row was extracted, besides some other replacements and generate a column for growth. In addition, getting rid of some countries with no information also was part of the initial section of this analysis.

## Exploratory Data Analysis
For this segment, libraries such as pandas, numpy, seaborn and plotly.express were used to get statistical metrics and plotting the information in an appealing way. Hence, patterns and trends were unveiled.

## Visualization
A dynamic presentation is provided in a pbix file to load into Power Bi desktop, so the user can explore key insights. The dashboard includes a distribution for schooling years, bottom and top countries with lowest and highest average schooling years, growth across time and a choropleth map.

## Disclaimer

Since GitHub does not show dynamic plotly charts, two notebooks were provided: Static and dynamic. Static shows the charts as images. Consequently, for the dynamic one, you can copy the url and run it here: https://nbviewer.org/ 

## Data Source

https://www.kaggle.com/datasets/iamsouravbanerjee/years-of-schooling-worldwide
