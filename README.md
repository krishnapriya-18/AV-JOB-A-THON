# AV-JOB-A-THON
Cross-Sell Prediction

Link to Hackathon: https://datahack.analyticsvidhya.com/contest/job-a-thon/#LeaderBoard

#### The aim of this notebook was just to extract maximum features from the data.

#### If it would be to get a higher rank / productionalizing the model, then the following things would be added to the notebook:

#### 1) All the imputation and interaction features would be made twice for the train set and test set. Just repeating the codes twice.
#### 2) All the aggregated features were made on combined data, they should be made separately on the train and test set, in this case, you just need to repeat the cell which has the code for aggregated features twice with df_train and df_test instead of df_total.
    This would ensure two things, no data leakage and as the newer test data comes, first the features will be made for that and then the model would predict.
#### 3) Feature selection and removing correlated features.
#### 4) Parameter tuning on the training set.
#### 5) Ensemble with different models if permitted.

# Private Rank: 10
# Public Rank: 15
