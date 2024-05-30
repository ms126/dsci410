## Overview:
This project offers a comprehensive overview of the CAHOOTS call log data, providing detailed insights into the demographics and trends within the data. By comparing the findings with census data, we can better understand the population served by CAHOOTS and identify areas for potential improvement in service delivery.

## RQs: 
The questions I am interested in answering are: How do demographics differ over time of day, day of the week, and over season? & How does the volume of CAHOOTS calls vary over time of day, day of the week, and over season? I chose to answer these questions because they provide answers as to when CAHOOTS provides the most help, and who they are helping. I want to see if there is a correlation between call times and demographics, or if there are any patterns that I can seek out which will help CAHOOTS in the future.

## Data:
cahoots_data.csv –– main CSV with all the call log information

Eugene-SpringfieldCensus.csv –– Census data, downloaded from [this](https://www.census.gov/quickfacts/fact/table/springfieldcityoregon,eugenecityoregon/POP060210) website.

## Data cleaning/processing steps
•	Imported CSV into Jupyter Notebook

•	Dropped ‘Language’ column

•	Converted entries in ‘Gender’ column to be consistent (changed FEMALE to Female, etc..)

•	Made bar graphs to display distributions and frequencies of each columns in the dataset

•	Made visualizations for:

  o	Gender breakdown for calls by month
  
  o	Age breakdown, after dividing ages into various ranges
  
  o	Call volume by hour AND month
  
  o	Most/least frequent call hour sorted by month
  
  o	Heatmap of frequency of calls by hour & month
  
  o	Boxplot of age distribution by reason for dispatch

## Methods:
![Picture1](https://github.com/ms126/dsci410/assets/109988475/2d99f24e-2d4b-41fd-9f8c-363e69b2ffd0)

### Required Libraries: 
NumPy, Pandas, Seaborn, Scipy, Matplotlib







