# CreditRisk_Supervised
## Loan Status Prediction using Logistic Regression

This repository contains Python code for a machine learning analysis that predicts loan status based on financial information using the Logistic Regression model. The analysis involves loading the loan dataset, preprocessing the data, training the Logistic Regression model, and evaluating its performance.

### Dataset

The dataset used for this analysis is provided in the `Resources` folder and is named `lending_data.csv`. It contains information on loans, including features related to financial information and the loan status as the target variable.

### Prerequisites

To run the code in this repository, you need the following prerequisites:

- Python 3.x
- Pandas
- NumPy
- scikit-learn

You can install the required Python libraries using pip:

~~~
pip install pandas numpy scikit-learn
~~~

- Usage    
    
Clone this repository to your local machine using the following command:

~~~
git clone https://github.com/your-username/loan-status-prediction.git
~~~

Change into the project directory:

~~~
cd loan-status-prediction
~~~

Run the loan_status_prediction.py script:

~~~
python loan_status_prediction.py
~~~
    
The script will load the dataset, preprocess the data, split it into training and testing sets, train the Logistic Regression model, and evaluate its performance using accuracy, precision, and recall metrics.
- Results    
Using the Logistic Regression model, here are the performance scores for both classes:

Machine Learning Model 1 (Logistic Regression):    
Balanced Accuracy: 0.94    
Precision (low/no risk): 1.00   
Precision (high risk): 0.87    
Recall (low/no risk): 1.00    
Recall (high risk): 0.89    
<br>
- Summary    
Based on the evaluation of the machine learning model, the Logistic Regression model (Model 1) demonstrated strong performance in predicting loan status. The model achieved an impressive balanced accuracy of 0.94, indicating its ability to make accurate predictions for both low/no risk and high-risk loans.

The precision score for the 'low/no risk' class is 1.00, indicating that when the model predicts a loan as low/no risk, it is almost always correct. However, the precision for the 'high risk' class is 0.87, implying that there is room for improvement in correctly identifying high-risk loans.

The recall score for the 'low/no risk' class is also 1.00, suggesting that the model can identify almost all of the actual low/no risk loans correctly. The recall for the 'high risk' class is 0.89, indicating that the model can capture a considerable portion of the high-risk loans but may miss some.

Considering the high accuracy, precision, and recall scores, the Logistic Regression model appears to be well-suited for predicting loan status based on the available financial information.
