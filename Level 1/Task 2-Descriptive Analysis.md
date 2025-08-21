**TASK 2- DESCRIPTIVE ANALYSIS**

**Task Overview**

The objective of this task is to perform descriptive analysis on the dataset to understand the distribution of restaurants across countries, cities, and cuisines.Basic statistical measures (mean,median, standard deviation, etc.) for numerical columns is found and explored the distribution of categorical variables like "Country Code," "City," and"Cuisines." Additionally,top cuisines and cities with the highest number of restaurants is identified.

**Dataset Overview**

The dataset for this analysis contains 9551 instances and 21 features, including the target variable. The target variable indicates the aggregate rating with value from 0 to 5.Some features like Country code are stored as integer but represents categorical variable.

**Library imports**

The following python libraries were used for analysis:

import pandas as pd

import numpy as np

import matplotlib.pyplot as plt

import seaborn as sns

**Dataset Loading**

The dataset is in CSV format, and it was loaded into a pandas DataFrame using the pd.read_csv() function.

**Statistical Summary**

- In this phase, the mean,median values of numerical features were found using describe function.

**Distribution of categorical variables**

- The distribution of categorial variables "Country Code","City" and "Cuisines" were analysed using unique(),nunique(),value_counts().
-  In the Cuisines column, multiple cuisines were stored as strings. These were split using .str.split(',') and transformed into individual rows with .explode()

**Conclusion and Key Findings**
- Most of the restaurants are in country code 1.
- New Delhi has most of the restaurants.
- Most demanded cuisines are North Indian and Chinese.
- Multicuisines restaurants were split to count each cuisines.
- There are 15 unique countries,141 unique cities and 145 unique cuisines.

 **Top three cuisinies**
 
    Cuisines	         Restaurant Count
 
     North Indian	           685

     Chinese	               556

     Italian	               398


**Top three cities with highest number of restaurant**

    City	         Count
  
	New Delhi	      2197
 
     Gurgaon	       831
  
     Noida       	   265


