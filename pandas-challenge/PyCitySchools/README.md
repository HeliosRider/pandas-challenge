# pandas-challenge
This file contains a complete analysis, using Pandas and Jupyter Notebook, of district-wide standardized test results.
The goal of the anlaysis is to aggregate the data showcase school performance trends.
the anlaysis consist of assessment of  
    District Summary
    School Summary
    Various DataFrames
    Written report
    
Note: 

The following code, courtesy of Stack Overflow, was incorporated into the script:

import warnings
warnings.simplefilter(action='ignore', category=FutureWarning)

Reference: https://stackoverflow.com/questions/15777951/how-to-suppress-pandas-future-warning

The code prevents the following "pandas future warning" from populating within the script:

    FutureWarning: The default of observed=False is deprecated and will be changed to True in a future version of pandas. Pass observed=False to retain current behavior or observed=True to adopt the future default and silence this warning

After the following provided codes are ran within the script:

  1. spending_math_scores = school_spending_df.groupby(["Spending Ranges (Per Student)"])["Average Math Score"].mean()
  2. size_math_scores = per_school_summary_df.groupby(["School Size"])["Average Math Score"].mean()

