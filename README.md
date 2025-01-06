- Updated 1/6/2024

## Big Data Bowl 2025: Insights from Pre-Snap Data

This repository contains Python notebooks developed while exploring, preparing, preprocessing, and modeling the numerous datasets the Big Data Bowl (BDB) sponsors provided on the Kaggle platform. The nine weekly tracking datasets contain massive amounts of records that could not quickly be loaded and used in Kaggle. 

The process included:
- Exploring the data and looking for trends
- Preparing the data and preprocessing for aggregation
- Feature Engineering
- Encoding Data
- Systematically creating nine different aggregated data frames for each of the first nine weeks of the 2022 NFL season.
- Concatenating those nine data frames into a final aggregated data frame
- Performing predictive modeling by comparing XGBoost and LightGBM
- Bayesian Optimization was used for parameters

Findings:
- A prediction could be made if a play was a run play within 79.1% accuracy
- The LightGBM model performed best, with a ROC-AUC of 85.6%
- The testing classification report was promising, with above-average scores for precision, recall, and f1-score
- Using XGBoost Feature Importance, the most predictive features revolved around offensive formations, wide receiver alignment, tight end shifting, wide receiver motion, and most importantly running back depth.


