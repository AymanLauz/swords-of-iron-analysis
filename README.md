# Swords of Iron Analysis 🚧 [Work in Progress] #

## Project Status: Under Development ##

This repository is a work in progress. It documents my journey as I build an end-to-end data science pipeline analyzing the security situation in Israel during the Swords of Iron war.

## Current Progress ##

[x] Data ingestion from CSV files (Alarms, Victims, Kidnappings data).

[x] Data cleaning and Hebrew-to-English mapping.

[x] Preliminary Exploratory Data Analysis (EDA) of alarm frequencies and demographics.

## Future Roadmap ##

[ ] Geocoding of cities for spatial analysis.

[ ] Interactive Heatmap of Red Alerts across Israel.

[ ] Correlation analysis between active combat periods and civilian safety metrics.

# About the Project #

This analysis explores the impact of the conflict from October 7, 2023, through 2025. By visualizing Red Alert sirens and demographic data, this project aims to tell a story of the home front through data.

# Note on Data Availability #

The raw datasets (alarms.csv, victims.csv, and kidnapped.csv) used in this analysis are private and are not included in this repository due to ownership and privacy considerations. The code provided in project.ipynb serves as a template for how this data can be processed and visualized.

Note: In respect for the privacy of victims and their families, personal identifying information is excluded from this analysis.

# Tech Stack #

Environment: Google Colab

Libraries: Pandas, Seaborn, Matplotlib, NumPy

Planned: Folium (Mapping), Geopy (Geocoding)

# How to View #

The analysis is contained within project.ipynb. While the project is in progress, the notebook currently displays initial visualizations of alarm distribution and demographic breakdowns.

# License #

MIT License
