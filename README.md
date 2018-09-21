# home_credit_default_risk_emplay
The code is written using the jupyter notebook and the score is submitted as such via email.

# approach to the problem
1) I downloaded and set up an environment on vmware for python and data analysis on kali os.
2) then performed EDA (exploratory data analysis) on the data to make sense and find patterns in the data.
3) then i installed jupyter notebook for easier use and also made a kaggle API token.
4) open a local jupyter server and started a  notebok where after the initial EDA, i performed basic feature engineering by only taking numeric data columns and built a model and trained it.
5) after the training was complete, i tested it against the test data given to get the approximate values for the repayment of loans for each given SK_ID in the file.
6) the results were stored in the csv file and submitted to kaggle for the scores.

# references
1) https://www.datacamp.com/community/tutorials/kaggle-machine-learning-eda
2) https://www.datacamp.com/community/tutorials/kaggle-tutorial-machine-learning

# notes
1) i didnt take into the account for the over-fitting of the data yet.
2) minimal feature engineering model but robust.

# Update
1)after some feature engineering the score is improved, kindly check the following jupyter notebook in the repo.
home_default_risk_feature_engg.ipnyb

# packages used
1) XGBoost 
2) numpy
3) pandas
4) matplot
5) jupyter notebook
