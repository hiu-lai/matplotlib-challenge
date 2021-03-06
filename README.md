# matplotlib-challenge

## Unit 5 Homework - Conclusion
1. Out of the 10 drug regimens in the study, mice recovers the best with Ramicane and Capomulins. This can be seen in our boxplot where the quartile and interquartile range are both relative low, this calculation is further supported by our line graph over timepoints comparing mice with the smallest tumor volume at timepoint 45 against each drugs. 80% of the drug regimens resulted the mice to have larger tumor volume than at the start.

![Comparison of tumor volume across 4 drug regimens](/Images/Comparison%20of%20tumor%20volume%20across%204%20drug%20regimens.png)

![Mice with smallest tumor vol per drug by timepoint](/Images/Mice%20with%20smallest%20tumor%20vol%20per%20drug%20by%20timepoint.png)

2. Propriva appears to be the worst drug out of the 10 tested, with the least mice surviving to timepoint 45. 
   24 mice started off on Propriva by timepoint 45, there was only 7 mice remaining. Surviving at 29.17% compares to 84% for Capomulin Regimens.

![Total timepoints by drugs regimen](/Images/Total%20timepoints%20by%20drugs%20regimen.png)

3. Correlation coefficient and linear regression model for mouse weight and average tumor volume for the Capomulin regimen are;

i.   Average Tumor Volume (mm3) = 0.95 x (Mouse Weight (g)) + 21.55   
ii.  r-squared of 0.7089    
r-squared at 0.7089 suggest moderate effective linear regression model.

![Scatterplot of ave Tumor Vol and Weight](/Images/Scatterplot%20of%20ave%20Tumor%20Vol%20and%20Weight.png)

Refer to and run \Pymaceuticals\pymaceuticals.ipynb for further analysis.
