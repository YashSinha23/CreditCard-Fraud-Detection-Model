# Credit Card Fraud Detection

## Project Overview
This project aims to detect fraudulent credit card transactions using machine learning techniques. The workflow includes data preprocessing and exploration, handling imbalanced data, feature scaling, model training and evaluation, followed by exporting the final model.

## Steps

### 1. Data Preprocessing and Exploration
- Cleaned data by handling missing values and outliers.
- Conducted exploratory data analysis to understand feature distributions and relationships.
- Identified important features correlated with fraud through correlation analysis.

### 2. Handling Imbalanced Data
- Applied undersampling to balance the dataset by reducing the number of majority class samples.

### 3. Feature Scaling
- Used `StandardScaler` to normalize the data, ensuring all features contribute equally to the model.

### 4. Model Training and Evaluation
- Implemented models including Random Forest Classifier, Isolation Forest, and Random Forest with undersampled data.
- Evaluated models using accuracy, F1-score, ROC AUC, and confusion matrix to select the best-performing model.

### 5. Model Exporting
- Exported the final model using `pickle` for deployment.

## Repository Structure
- `CodeNotes.ipynb` : Jupyter Notebook containing the code used to build this model
- `model.pkl` : Trained model saved a .pkl file ready for Deployment

## DataSet
The dataset used in this project is a Public dataset availaible on Kaggle :
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

## Conclusion
This project demonstrates the use of machine learning for detecting credit card fraud, providing a robust model that can be integrated into financial systems to enhance fraud detection capabilities.
