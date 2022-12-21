# matplotlib_challenge

* In this challenge, a folder was created named matplotlib_challenge, which contains the main script for the jupyter notebook.
* The folder also contains a Resource folder which has the csv files used in the analysis.
* The folder also contains a Images folder which has the images of the charts plotted during the study.

# Summary

* For this analysis, dataset of 249 mice who were identified with SCC tumours and received treatment with a range of drug regimens were provided. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

* Initially the data provided was cleaned and prepared by dropping the duplicate values. Than a summary statistics dafaframe was created.
    
* A bar chart was plotted to show the total number of time points for all mice tested for each drug regimen throughout the study and a pie chart was plotted to show the distribution of female versus male mice in the study.
    
* Any potential outliers across all four treatment regimens were identified by consodering the tumour volume at the last timepoint for each mouse and a box plot was plotted to show the distribution of the final tumour volume for all the mice in each treatment group.
    
* The mouse ID s185 was chosen that was treated with the Capomulin drug and a a line plot was plotted to show trend of the tumour volume versus time point for s185.
    
* A scatter plot was plotted that shows the distribution of tumour volume versus mouse weight for the Capomulin treatment regimen.
    
* The correlation coefficient and r-squared value between mouse weight and average tumour volume for the Capomulin treatment was calculated and a linear regression model was plotted.

# Conclusion

* There is a positive correlation between the mouse weight and the average tumour volume for the mice treated with the drug Capomulin which indicates that as the weight of the mouse increases the tumour volume identified also increases.

* The distribution of male and female mice considered for this study is almost equal and hence it can be said to be a fair comparison.

* Only one outlier value could be found among the data set which indicates that the dataset provided is not contaminated.
