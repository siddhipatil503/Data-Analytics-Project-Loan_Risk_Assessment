# Data-Analytics-Project-Loan_Risk_Assessment
LOAN DEFAULT RISK ASSESSMENT 

1.ABOUT THE PROJECT
This project aims to predict whether a borrower will be able to repay a loan based on various 
criterions similar to that of the FICO scores. Credit based risks are very common for investors
and banks alike and here we aim to reduce such risks through predictive analysis.
We've compared 5 different machine learning models for the same.

2.ABOUT THE DATASET
The dataset we have chosen is from a peer to peer lending website called Lending club , based in
San francisco. Though it has been discontinued the datasets are available on www.kaggle.com
This particular dataset consisted of 27 columns and over 3.9 lakh entries.
The data attributes were broadly of two types
	1.Loan describing
	2.Borrower attributes

3.OUR STRATEGY
The main focus of our project was to accurately predict the 'Loan_status' of any entry.
This could be 'charged off'or 'fully paid'.For this classification problem we employed 5 models,
ANN, SVC, Random Forest,Logistic Regression and XGBoost.

4.STEPS TO RUN THE CODE
To run the code on Google collab you can directly click on the ipynb file (all graphs are visible at this checkpoint)
 or :
	1. Download the ipynb file, as well as the dataset csv file
	2. Upload the notebook on Google collab, add the dataset in the files section (left hand side)
	3. Update the 2nd cell data = pd.read_csv("add dataset location")
	4. Run All

5.CONCLUSION
Consequently, it was concluded that the best model in terms of overall accuracy was Artificial Neural Network,
more precisely Dense Neural Network with Dropout (Deep Learning).
While in terms of speed and confusion matrix metrics XGBoost is superior.

