# Prosper Loan Data
## Patrick Schütze


## Dataset

The Dataset contains 81 columns and 113,917 rows. Each rows contains information about the borrower and all necessary loan data.
All variables with missing values were dropped or corrected.


The original dataset can be download here: https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1547358770029000


## Summary of Findings



A good ProsperRating or a good ProsperScore does effect the percentage of the rate the borrower will get.
The higher the rating the lower the percentage and the earlier the ProsperRating letter appears in the alphabet, the better the percentage.

Of all the variables, ProsperScore and ProsperRating have a strong relationship to BorrowerAPR and BorrowerRate.
As expected, the risk rating values play a very large role in the granting of loans to borrowers.

BorrowerRate is positive correlated with ProsperRating and ProsperScore.
The better the Rating and the Score, the lower the individual BorrowerRate.

## Key Insights for Presentation

The first plot shows the the Distribution of the borrower rate with a median of 1.86%. A max of 3.6% and a min of 0.4%.
ProsperScore has the strongest relationship with BorrowerRate (negatively correlated).
Scatter plot and Heatmap were created to show that ProsperScore and BorrowerRate are negatively correlated.
The third plot shows BorrowerRate vs ProsperRating vs ProsperScore.
We can see here that a better Rating and a better ProsperScore leads to a better rate for the borrower.

## Sources:

https://www.machinelearningplus.com/plots/top-50-matplotlib-visualizations-the-master-plots-python/
https://matplotlib.org/
https://realpython.com/python-matplotlib-guide/
https://plot.ly/python/
