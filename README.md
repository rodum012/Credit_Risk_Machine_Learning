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

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

### Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

### Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.

---

## Contributors

Robby Odum

Email: rodum012@gmail.com

---

## License

MIT