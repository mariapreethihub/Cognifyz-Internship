# TASK 3- FEATURE ENGINEERING

**Task Overview**

The objective of this task is to extract additional features from the existing columns and to create new features by encoding categorical variables.

**Dataset Overview**

The dataset for this analysis contains 9551 instances and 21 features, including the target variable. The target variable indicates the aggregate rating with value from 0 to 5.Some features like Country code are stored as integer but represents categorical variable.

**Library imports**

The following python libraries were used for analysis:

import pandas as pd

import numpy as np


**Conclusion**
- New columns 'Name_Length and Address_Length is created from existing column 'Restaurant name' and 'Address' which contains the length of restaurant name and adress.
- Fields 'Has Table booking','Has Online delivery and 'Is delivering now' are categorical in nature and hence same is converted as binary values using map() function.
- 'Rating color' and 'Rating text ' are categorical variables.ML models cannot work directly with text and hence OneHotEncoding is performed for the features.
  
