# Basic-Data-analysis-related-problem
In this section I do some basic data analysis related problem
A survey was conducted to gauge an audience interest in different data science topics, namely:

1. Big Data (Spark / Hadoop)
2. Data Analysis / Statistics
3. Data Journalism
4. Data Visualization
5. Deep Learning
6. Machine Learning
7. The participants had three options for each topic: Very Interested, Somewhat interested, and Not interested. 2,233 respondents completed the survey.

The survey results have been saved in a csv file and can be accessed through this link: https://cocl.us/datascience_survey_data.

If you examine the csv file, you will find that the first column represents the data science topics and the first row represents the choices for each topic.



Use the artist layer of Matplotlib to replicate the bar chart below to visualize the percentage of the respondents' interest in the different data science topics surveyed.





To create this bar chart, you can follow the following steps:

Sort the dataframe in descending order of Very interested.
Convert the numbers into percentages of the total number of respondents. Recall that 2,233 respondents completed the survey. Round percentages to 2 decimal places.
As for the chart:
use a figure size of (20, 8),
bar width of 0.8,
use color #5cb85c for the Very interested bars, color #5bc0de for the Somewhat interested bars, and color #d9534f for the Not interested bars,
use font size 14 for the bar labels, percentages, and legend,
use font size 16 for the title, and,
display the percentages above the bars as shown above, and remove the left, top, and right borders.



In the final lab, we created a map with markers to explore crime rate in San Francisco, California. In this question, you are required to create a Choropleth map to visualize crime in San Francisco.

Before you are ready to start building the map, let's restructure the data so that it is in the right format for the Choropleth map. Essentially, you will need to create a dataframe that lists each neighborhood in San Francisco along with the corresponding total number of crimes.

Based on the San Francisco crime dataset, you will find that San Francisco consists of 10 main neighborhoods, namely:

1.Central,
2.Southern,
3.Bayview,
4.Mission,
5.Park,
6.Richmond,
7.Ingleside,
8.Taraval,
9.Northern, and,
10.Tenderloin.
