# Heart-Disease-Predictor

The Heart Disease Prediction Model in the Jupyter Notebook (HeartDiseasePredictor.ipynb) is a machine learning pipeline designed to predict whether a person has heart disease based on various health attributes.

Process Overview:
Data Preprocessing:

The dataset is loaded and cleaned. Missing values are handled, and features such as age, cholesterol, and blood pressure are scaled for consistency. Categorical features (like chest pain type) are encoded into numerical values.
Model Training:

Four machine learning models are trained using the dataset:
Logistic Regression
Random Forest Classifier
Support Vector Machine (SVM)
Gradient Boosting Classifier
These models are trained to predict heart disease (binary classification: 1 for disease, 0 for no disease).
Model Evaluation:

The models are evaluated using accuracy, precision, recall, and F1-score. The best-performing model is selected based on these metrics.
Saving the Best Model:

The best model is saved to a .pkl file using joblib for future use in making predictions.
This approach ensures that the model with the best performance is used to predict heart disease, providing accurate and reliable results for healthcare applications.
