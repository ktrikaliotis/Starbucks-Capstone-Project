# Starbucks-Capstone-Project

## Introduction
This is the final project of the Udacity Machine Learning Engineer Nanodegree Program.

This data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks.

Not all users receive the same offer, and that is the challenge to solve with this data set.

The task is to combine transaction, demographic and offer data to determine which demographic groups respond best to which offer type. This data set is a simplified version of the real Starbucks app because the underlying simulator only has one product whereas Starbucks actually sells dozens of products.

## Introduction
* data - folder with all relevant input data and all saved datasets
* merged_df_report.html - pandas profiling report for the merge dataframe
* offer_summary.csv - offer summary dataframe saved from the final notebook
* portfolio_report.html - pandas profiling report for the portfolio dataframe
* profile_report.html - pandas profiling report for the profile dataframe
* starbucks-capstone-notebook.html - notebook to generate all the results in html format
* starbucks-capstone-notebook.ipynb - summary notebook to generate all the results
* transcript_report.html - pandas profiling report for the transcript dataframe

## Setting up the environment
**Datasets**

After downloading or cloning this repository, the only datasets needed to run the notebook are the three main datasets in the data folder:
* portfolio.json
* profile.json
* transcirpt.json

**Libraries / Systems**
* AWS Sagemaker
* pandas_profiling
* numpy
* pandas
* json
* math
* sklearn
* seaborn
* os
* matplotlib

## License
[MIT](https://choosealicense.com/licenses/mit/)