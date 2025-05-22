#  Flight Price Prediction

This project predicts the price of flight tickets based on features such as airline, source, destination, duration, and more. It includes a complete machine learning pipeline — from data preprocessing and model training to deployment using Flask.

##  Project Overview

The goal of this project is to build a regression model that can predict flight ticket prices using structured data. The project covers:

- Data cleaning and preprocessing
- Feature engineering
- Model training (Random Forest)
- Model evaluation
- Web interface using Flask
- Deployment files (Heroku-ready)

##  Project Structure

├── app.py # Flask application file

├── FlightPricePred.ipynb # Model training and analysis notebook

├── flight_rf.pkl # Trained Random Forest model

├── requirements.txt # Python dependencies

├── templates/ # HTML templates for Flask frontend

├── static/css/ # CSS styling

├── Data_Train.xlsx # Training dataset

├── Test_set.xlsx # Test dataset

├── Sample_submission.xlsx


## Model

- **Algorithm:** Random Forest Regressor
- **Libraries used:** pandas, numpy, sklearn, seaborn, matplotlib

## Frontend

- Built using Flask with basic HTML/CSS for prediction input and results.

## How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/himanshisharmaa/Flight-Price-Prediction.git
   cd Flight-Price-Prediction
   
2. Install dependencies:
   ```bash
   pip install -r requirements.txt

4. Run the app:
   ```bash
   python app.py


   
   
