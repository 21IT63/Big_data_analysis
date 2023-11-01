# Big_data_analysis
Big Data Analysis Project - GlobalLandTemperaturesByCity Dataset

#Project Overview
This project explores historical temperature records from various cities worldwide using the GlobalLandTemperaturesByCity dataset. The objective is to perform time series analysis and visualize monthly average temperatures over time.

#Dataset Description
The GlobalLandTemperaturesByCity dataset provides historical temperature records with details such as date, city, country, and average temperature. It covers a wide range of cities and regions worldwide, making it a valuable resource for climate and weather analysis.

#Setup and Dependencies
To run this project, you need the following dependencies:

Python (3.6+)
Pandas
Matplotlib
Seaborn
You can install the required Python packages using pip:

#Data Analysis
The 'dt' column is converted to a datetime format.
The 'dt' column is set as the index for time series analysis.
The data is resampled to calculate monthly average temperatures.

#Visualization
The project uses Matplotlib and Seaborn for visualization:

A line plot is generated to visualize monthly average temperatures over time.
Seaborn is used to improve the plot's style.
Results
The project produces a time series plot that displays the monthly average temperature over time. It can help identify temperature trends, seasonal patterns, and long-term variations.
