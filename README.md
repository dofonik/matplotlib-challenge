# matplotlib-challenge
Module 5 Challenge - UWA Data Analytics Bootcamp

DESCRIPTION:
Within the Pymaceuticals file there is the pymaceuticals.ipynb which contains the main code, as well as pymaceuticals_starter.ipynb which contains the sample solutions and template provided for this analysis.

In the 'data' file, there are two csv files which contain our raw data.

The main code first reads in the csv files data and merges it into a pandas DataFrame.

It checks the number of unique mouse IDs and detects 249 mice.

Duplicates are then found, stored seperately and the original DataFrame is cleaned of any row containing a mouse that has duplicate data.

Checking the number of unique mouse IDs shows 248 mice and the data of 1 mouse has been removed.

Summary statistics are calculated for each drug regimen and stored in a DataFrame.

Bar charts are created for the number of rows (data) for each drug regimen.

Pie charts are created showing the distribution of mouse genders.

A box plot is created showing the distribution for 4 of the drug regimens, with outliers shown.

A line chart is created showing the Tumor Volume vs Time Point for a Mouse on Capomulin.

A scatter plot is created demonstrating Mouse Weight vs Average Tumor Volume (Capomulin Drug Regimen).

A linear regression is calculated and plotted on top of the scatter plot with a Correlation Coefficient between mouse weight and the average tumor volume being 0.84.

pandas.DataFrame.corr refernce:
https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.corr.html

scipy.stats.linregress reference:
https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.linregress.html