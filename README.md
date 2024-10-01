# Customer Complaint Classification Project

## Business Goal
The primary objective of this project is to build a model that classifies customer complaints based on products and services. By accurately segregating these tickets into relevant categories, we can facilitate quicker resolutions for issues reported by customers.

## Project Overview
You will be conducting topic modeling on the provided `.json` data from the company. Since the data is not labeled, you will apply Non-negative Matrix Factorization (NMF) to analyze patterns and classify tickets into five clusters corresponding to the following product/service categories:

- Credit Card / Prepaid Card
- Bank Account Services
- Theft / Dispute Reporting
- Mortgages / Loans
- Others

Using topic modeling, each ticket can be mapped to its respective department or category. This data can subsequently be utilized to train supervised models (e.g., Logistic Regression, Decision Tree, or Random Forest) for classifying new customer complaint support tickets.

## Metrics
The following metrics will be used to evaluate the models:

| Metric                                   | Multinomial Naive Bayes | Logistic Regression | Decision Tree Classifier | Random Forest Classifier | Multinomial Naive Bayes with GridSearchCV | Logistic Regression with GridSearchCV | Decision Tree Classifier with GridSearchCV | Random Forest Classifier with GridSearchCV |
|------------------------------------------|--------------------------|---------------------|-------------------------|-------------------------|-------------------------------------------|----------------------------------------|----------------------------------------------|---------------------------------------------|
| ROC_AUC Score (Train)                   | 0.95                     | 1.00                | 1.00                    | 1.00                    | 0.98                                      | 1.00                                   | 0.97                                         | 0.99                                        |
| ROC_AUC Score (Test)                    | 0.93                     | 0.99                | 0.85                    | 0.98                    | 0.95                                      | 0.99                                   | 0.94                                         | 0.97                                        |
| Accuracy (Train)                         | 0.68                     | 0.95                | 1.00                    | 1.00                    | 0.85                                      | 0.94                                   | 0.81                                         | 0.85                                        |
| Accuracy (Test)                          | 0.64                     | 0.90                | 0.76                    | 0.83                    | 0.76                                      | 0.93                                   | 0.77                                         | 0.77                                        |
| Precision (Train)                        | 0.76                     | 0.95                | 1.00                    | 1.00                    | 0.85                                      | 0.94                                   | 0.81                                         | 0.86                                        |
| Precision (Test)                         | 0.72                     | 0.90                | 0.76                    | 0.84                    | 0.76                                      | 0.93                                   | 0.77                                         | 0.80                                        |
| Recall (Train)                           | 0.68                     | 0.95                | 1.00                    | 1.00                    | 0.85                                      | 0.94                                   | 0.81                                         | 0.85                                        |
| Recall (Test)                            | 0.64                     | 0.90                | 0.76                    | 0.83                    | 0.76                                      | 0.93                                   | 0.77                                         | 0.77                                        |
| F1-Score (Train)                        | 0.66                     | 0.95                | 1.00                    | 1.00                    | 0.85                                      | 0.94                                   | 0.81                                         | 0.84                                        |
| F1-Score (Test)                         | 0.61                     | 0.90                | 0.76                    | 0.83                    | 0.75                                      | 0.93                                   | 0.77                                         | 0.76                                        |

## Pipelines to be Performed
The following eight major tasks need to be completed for this assignment:

1. Data Loading
2. Text Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Extraction
5. Topic Modeling
6. Model Building using Supervised Learning
7. Model Training and Evaluation
8. Model Inference

## Getting Started
1. Clone the repository.
2. Install the required dependencies listed in `requirements.txt`.
3. Run the `main.py` script to execute the complete workflow.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue for discussion.

## License
This project is licensed under the MIT License.

## Contact
For further inquiries or discussions, feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/jitesh-rathod/).
