# Credit_Risk_Analysis

## Overview

Using a dataset containing individual credit loan information, a variety of different supervised machine learning models designed for unbalanced classification were fitted to the data. Each model then predicted credit risk and the performance of these models were evaluated for their accuracy  

## Results

*BAS is the Balanced Accuracy Score 
<br><br>

### Cluster Centroids<br>
BAS = 0.60, high Precision but low Recall

![](https://github.com/alexlieberman22/Credit_Risk_Analysis/blob/main/Images/Undersample.PNG)

### SMOTE<br>
BAS = 0.60, high Precision but low Recall

![](https://github.com/alexlieberman22/Credit_Risk_Analysis/blob/main/Images/SMOTE.PNG)

### SMOTEEN<br>
BAS = 0.60, high Precision but low Recall

![](https://github.com/alexlieberman22/Credit_Risk_Analysis/blob/main/Images/SMOTEEN.PNG)

### Random Over Sampler<br> 
BAS = 0.64, high Precision but low Recall

![](https://github.com/alexlieberman22/Credit_Risk_Analysis/blob/main/Images/Oversample.PNG)

### Balanced Random Forest<br>
BAS = 0.79, high Precision and high Recall

![](https://github.com/alexlieberman22/Credit_Risk_Analysis/blob/main/Images/Balanced_Random_Forest.PNG)

### Easy Ensemble<br>
BAS = 0.92, high Precision and very high Recall

![](https://github.com/alexlieberman22/Credit_Risk_Analysis/blob/main/Images/EasyEnsemble.PNG)

## Summary

The best preforming model and the one to use would be the Easy Ensemble model. All other models except Balanced Random Forest preformed far less accurately predicting far too many good credit loans as risky. Only Easy Ensemble had a sensible number of false positives.
