# cs4100_final_proj
NCAA AI Project Notes
Outline:
Scrape NBA win shares and corresponding college statistics from basketball reference starting at 2009 draft

First basic stats
Add advanced 
Add positions/one hot encoding 
Add metadata
Add Recursive Feature elimination
Training set: 2009 - 2018 (~45 collegiate players * 10 years = 450 data points)
Testing set: 2019 - 2022


BBall Ref NBA Stats
BBall Ref College Stats
Other Vars:
Height
Weight
Position 
Wingspan
Age
College (one-hot-encoding)
Strength of Schedule 

Target Variable Choices:
- Win Shares
- Win Shares Per 48
- VORP
- BPM

Potential Algorithms: 
XGBoost
Random Forest
Decision Tree
AdaBoost Ensemble
Multi-Layer Perceptron
Linear

Feature Selection: 
Recursive Feature Elimination 
Boruta

