# NYC Congestion Pricing Impact

## Description

This repository contains the analysis of the effects of congestion pricing on traffic volume and public transit ridership across New York City's five boroughs. The focus is on exploring the relationship between congestion pricing policies and transportation patterns, using various data sources and models.

## Folder Structure


## Data Sources
- **Traffic Volume** [https://data.cityofnewyork.us/Transportation/Automated-Traffic-Volume-Counts/7ym2-wayt/about_data]
- **CRZ Vehicle Entries** [https://data.ny.gov/Transportation/MTA-Congestion-Relief-Zone-Vehicle-Entries-Beginni/t6yz-b64h/about_data]
- **MTA Subway and Bus Hourly Ridership** [https://data.ny.gov/Transportation/MTA-Subway-Hourly-Ridership-2020-2024/wujg-7c2s/about_data] [https://data.ny.gov/Transportation/MTA-Bus-Hourly-Ridership-2020-2024/kv7t-n8in/about_data]
- **311 complaints data** [https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9/about_data]
- **NYPD Crash and Vehicle Datasets** [https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95/about_data]

## Processed Data

- **311_2025.csv**: Service request data collected from the 311 system for the year 2025.
- **311_2325.csv**: Service request data from 2023-2025, providing insights into community concerns and city service operations.
- **congestion_zone.zip**: Contains information about New York City's congestion pricing zones.
- **Modified_Zip_Code_Tabulation_Areas__MODZCTA__20250427.csv**: Updated ZIP Code Tabulation Area data for 2025 used in geographic analysis.

## Notebooks

The Jupyter notebooks in the **Notebooks** folder provide the analysis and modeling steps used to explore the impact of congestion pricing. Key analyses include:

- **Exploration_2024Subway.ipynb**: Exploration of 2024 subway ridership data.
- **Exploration_2024TrafficVolumn.ipynb**: Exploration of 2024 traffic volume data.
- **Model_Cluster_311DataCongestion.ipynb**: Clustering model to identify patterns in 311 data related to congestion.
- **Model_DiD_Crash.ipynb**: Difference-in-Differences approach to analyze crash data before and after the policy implementation.
- **Model_Timeseries_RidershipSubway&Bus.ipynb**: Time series analysis for subway and bus ridership patterns.
- **Model_Timeseries_TrafficVolume.ipynb**: Time series analysis of traffic volume trends.

## Results

- **Congestion Pricing Analysis Final Presentation.pptx**: The final presentation summarizing the analysis results and key findings related to congestion pricing and its impact on New York City.
