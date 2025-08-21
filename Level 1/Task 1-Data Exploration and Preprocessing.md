**TASK 1- DATA EXPLORATION AND PREPROCESSING**

**Task Overview**

This task aims to explore the dataset for identifying missing values,analyzing the distribution of the target variable("Aggregate rating") and identify any class imbalances.

**Dataset Overview**

The dataset for this analysis contains 9551 instances and 21 features, including the target variable. The target variable indicates the aggregate rating with value from 0 to 5.Some features like Country code are stored as integer but represents categorical variable.

**Library imports**

The following python libraries were used for analysis:

- import pandas as pd
- import numpy as np
- import matplotlib.pyplot as plt
- import seaborn as sns

**Dataset Loading**

The dataset is in CSV format, and it was loaded into a pandas DataFrame using the pd.read_csv() function.

**Exploratory Data Analysis(EDA)**

In this phase, we explore and analyze the basic structure and characteristics of the dataset. The following aspects are examined:

- Dataset shape (number of rows and columns)
- Data types of each feature
- Unique values and distributions
- Statistical summary (mean, median, standard deviation, etc.)
- Missing values

  This initial analysis helps for a better understanding of the dataset and for the preprocessing steps.

**Datapreprocessing**

Various dataset preprocessing steps were performed to prepare data for modelling.Same is brifely explained in this part:

a. Removing irrelavent fields

- The categorical column 'Switch to order menu' does not contribute to prediction and hence dropped.

b. Handling Null Values

- The dataset contain null values in the field 'Cuisines'.

c. Finding and removing duplicate value

- There are no duplicate values in the dataset.

**Conclusion and Key Findings**

- Majority of the customers have not rated the restaurants or missing.
- Most of the customers have given rating between 3-3.5.
- Restaurants with very less and very high rating is fewer.
- Given dataset is highly imbalanced which can lead the ML model to bias.Class imbalance can be handled using SMOTE Technique.
