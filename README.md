# Credit_Risk_Analysis
## Overview
The purpose of this analysis was to use machine learning models to predict credit risk with Python. Oversample analysis using RandomOverSampler and SMOTE. Undersample analysis using ClusterCentroids. There was a combination analysis using SMOTEENN. There also was a comparison of analysis using BalancedRandomForestClassifier and EasyEnsembleClassifier.

## Results
RandomOverSampler
- Balacnced accuracy is 65%.
- The precision is 99%.
- The recall is 69%.

SMOTE 
- Balacnced accuracy is 62%.
- The precision is 99%.
- The recall is 64%.

ClusterCentroids
- Balacnced accuracy is 62%.
- The precision is 99%.
- The recall is 45%.

SMOTEENN
- Balacnced accuracy is 51%.
- The precision is 99%.
- The recall is 58%.

BalancedRandomForestClassifier
- Balacnced accuracy is 77%.
- The precision is 99%.
- The recall is 88%.

EasyEnsembleClassifier
- Balacnced accuracy is 92%.
- The precision is 99%.
- The recall is 94%.

## Summary
If one of these models had to be used I would recommend the EasyEsmembly. Although this model could be faulty, it was the best at predictiting high-risk credit. I do not think there would ever be a perfect model but know what matters most to the business could help make that decision.
