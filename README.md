Dataset : https://www.kaggle.com/datasets/arunavakrchakraborty/financial-payment-services-fraud-data


📌 1. Logistic Regression — Why I chose it:
I chose Logistic Regression as the baseline model because of its simplicity, interpretability, and effectiveness for binary classification tasks like fraud detection (where the outcome is either fraud or not fraud).

It assumes a linear relationship between the features and the log-odds of the outcome, which makes it efficient to train and understand. This model helps establish a benchmark performance, and because it is relatively quick to compute, it's useful during the initial stages of model selection to test the quality of feature engineering.

Even if it's not always the most accurate in complex datasets, its predictive probabilities, low computational cost, and clear coefficients make it valuable — especially when communicating results to non-technical stakeholders or domain experts.

📌 2. Decision Tree Classifier — Why I chose it:
I selected the Decision Tree Classifier because it can model nonlinear relationships and complex feature interactions, which are often present in real-world fraud patterns. Unlike Logistic Regression, it does not assume linearity or require feature scaling.

Decision Trees use a tree-like structure to split data based on conditions, making them highly interpretable — one can easily visualize how decisions are made. This makes them great for identifying decision rules in fraud detection, such as specific transaction types or thresholds that are more likely to indicate fraud.

Additionally, Decision Trees are robust to outliers and can handle both numerical and categorical data natively. In fraud detection tasks, where certain combinations of conditions may signal rare but important fraudulent events, trees can be particularly useful.

📌 Small and Clear Reason for Choosing Each:
1. Logistic Regression:
I chose Logistic Regression as a baseline model because it is simple, fast, and provides a good starting point for binary classification tasks like fraud detection.

2. Decision Tree Classifier:
I used Decision Tree because it can capture nonlinear patterns, is easy to interpret, and performs well when feature interactions are important.
