# Loan-Status-Classification

## Objective
In this project we are going to find the most accurate ML Classifier Algorithm whcih will be used to predict the Loan Status for new or unkown users.

## Data Description
We are going to use a historical Loans data to predict the new\unkown users. 
We will use the [Loan_train.csv](https://raw.githubusercontent.com/YousefMajadbi/Loan-Status-Prediction/main/loan_train.csv) dataset to train and fit our model.
And use the [Loan_test.csv](https://raw.githubusercontent.com/YousefMajadbi/Loan-Status-Prediction/main/loan_test.csv) dataset to test and evaluate our built model.

Dataset includes details of 346 customers whose loan are already paid off or defaulted. It includes following fields:

| Field          | Description                                                                           |
| -------------- | ------------------------------------------------------------------------------------- |
| Loan_status    | Whether a loan is paid off on in collection                                           |
| Principal      | Basic principal loan amount at the                                                    |
| Terms          | Origination terms which can be weekly (7 days), biweekly, and monthly payoff schedule |
| Effective_date | When the loan got originated and took effects                                         |
| Due_date       | Since it’s one-time payoff schedule, each loan has one single due date                |
| Age            | Age of applicant                                                                      |
| Education      | Education of applicant                                                                |
| Gender         | The gender of applicant                                                               |

## Methodology
- Data Analysis.
- Data Visualization.
- Data Preprocessing
  - Import Dataset & Libraries.
  - Data Cleaning.
  - Convert Categorical Variables to Numerical values.
  - Feature Selection.
  - Feature Engineering \ Normalization. 
- Classification
  - K Nearest Neighbor (KNN).
  - Decision Tree.
  - Support Vector Machine.
  - Logistic Regression.
- Model Evaluation.

## Technologies
- Jupyter Notebook.
- Python.
- pandas.
- Numpy.
- Matplotlib.
- Seaborn.
- Sklearn.

## Results
By using the below **Evaluation Metrics** we see that **SVM** model is the most suitable model to be used to predict the loan status for the new or unkonw users.

<table align="left" style="width: 40%">
  <tr align="left">
    <th>Algorithm</th>
    <th>Jaccard</th> 
    <th>F1-Score</th>
    <th>LogLoss</th>
  </tr>
  <tr>
    <td>KNN</td>
    <td>0.65</td>
    <td>0.63</td>
    <td>NA</td>
  </tr>
  <tr>
    <td>Decision Tree</td>
    <td>0.66</td>
    <td>0.74</td>
    <td>NA</td>
  </tr>
  <tr>
    <td>SVM</td>
    <td>0.78</td>
    <td>0.76</td>
    <td>NA</td>
  </tr>
  <tr>
    <td>Logistic Regression</td>
    <td>0.74</td>
    <td>0.66</td>
    <td>0.57</td>
  </tr>
</table>
<br>
<br>
<br>
<br>
<br>
