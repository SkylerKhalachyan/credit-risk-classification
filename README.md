# credit-risk-classification
#
### Credit Risk Analysis Report 
#
This supervised machine learning model was built to identify the creditworthiness of borrowers. Historical lending activity data from a peer-to-peer lending services company was classified to predict outcomes on new data.  

Logistic Regression Model with the Original Data
* Accuracy Score
     * 0.94
* Precision Score
     * Healthy Loan: 1.00
     * High-Risk Loan: 0.87
* Recall Score
     * Healthy Loan: 1.00
     * High-Risk Loan: 0.89

Logisitic Regression Model with Resampled Training Data
* Accuracy Score
     * 0.99
* Precision Score
     * Healthy Loan: 1.00
     * High-Risk Loan: 0.87
* Recall Score
     * Healthy Loan: 1.00
     * High-Risk Loan: 1.00

The logisitic regression model with the original data predicts the healthy loan label perfectly. The goal is to have a score as close to 1.00 as possible. This one scored perfectly. The logistic regression model predicts the high-risk loan label very well. For a good reading, you want to score betweeen 0.85-0.95. The model lands right there with scores of 0.87, 0.89, and 0.88 for precision, recall, and f1-score respectively. 

The logisitic regression model with resampled training data predicts the healthy loan label perfectly. The goal is to have a score as close to 1.00 as possible. This one scored perfectly. The logistic regression model predicts the high-risk loan label very well. For a good reading, you want to score betweeen 0.85-0.95. The model lands right there with scores of 0.87, 1.00, and 0.93 for precision, recall, and f1-score respectively. 

When we resampled our data, the accuracy score imporved, precision stayed the same, and our recall score improved as well. Overall I would reccomend this model due to it's great scoring across all performance measures. 


### Built With:
#
* [![Scikit Logo](Credit_Risk/Resources/Images/Scikit_Learn_Logo.jpg? "Scikit logo")](https://scikit-learn.org/stable/)
* [![Jupyter Logo](Credit_Risk/Resources/Images/Jupyter_logo.png "Jupyter logo")](https://jupyter.org/)
* [![Python Logo](Credit_Risk/Resources/Images/python_logo.png "python logo")](https://www.python.org/)

  
### User Set Up
#
To create a copy ready to perform on your local computer follow these simple steps.

#### Prerequisites
For this project, you will use the below-listed Python libraries. If you do not have these libraries installed in your virtual environment, run the codes provided to do so. 
* hvplot

```

conda install -c pyviz hvplot

```

#### Installation
1. Install the above package.


### Usage
# 
* Evaluate a model based on loan risk.
### Acknowledgements
#
* Author: [Skyler Khalachyan](https://github.com/SkylerKhalachyan)
* Contributors:
     - Study Groups: Collaborated with the Instructor and multiple students during class time to better understand the project.
     - Program: UC Berkeley Extension Data Analytics Bootcamp 
     - Starter Code:  Some starter code was provided
     - Instructor: [Ahmad Sweed](https://github.com/ahmadswd) 

