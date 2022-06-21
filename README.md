# Performing-Analysis-of-Meteorological-Data
This blog is mainly for the weather history and we will be performing data analytics in it.
Before going through the blog we must understand the dataset which we have taken from Kaggle about the weather
Source URL: https://www.kaggle.com/muthuj7/weather-dataset
Dataset consists of columns
Formatted Date, Summary, Precip Type ,Temperature, Apparent Temperature ,Humidity ,Wind Speed (km/h) , Wind Bearing (degrees) ,Visibility (km) ,Pressure (millibars) ,Daily Summary
Here we have 11 columns with rows 96453.
The Null Hypothesis is "Has the Apparent temperature and humidity compared monthly across 10 years of the data indicate an increase due to Global Warming".
We need to find whether the average Apparent Temperature for a month say April starting from the year 2006 to 2016 and the average Humidity for the same period has increased or not.
This monthly analysis has to be done for all 12 months over the 10-year period. So we're basically resampling our data from hourly to monthly, then comparing the same month over the 10-year period.
Also, we have to support our analysis with appropriate visualizations.
First step:
Importing libraries and loading the dataset.
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import Libraries and loading dataset
Now we will be performing some basic operations for the analysis purpose
DATA CLEANING
Now we will be selecting the columns for our analysis Formatted Date, Apparent Temperature, and Humidity.
Now we will be Now let's dig deeper using some graphs and visualizations.
Here we've plotted the yearly variation in Apparent Temperature and Humidity over the 10-year period starting from 2006 to 2016.
We can see that both the peaks and the troughs in the graph are almost the same throughout the 10-year period.
Here is a plot that shows the yearly variation in Apparent Temperature © and Humidity for the month of April over the 10-year period starting from 2006 to 2016 -
From this we will conclude from our analysis we can conclude that there is no such increase in the average Apparent Temperature and average Humidity due to global warming as mentioned in the null hypothesis.
I am really thankful to the team of Suven consultants for providing me with this opportunity to showcase the given problem statement and for giving me a coding internship. Thank you, Suven consultants.
