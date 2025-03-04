# Heart-Disease-Prediction

## Overview

The **Heart Disease Prediction** project is a machine learning-based application that predicts the likelihood of heart disease in a patient based on various medical parameters. It uses historical health data to train predictive models and provide insights into potential risks.

## Features

- **User Input:** Accepts medical parameters such as age, blood pressure, cholesterol levels, etc.
- **Machine Learning Model:** Uses a trained model to predict heart disease risk.

## Technologies Used

- **Programming Language:** Python
- **Machine Learning Library:** Scikit-learn
- **Data Handling:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/sumantahitk/Heart-Disease-Prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Heart-Disease-Prediction
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the application:
   ```bash
   python app.py  # If using Flask
   streamlit run app.py  # If using Streamlit
   ```
2. Enter patient details in the input fields.
3. Get predictions on heart disease risk.

## Dataset

- The model is trained on a dataset containing medical records with heart disease indicators.
- Common features include age, sex, blood pressure, cholesterol, and more.

## Model

- The machine learning model is trained using classification algorithms such as Logistic Regression, Random Forest, or SVM.
- The model is evaluated using accuracy, precision, recall, and F1-score.


