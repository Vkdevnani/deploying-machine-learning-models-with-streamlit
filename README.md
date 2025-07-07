# deploying-machine-learning-models-with-streamlit
A simple and interactive machine learning app that predicts house prices based on size (sqft) using Streamlit and Linear Regression.

# House Price Predictor

This project is a simple machine learning web application built with **Streamlit**. It predicts house prices based on input size (in square feet) using a Linear Regression model trained on synthetic data.

# Features
- Trains a linear regression model on synthetic housing data
- Accepts user input for house size
- Predicts the price instantly
- Visualizes the input prediction on a scatter plot using Plotly

# Technologies Used
- Python
- scikit-learn
- pandas
- numpy
- Streamlit
- Plotly

# How to Run Locally

```bash
pip install -r requirements.txt
streamlit run model_app.py
