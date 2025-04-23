# Screen Time Analysis in R

This project analyzes screen time data using R, providing insights into app usage patterns, notification frequency, and how often apps are opened.

## Project Description

The goal of this project is to analyze screen time data.  The analysis focuses on:

* Loading and inspecting the data.
* Calculating summary statistics.
* Analyzing screen time trends for different apps.

##   File Structure

* `Screen_Time_Analysis.ipynb`: Jupyter Notebook containing the R code.
* `screentime_analysis (1).csv`: CSV file containing the screen time data.

##   Requirements

* R 3.6 or later
* R Packages:
    * `readr`
    * `ggplot2`
    * `lubridate`

##   Usage

The notebook performs the following steps:

1.  **Imports Libraries**: Imports the necessary R libraries.
2.  **Loads Data**: Loads the screen time data from the CSV file.
3.  **Displays Data**:  Displays the first few rows of the data using `head()`.
4.  **Calculates Summary Statistics**:  Calculates and displays summary statistics of the data using `summary()`.
5.  **Analyzes Screen Time Trends**:  Creates a plot showing screen time trends for different apps using `ggplot2` and `lubridate`.

##   Data Description

The `screentime_analysis (1).csv` file contains the following columns:

* `Date`:  The date of the screen time record.
* `App`:  The name of the app.
* `Usage (minutes)`:  The amount of time the app was used in minutes.
* `Notifications`:  The number of notifications received from the app.
* `Times Opened`:  The number of times the app was opened.

##   Analysis

The analysis includes:

* **Descriptive Statistics**:  Basic statistics of the usage, notifications, and times opened.
* **Trend Analysis**:  Visualization of app usage over time to identify trends.
