# Heart Disease Prediction

A machine learning project that predicts the likelihood of heart disease based on patient health-related features.

This project was developed as part of my machine learning practice to understand the complete workflow of data preprocessing, exploratory data analysis, model training, evaluation, and deployment using Flask.

## Project Overview

The goal of this project is to build a machine learning model that can classify whether a person is likely to have heart disease based on the provided health attributes.

The project includes:

- Exploratory Data Analysis (EDA)
- Data preprocessing and cleaning
- Feature scaling
- Machine learning model training
- Model evaluation
- Saving the trained model using Pickle
- Flask-based web application for predictions

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
- Flask
- HTML/CSS

## Machine Learning Workflow

1. Data collection and exploration
2. Data cleaning and preprocessing
3. Exploratory Data Analysis
4. Feature preparation
5. Train-test split
6. Feature scaling
7. Model training
8. Model evaluation
9. Model serialization
10. Flask integration

## Installation

Clone the repository:

```bash
git clone YOUR_REPOSITORY_URL
cd heart-disease-prediction
```

Create and activate a virtual environment:

```bash
python -m venv .venv
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Running the Application

Run the Flask application:

```bash
python app.py
```

Then open the local address displayed by Flask in your browser.

## Model

The trained model, scaler, and required feature information are stored inside the `model/` directory and loaded by the Flask application to generate predictions.

## Future Improvements

- Compare additional machine learning algorithms
- Perform hyperparameter tuning
- Improve model evaluation
- Improve the web interface
- Deploy the application publicly
- Add model explainability

## Disclaimer

This project is intended for educational and machine learning practice purposes only. It is not a medical diagnostic tool and should not be used for medical decision-making.