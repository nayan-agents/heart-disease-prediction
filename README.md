# Heart Disease Prediction

A machine learning project that predicts the likelihood of heart disease based on patient health-related features.

This project was developed as a learning project to understand and implement an end-to-end machine learning workflow, including data preprocessing, exploratory data analysis, model training, evaluation, and building an interactive prediction application using Streamlit.

## Project Overview

The goal of this project is to build a machine learning model that can predict whether a person is likely to have heart disease based on the provided health attributes.

The project covers:

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature preparation
- Feature scaling
- Machine learning model training
- Model evaluation
- Saving the trained model and preprocessing components
- Building an interactive web application using Streamlit

## Project Structure

```text
heart-disease-prediction/
│
├── data/
│   ├── heart_raw.csv
│   └── final_df2.csv
│
├── model/
│   ├── heart_columns.pkl
│   ├── heart_scaler.pkl
│   └── LRG_heart_model.pkl
│
├── notebooks/
│   └── Heart_Disease_analysis.ipynb
│
├── app.py
├── requirements.txt
├── .gitignore
└── README.md
```

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook
- Streamlit
- Pickle

## Machine Learning Workflow

1. Data exploration
2. Data cleaning and preprocessing
3. Exploratory Data Analysis
4. Feature preparation
5. Train-test split
6. Feature scaling
7. Model training
8. Model evaluation
9. Saving the trained model
10. Streamlit application integration

## Installation

Clone the repository:

```bash
git clone YOUR_REPOSITORY_URL
```

Navigate to the project directory:

```bash
cd heart-disease-prediction
```

Create a virtual environment:

```bash
python -m venv .venv
```

Activate it on Windows:

```bash
.venv\Scripts\activate
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Running the Application

Start the Streamlit application:

```bash
streamlit run app.py
```

Streamlit will provide a local URL that you can open in your browser.

## Model Files

The `model/` directory contains the trained machine learning model and preprocessing components required by the application:

- `LRG_heart_model.pkl` — trained prediction model
- `heart_scaler.pkl` — fitted feature scaler
- `heart_columns.pkl` — feature information required for prediction

These files are loaded by `app.py` when generating predictions.

## Future Improvements

- Compare additional machine learning algorithms
- Perform hyperparameter tuning
- Add model explainability
- Improve the Streamlit user interface
- Deploy the application publicly

## Disclaimer

This project was created for educational and machine learning practice purposes only. It is not intended to provide medical diagnoses or replace professional medical advice.