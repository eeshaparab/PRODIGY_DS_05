US Traffic Accidents Analysis

This project involves the analysis of a large dataset of traffic accidents in the United States. The dataset includes a variety of features such as the location of the accident, weather conditions, and other contextual factors. This README provides an overview of the dataset, the analyses performed, and instructions for running the code.

Dataset
The dataset used in this analysis contains 7,728,394 entries and 46 columns. Some of the key columns include:

ID: Unique identifier for each accident.
Source: Source of the data.
Severity: Severity of the accident (scale 1-4).
Start_Time: Start time of the accident.
End_Time: End time of the accident.
Start_Lat/Start_Lng: Latitude and Longitude where the accident started.
End_Lat/End_Lng: Latitude and Longitude where the accident ended.
City: City where the accident occurred.
State: State where the accident occurred.
Temperature(F): Temperature at the time of the accident.
Weather_Condition: Weather condition at the time of the accident.
Traffic_Signal: Whether a traffic signal was present at the accident location.
Sunrise_Sunset: Time of the day (Sunrise/Sunset).

Project Overview
1. Initial Data Inspection
Column Overview: There are 46 columns with a mix of categorical, boolean, and numerical data types.
Missing Data: A significant portion of the dataset contains missing values. The columns with the highest percentage of missing data include End_Lat, End_Lng, Precipitation(in), and Wind_Chill(F).

3. Exploratory Data Analysis (EDA)
The EDA process involves understanding the distribution of accidents across different cities, analyzing the severity of accidents, and looking at weather conditions at the time of accidents.

City Analysis: The dataset includes accidents from 13,678 cities. Cities like Miami, Houston, and Los Angeles have the highest number of recorded accidents.
Accidents by Severity: The severity of accidents is recorded on a scale of 1 to 4. The majority of accidents have a severity of 2.
Missing Data Visualization: A bar plot was generated to visualize the percentage of missing data across different columns.
Top Cities with Accidents: A horizontal bar plot visualized the top 20 cities with the highest number of accidents.

3. Visualization
The project includes various visualizations to represent the data, including:

Bar Plots: To show the distribution of accidents by city and severity.
Distribution Plots: To analyze the distribution of accidents in cities with a high number of incidents (using Seaborn’s distplot).
