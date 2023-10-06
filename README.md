# Heart Disease Prediction

This is a Streamlit web application for predicting the likelihood of heart disease based on user-provided information. The application uses a trained model to make predictions.

## Prerequisites

Before running the application, ensure you have the required dependencies installed:

```bash
pip install scikit-learn pandas streamlit numpy
```
Clone this repository to your local machine:

```bash
git clone https://github.com/dhanush1109/Heart_Disease_Prediction.git
```
Place the trained model (the_model.pkl) file in the same directory as the app.py script.

# Installation

Before running the code, you'll need to make sure you have the required libraries installed. You can install them using the following commands:

```bash
pip install pandas numpy scikit-learn
```
Please ensure that you have the necessary dependencies installed before running the code.

After installing the required python modules run the model file
```bash
model.ipynb
```
After running this file we will get the following files
```bash
model.pkl
```
After that run the Streamlit app:

```bash
streamlit run app.py
```

This will launch a local development server and open the app in your default web browser.

# How to Use
1. Enter the proper detail which are asked in the webpage.

2. Click the "Predict" button to see the predicted result.

# Custom Styling
The app features custom CSS styles for the button. If you'd like to modify the styles, you can do so in the app.py file, where the CSS styles are defined in the markdown function.
