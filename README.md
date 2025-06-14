# Heart-issue-Detection-system
Jupyter Notebook project that predicts heart disease using logistic regression on clinical data. Built with scikit-learn, pandas, and NumPy.

# Heart Disease Detection System

This project is a machine learning-based heart disease prediction system developed using Python and scikit-learn. It uses clinical features to predict whether a person is likely to have heart disease. The model is trained on the popular UCI Heart Disease dataset and achieves strong accuracy and performance.

## Features

- Uses Logistic Regression for binary classification
- Predicts heart disease presence based on 13 clinical parameters
- Evaluates performance with Accuracy, Confusion Matrix, and ROC AUC
- Clean and interpretable code using Jupyter Notebook
- Real-time prediction with custom user inputs

## Dataset

- **Source:** UCI Machine Learning Repository – Heart Disease Dataset  
- **Link:** [UCI Dataset](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/ReminJoby/Heart-issue-Detection-system.git
   cd Heart-issue-Detection-system
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
3. Open and run the Jupyter Notebook:
   ```bash
   jupyter notebook Heart-issue detection system.ipynb
4. Replace input_data at the end of the notebook to test predictions with your own values.

## Model Evaluation

- Training Accuracy: ~84%
- Test Accuracy: ~81%
- ROC AUC Score: Evaluates model's ability to distinguish between classes.
- Confusion Matrix: Provides insight into false positives/negatives.

## Future Scope

- Add support for advanced models (e.g., Random Forest, XGBoost).
- Deploy as a web application using Flask or Streamlit.
- Incorporate additional medical features for better predictions.

## Requirements

See `requirements.txt` for dependencies.
