# Telephonic-Deposit-Predictor

This repository houses a predictive modeling project aimed at assisting a retail banking institution in optimizing their telephonic marketing campaigns for term deposit subscriptions. Term deposits are a significant revenue source, and the goal is to identify potential clients likely to subscribe, enabling targeted outreach efforts.

### Problem Statement:

- The bank employs various outreach strategies, including telephonic marketing.
- Telephonic campaigns are effective but resource-intensive, necessitating targeted identification of potential subscribers.
- Client data, call details, and outcomes are provided for training a predictive model.

### Data:

1. train.csv: Dataset for training the model, including client details, call information, and the target variable "subscribed."
2. test.csv: Test dataset to predict new clients' subscription likelihood using the trained model.

### Data Dictionary:

- Various features including client age, job type, marital status, education, communication type, contact duration, and previous campaign outcomes.
- Target variable: "subscribed" indicating whether the client subscribed to a term deposit.

### Evaluation Metric:

- Accuracy is the evaluation metric for this project.

### Solution Checker:

- Utilize "solution_checker.xlsx" to generate accuracy scores for predictions on the test dataset.

### How to Use:

1. Train your model using "train.csv."
2. Use the trained model to predict term deposit subscriptions on "test.csv."
3. Save predictions in a new CSV file and use "solution_checker.xlsx" to generate accuracy scores.

Explore the baseline Python Notebook provided to kickstart your project.
