**TASK 3- GEOSPATIAL ANALYSIS**

**Task Overview**

The objective of this task is to visualize the locations of restaurants on a map using latitude and longitude,to analyze the distribution of restaurants across different cities or countries and determine if there is any correlationbetween the restaurant's location and its rating.

**Dataset Overview**

The dataset for this analysis contains 9551 instances and 21 features, including the target variable. The target variable indicates the aggregate rating with value from 0 to 5.Some features like Country code are stored as integer but represents categorical variable.

**Library imports**

The following python libraries were used for analysis:

- import pandas as pd

- import numpy as np

- import matplotlib.pyplot as plt
  
- import seaborn as sns
  
- import folium



**Conclusion and Key Findings**

- The scatter plot shows distribution of restaurant across the city.Most restaurants are highly concentrated in the latitude range of 10–30 and longitude range of 70–80.

- New Delhi has the top 5 most popular restaurants which indicates the dominace of the City in restaurant market.

- The correaltion between latitude, logitude with Aggregate Rating is less than 0.3 which indicates a weak relationship.This suggets that restaurant's location does not influence rating.



