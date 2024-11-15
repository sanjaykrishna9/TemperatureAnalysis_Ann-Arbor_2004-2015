# TemperatureAnalysis for Ann-Arbor,Michigan(2004-2015)

This repository contains a Python-based analysis and visualization of NOAA temperature data near Ann Arbor, Michigan, United States.   
The project focuses on analyzing temperature records over a 10-year period (2005–2014) and highlighting temperature anomalies in 2015.

# Dataset Description
The data used for this analysis is derived from the Daily Global Historical Climatology Network (GHCN-Daily)   
provided by NOAA's National Centers for Environmental Information (NCEI). 

Two CSV files are provided:

__temperature.csv:__ Contains daily temperature records with the following columns:  
id: Station identification code  
date: Date in DD-MM-YYYY format  
element: Type of temperature data (TMAX for maximum, TMIN for minimum)  
value: Recorded temperature (tenths of degrees Celsius)   

__BinSize.csv:__ Contains fields like 
id: Station identification code    
longitude:A geographic coordinate that specifies the east–west position of a point on the Earth's surface.  
latitude:A geographic coordinate that specifies the north–south position of a point on the Earth's surface.

# Task Overview
*Record Temperature Visualization (2005–2014)*  
Generate a line graph showing the record high and low temperatures for each day of the year.
Shade the area between record highs and lows.

*2015 Anomalies Overlay*   
Overlay a scatter plot of 2015 temperature data points (highs and lows) where the 2005–2014 record was broken.

*Leap Day Handling*  
Exclude leap day data (February 29) to ensure accurate day-to-day comparisons. 

*Visualization Enhancements*  
Add appropriate legends, axis labels, and titles to improve clarity.  
Remove unnecessary chart elements to reduce chart junk.

*Station Mapping*  
Visualize the locations of weather stations near Ann Arbor, Michigan, on a map.

*2015 Temperature Summary*  
Create summary visualizations for 2015 temperature data near Ann Arbor, Michigan.


# Modules Used:
-Pandas  
-Matplotlib  
-Folium  

# Usage
1 Install libraries : pip install pandas  
                      python -m pip install folium  
                      python -m pip install -U matplotlib  

2 Run the Jupyter notebook to perform the analysis and visualize the results.
