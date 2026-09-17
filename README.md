# Pranjal-Srivastava-202501100300186-MLE-CASESTUDY-1
Hospital Readmission Prediction Using Logistic Regression with L2 Regularization.
# Hospital Readmission Prediction

## Case Study

**Hospital Readmission Prediction using Logistic Regression with L2 Regularization**

## Objective

The main aim of this project is to develop a machine learning model that can predict whether a patient is likely to be readmitted to the hospital within 30 days based on their medical and demographic information.

## Dataset

The dataset consists of **2000 patient records**.

### Input Features

* Age
* Gender
* Blood Pressure
* Glucose Level
* Previous Hospital Visits
* Diagnosis

### Target Variable

* **0** – Patient is not readmitted
* **1** – Patient is readmitted

## Methodology

The project follows these steps:

1. Import and examine the patient dataset.
2. Remove the patient ID column as it does not contribute to prediction.
3. Separate the input features from the target variable.
4. Encode categorical features into numerical values.
5. Divide the dataset into training and testing sets.
6. Apply Logistic Regression with **L2 regularization** to train the model.
7. Predict readmission outcomes on the test data.
8. Measure model performance using Accuracy and ROC-AUC.
9. Analyze predictions using a Confusion Matrix.
10. Visualize model performance using an ROC Curve.

## Technologies and Tools

* **Python**
* **Pandas** – Data loading and preprocessing
* **Matplotlib** – Data visualization
* **Scikit-learn** – Machine learning and evaluation
* **Google Colab** – Development environment
* **GitHub** – Project hosting and version control

## Model Evaluation

The performance of the Logistic Regression model is assessed using:

* Accuracy
* ROC-AUC Score
* Confusion Matrix
* ROC Curve

These metrics help determine how effectively the model distinguishes between patients who are readmitted and those who are not.

## Clinical Consideration

In a healthcare prediction system, both false positives and false negatives are important.

A **false negative** means that the model fails to identify a patient who may be readmitted. This can be significant because the patient may not receive additional monitoring or follow-up care.

A **false positive** means that the model identifies a patient as high-risk when they are not actually readmitted. This could lead to unnecessary monitoring and additional use of healthcare resources.

Therefore, model performance should be evaluated not only by overall accuracy but also by considering the potential impact of both types of p
