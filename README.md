# Predicting Active Membership in a Bank using Artificial Neural Networks

Objective:
This project utilizes artificial neural networks (ANNs) to predict whether a customer of a bank is an active member based on demographic and financial variables.

Dataset:
The dataset includes the following variables for each customer:

Geography: Country of residence.
CreditScore: Numerical measure of creditworthiness.
Age: Age of the customer.
Tenure: Number of years with the bank.
Balance: Account balance.
NumOfProducts: Number of bank products used.
Has Credit Card: Binary indicator (1 = Yes, 0 = No).
Is Active Member: Binary target variable (1 = Yes, 0 = No).
Methodology:

Data Preprocessing:

Cleaning and handling missing data.
Encoding categorical variables like "Geography" and "Has Credit Card".
Model Architecture:

Designed and implemented an ANN using TensorFlow/Keras.
Input layer for encoded variables.
Hidden layers with ReLU activation functions.
Output layer with sigmoid activation to predict active membership probability.
Training and Evaluation:

Split dataset into training and validation sets.
Trained the model using binary cross-entropy loss and Adam optimizer.
Evaluated model performance using metrics like accuracy, precision, recall, and F1-score.
Results:

Achieved [mention accuracy/recall/precision/F1-score].
Identified key variables influencing active membership prediction.
Deployment:
The trained model is ready for deployment in production environments to predict whether new customers are likely to become active members, aiding in customer retention strategies.

Conclusion:
This project demonstrates the application of ANN in predicting customer behavior in banking, providing insights for improving customer engagement and retention.
