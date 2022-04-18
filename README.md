# Credit_Risk_Analysis
## Overview
This project used six different machine learning models in order to see which one faired best when it came to prediciting credit fraud. Loans were labeled as either low risk or high risk. 
## Results
. The random oversampler model had an overall accuracy score of .64. Its precision score was .99 and its recall score was .66
. The SMOTE model's accuracy score was .65. Its precision score was .99 and its recall was .69
. The SMOTEENN model had an accuracy .64. Its precision score was .99 and its recall score was .57
. The BalancedRandomForestClassifier model had an accuracy score of .79. Its precision was .99 and its recall was .87
. The EasyEnsembleClassifier's accuracy score was .92, the best of any tested. Its precision score was .99 and its recall was .90
## Summary
Based on these results, the best model to use to detect credit fraud is the EasyEnsembleClassifier. While probably not quite good enough on its own it does the best job of any of the models at picking out which loans are likely at risk.
