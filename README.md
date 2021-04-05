# Classification_Project

Mod3 Classification Project using data from Taarifa and the Tanzanian Ministry of Water

by Antonio Hila and Jude Buenaseda

This project aims to predict which pumps are functional, which need some repairs, and which don't work at all as part of the Pump it Up: Data Mining the Water Table Competition by Drivendata (www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/) 


## Project Overview

For this project we are looking at data on water wells in Tanzania. We want to see what factors of the well (location, altitude, quantity and quality of water, etc) lead to lack of functionality of wells. This information could then be used by the companies that handle the functionality of the well (whether it be the government or the other companies) to decide what wells that are functional now may be showing signs of wear and will need to be replaced soon.

The approach we took on this was to first look at this problem as a logical one and use preset ideas we had about wells and what could lead to damage to make a base model. From there we used different methods of Data analysis to get a better idea of what exactly we want to look at.

What we found through our visualizations and analysis was that the location of the wells (using latitude and longitude) and the age of the wells, among other factors were what contributed primarily to understanding which wells needed to be repaired or replaced

## Data Gathering and Analysis

The data was taken from the driven data project on the wells in Tanzania. With that data we used different libraries in python to visualize the data including Folium to plot the data using a map and to them model the data and gather predictions.


## Github Content

- CSV_files: Collection of all CSV's used and then created throughout the process
- Graphs and EDA: All Visualizations obtained through the project
- Pickle_files: All saved data that wasnt a csv or visual
- General: General overview of all the data including base models for which we will be basing our final models off of as a reference point
- EDA_Modeling_1: Used visualizations to gather analysis of the wells for use in the modeling. Also generated some base models using the eda from the visualizations
- PCA_Feature_Importance: Used PCA Clustering to get a better breakdown of which features have the most value in the final models
- Mod_3_project_Final_Notebook: Final Collection of the results and final model that was used
- Pipeline functions: Collection of all the functions used throughout the notebooks 


## EDA

- Identifying Well Clusters by Region Using Folium

![](/Visualizations/clusters.png)


- Distribution of Well Classes

![](/Visualizations/wellclasses.png)

## Blog Article

https://antoniohila.medium.com/analyzing-water-well-data-in-tanzania-48a394fd7005
