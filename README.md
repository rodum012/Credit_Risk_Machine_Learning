# Credit_Risk_Machine_Learning
A comparison of supervised learning models with and without oversampling that can be used to predict whether a loan is healthy or risky

---

## Technologies

This application is written in Python v. 3.9.7 and uses [JupyterLab](https://jupyter.org/) to deploy the code. This application makes use of
 the following libraries:


[pandas](https://pandas.pydata.org/docs/) was used for data collection, preparation, and analysis.

[numpy](https://numpy.org/doc/) was used for mathematical manipulation of data

[pathlib](https://docs.python.org/3/library/pathlib.html) was used to assist in importing csv data

[sklearn](https://scikit-learn.org/stable/) was used for machine learning modeling

[imblearn](https://imbalanced-learn.org/stable/) was used for oversampling operations

[warnings](https://docs.python.org/3/library/warnings.html) was used for warning control

---

## Installation Guide

Prior to running this application, perform the following in the command line to install the required libraries:

`pip install pandas`

`pip install jupyterlab`

`pip install numpy`

`pip install pathlib`

`pip install sklearn`

`pip install imblearn`

`pip install warnings`


---

## Usage

In order to launch the application, navigate to the Credit_Risk_Machine_Learning folder that contains all of the code for this application, and then type into the command line:

```
jupyter lab
```

Once in jupyter lab, open the credit_risk_resampling.ipynb and run each cell in the jupyter file to see the resulting anlysis.

---

## Credit Risk Analysis Report

### Overview of the Analysis

The purpose of this analysis was to compare a logistic regression supervised learning model on credit data both with and without utilizing oversampling. The model took in multiple different credit data of clients as well as if the loan was high risk or healthy in order for the model to attempt to predict whether future loans are healthy or risky based on their credit profile. The machine learning process began by creating a logistic regression model and fitting the model to the data. From there the model was able to make predictions on test data and was analyzed for accuracy using a confusion matrix. This process was then repeated with the model using data that was oversampled. 

### Results

* Machine Learning Model 1 (Logistic Regression):
  * Accuracy = 94.90%
  * Precision = 1.00 and 0.86 for healthy and risky loans respectively 
  * Recall = 1.00 and 0.90 for healthy and risky loans respectively 



* Machine Learning Model 2 (Oversampled Data Logistic Regression):.
  * Accuracy = 99.65%
  * Precision = 1.00 and 0.86 for healthy and risky loans respectively 
  * Recall = 0.99 and 1.00 for healthy and risky loans respectively

### Summary

The oversampled model performs best overall for both metrics with a higher accuracy score, better recall, and equally as good precision as the original model. Additionally, the original model is no better than guessing every loan is healthy, which would have yielded an accuracy of nearly 97%, while the oversampled model had an accuracy of 99.65%.

---

## Contributors

Robby Odum

Email: rodum012@gmail.com

---

## License

MIT