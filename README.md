# Temp_Data_Analysis

## 📜 Overview
This project analyzes historical temperature data from NOAA's Global Historical Climatology Network (GHCN-Daily) dataset. It focuses on visualizing temperature trends, detecting record-breaking temperatures, and mapping weather stations near Ann Arbor, Michigan.

## 📊 Dataset
The data for this assignment comes from a subset of The National Centers for Environmental Information (NCEI) [Daily Global Historical Climatology Network (GHCN-Daily). The GHCN-Daily is comprised of daily climate records from thousands of land surface stations across the globe. Each row in the assignment datafile corresponds to a single observation.

### Temperature.csv:
- **ID**: station identification code.
- **Date**: date in YYYY-MM-DD format.
- **Element**: Temperature type (TMAX, TMIN).
- **Data_Value**: Temperature in tenths of degrees Celsius.

### BinSize.csv:
- **ID**: station identification code.
- **Latitude & Longitude**: Geolocation of stations.
- **Name**: Station name.

## 📈 Analysis and Implementation
### Record Highs and Lows (2005-2014) with 2015 Breaks
- Extracted historical temperature extremes per day.
- Compared 2015 data to detect new record-breaking temperatures.
- Visualized using a line plot with shaded areas and scatter markers.
### Weather Station Locations near Ann Arbor
- Mapped station locations using latitude and longitude data.
- Ann Arbor was marked separately for reference.
### Temperature Summary for Ann Arbor (2015)
- Computed daily average TMAX and TMIN for 2015.
- 
## 🛠️ Tools & Technologies
- **Programming Language**: Python
- **Libraries**: Pandas,Matplotlib.

## 🛠️ Installation
### Load Data
- Place temperature.csv and BinSize.csv in the project directory.
### Run Analysis
- Execute the Python script to generate visualizations.

---
Feel free to explore, contribute, and share your feedback! 
