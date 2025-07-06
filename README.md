# Nepal Climate Data Analytics Project

This project focuses on performing end-to-end data analysis on Nepal's climate dataset obtained from Kaggle, which sources its data from NASA's POWER project.

## 📝 Project Overview

The analysis spans multiple steps including:

- **Big Data Handling with PySpark:** Initial exploration and attempted processing of the large dataset using PySpark with HDFS setup.
- **Data Analysis with Pandas:** Shifted to Jupyter Notebook for detailed data wrangling and visualizations using pandas, matplotlib, and seaborn.
- **Visualization:** Generated insightful plots to observe temperature trends over years, district-wise temperature averages from 1990 onwards, and wind speed distributions.
- **Future Scope:** Building predictive models to forecast climate parameters using this dataset.

## 📂 Dataset

- **Source:** [Kaggle - Nepal Daily Climate (1981-2019)]([https://www.kaggle.com/](https://www.kaggle.com/datasets/saimondahal/nepal-daily-climate-1981-2019))  
- **Description:** Daily climate data for 93 weather stations across 62 districts in Nepal with parameters such as temperature, humidity, wind speed, precipitation, and pressure from 1981 onwards.
- **Key Features:**
  - Date, District, Latitude, Longitude
  - Temperature (mean, min, max, wet bulb, range)
  - Humidity (specific and relative)
  - Precipitation, Pressure
  - Wind Speed at 10m and 50m levels with their respective ranges

## 💻 Technologies Used

- **PySpark:** For initial big data reading, exploration, and environment setup.
- **HDFS & YARN:** Configured for distributed file storage and processing.
- **Pandas:** For data wrangling and manipulation.
- **Matplotlib & Seaborn:** For creating meaningful visualizations.
- **Jupyter Notebook:** Interactive environment for analysis and visualization.

## 📊 Current Analysis

- Converted date to datetime for time-series analysis.
- Extracted year to observe average temperature trends.
- Grouped data to analyse district-wise temperature averages post-1990.
- Explored wind speed distributions with histograms and frequency observations.
- Generated heatmaps for correlation analysis among numerical variables.

## 🚀 Future Plans

- Time series modeling for temperature prediction.
- Machine learning models to analyse climate patterns.

## 📌 Motivation

This project was undertaken as part of my daily data analytics learning streak to build practical skills in big data, data analysis, and visualization while exploring Nepal's real climate data.

## 🐦 Follow Daily Updates

For my daily learning progress and insights from this project, follow me on Twitter: [@YourTwitterHandle](https://x.com/itspriibhatta)


