\# Lending Club Case Study We have performed a comprehensive analysis on
the loan dataset, including data cleaning, outlier treatment, feature
engineering, and various types of univariate and bivariate analyses.

\## Table of Contents \* Data Initialization \* Data Cleaning and
Manupulation \* Univariant Analysis \* Bivariant Analysis \* Correlation
Matrix \* Time based analysis \* Summary

\## General Information \### Data Cleaning: Dropped columns with 100%
missing values. Converted string percentage values to float (e.g.,
int_rate). Handled missing values by imputing the median for numerical
columns and the mode for categorical columns. Addressed outliers using
the Interquartile Range (IQR) method.

\### Feature Engineering: Extracted features from the term column and
created new features like loan_inc_ratio (loan amount to annual income
ratio), DTI (Debt-to-Income ratio), and issue_year, issue_month, and
issue_quarter from the issue_d column. Cleaned percentage columns like
int_rate and revol_util.

\### Exploratory Data Analysis: Generated summary statistics for
numerical variables and frequency counts for categorical variables.
Visualized numerical variables using histograms and boxplots,
categorical variables using count plots, and relationships between
variables using scatter plots, correlation matrices, and heatmaps.

\### Bivariate Analysis: Analyzed relationships between numerical and
categorical variables using scatter plots, cross-tabulation heatmaps,
and box/violin plots.

\### Correlation Analysis: Computed the correlation matrix for numerical
variables and visualized it using a heatmap. Identified the top
correlations between variables.

\### Visualizations: Plotted various distributions for key variables
like loan_amnt, int_rate, grade, and term. Created scatter plots to show
the relationship between loan_amnt and int_rate, as well as box plots to
visualize the distribution of loan_amnt by grade.

\## Conclusions:

dataset contains 39,717 records with 111 columns.

\### Here is a brief summary:

Loan Amount (loan_amnt):

Range: 500 to 35,000

Mean: 11,219

25th Percentile: 5,500

75th Percentile: 15,000

Funded Amount (funded_amnt): Similar to loan amount, with a mean of
10,947.

Interest Rate (int_rate): 371 unique interest rates, most common is
10.99%.

Term: Either 36 months (29,096 loans) or 60 months.

Installment:

Mean: 324.56

Range: 15.69 to 1,305.19

Grade: Loans are categorized into seven grades (A to G), with B being
the most frequent.

\## Contact Created by \[@vishnusag\] - feel free to contact me!
