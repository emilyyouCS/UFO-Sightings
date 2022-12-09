# UFO-Sightings

Data analysis project in R using the UFO Sightings data set on Kaggle courtesy of the NATIONAL UFO REPORTING CENTER (NUFORC). 

https://www.kaggle.com/datasets/NUFORC/ufo-sightings

The object of the project was to see if there was a trends such as location, time, appearance etc.

Overall, we used a combination of data cleaning, visualization, dimensionality reduction, and clustering techniques to analyze the data. We used a range of functions and packages in R to perform these tasks, including the tidyverse, lubridate, dplyr, corrplot, factoextra, dendextend, ggplot2, and others. The project provides valuable experience in data analysis and visualization using R, and demonstrates the ability to use R for a wide range of data analysis tasks.

Summary of the steps below:

1. Load the data into a data frame, replacing all blanks and "NA" values with null values, and stripping whitespace.
2. View the data, including the number of observations and variables, and the levels of the "state" and "country" variables.
3. View the number of observations by country.
4. Drop the "duration in hours and minutes" and "date posted" columns, since these are redundant with other columns in the data.
5. Check for and remove null values in the data.
6. Convert the "datetime" variable into separate columns for year, month, day, and time in hours.
7. Create box plots to visualize the data by time of day, month, and year.
8. Create density plots to visualize the data by time of day, month, and year.
9. Scale the data and convert it to a numeric matrix.
10. Create a correlation plot to visualize the relationships between different variables in the data.
11. Use principal component analysis (PCA) to reduce the dimensionality of the data.
12. Use k-means clustering to group the data into clusters.
13. Use hierarchical clustering with different linkage methods to group the data into clusters.


