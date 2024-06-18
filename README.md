# Integrated_Project

Contents:

PowerBi File:

Insurance Claims.pbix
- The main aim is to show what the attributes positive net value clients are so that the company can look to attract more of these clients and promote the insurance industry
- In SA there is a problem that not enough people are insured. By targeting customers that add positive_net_value, it also makes sure that the 
business is profitable in the long run.
- The dashboard is built off the 'Advanced Features Claims Data.csv' file below
- The Dashboard shows a summary page where one can select positive or negative net value customers and see what their attributes are
- There are two additional pages
- There is a page which shows which features are most influatial in whether a claim is fraudulent or not
- Another page is showing which features are most influential in showing if a customer is adding positive net value or not

Excel Files:

insurance_claims_raw.xlsx 
- This is the original dataset provided
insurance_claims_raw - Excel Clean.xlsx 
- This is where there excel analysis has been done
- Each Feature has been analysised to fill in missing values where needed most appropriately, using pivot tables and statistics where needed

CSV Files:

insurance_claims_cleaned_for_analysis.csv
- This CSV file is the result of the insurance_claims_raw - Excel Clean.xlsx file above
Advanced Features Claims Data.csv
- This is the result of the 'Advanced Features Claims Data.ipynb' file below

Jupyter Notebook files:

Advanced Features Claims Data.ipynb
- This notebook has code in it to create extra features and analyse the file 'insurance_claims_cleaned_for_analysis.csv'
- It creates the file 'Advanced Features Claims Data.csv'

Logistic_model_predicting_fraud.ipynb
- Consumes the Advanced Features Claims Data.csv file
- Builds a logistic model based on the features in the file to predict Fraud
- It shows the features most likely to cause fraud

Tree_Models_Predicing_Fraud.ipynb
- Consumes the Advanced Features Claims Data.csv file
- Builds a Random Forest model based on the features in the file to predict Fraud
- It shows the features most likely to cause fraud

Log_model_Predicting_Positive_Net_Value.ipynb
- Consumes the Advanced Features Claims Data.csv file
- Builds a logistic model based on the features in the file to predict a Positive Net Value Customer
- It shows the features most likely to cause a Positive Net Value Customer


Tree_Model_Predicting_Positive_Net_Value.ipynb
- Consumes the Advanced Features Claims Data.csv file
- Builds a logistic model based on the features in the file to predict a Positive Net Value Customer
- It shows the features most likely to cause a Positive Net Value Customer



