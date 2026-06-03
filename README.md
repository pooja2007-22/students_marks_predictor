# students_marks_predictor
Machine Learning model to predict student marks based on study hours, attendance, previous scores and other academic factors. Built with Python, Scikit-learn, and Streamlit for interactive predictions 
# PROBLEM STATEMENT

A machine learning project that predicts a student’s expected marks based on academic and behavioral inputs like study hours, attendance, previous test scores, and extracurricular activities.

## Project Objective
- Predicts marks for individual students using trained regression/classification models
- Handles multiple input features: study time, sleep hours, attendance %, previous marks, etc.
- Interactive web app built with Streamlit for real-time predictions
- Model evaluation with metrics: MAE, RMSE, R² Score
- Clean dataset preprocessing and feature engineering

## MODULE LIST
- **Language**: Python 3.10+
- **ML Libraries**: Scikit-learn, Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Web App**: Streamlit

## How It Works
1. Dataset is preprocessed and split into training/testing sets
2. Models like Linear Regression, Random Forest, or Gradient Boosting are trained
3. The best-performing model is saved using `joblib`
4. Streamlit app loads the model and takes user input to predict marks

## Usage
```bash
git clone <repo-url>
cd student-marks-predictor
pip install -r requirements.txt
streamlit run app.py
