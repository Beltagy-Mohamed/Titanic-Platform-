# Titanic Data Analysis and ML Model Deployment

## Overview

This repository contains a comprehensive analysis of the Titanic dataset, including the exploration of passenger information and the development of a machine learning model. The model predicts the probability of survival for individuals based on various factors such as class, gender, age, siblings/spouses aboard, parents/children aboard, fare, and the port of embarkation.

## Features

- **Analysis and Exploration:**
  - Utilized Pandas, NumPy, Seaborn, and Matplotlib for exploratory data analysis.
  - Investigated the distribution of passenger features, survival rates, and correlations.

- **Machine Learning Model:**
  - Developed a machine learning model using scikit-learn to predict survival probabilities.
  - The model is trained on historical data and deployed for real-time predictions.

- **Web Application with Flask:**
  - Created an interactive web application using Flask to provide users with a user-friendly interface.
  - Integrated the machine learning model into the web app for live predictions.

- **Database Integration:**
  - Utilized SQLite database to store predictions and recent model outputs.
  - Incorporated SQLite queries to retrieve recent predictions for display on the website.

## Code Structure

- `titanic_model.pkl`: Pickle file containing the trained machine learning model.
- `titanic_database.db`: SQLite database for storing predictions.
- `app.py`: Flask web application code for rendering pages and handling predictions.
- `templates/`: Folder containing HTML templates for different pages (index, about, team, result).
- `static/`: Folder for static files (CSS, images) used in the web application.

## Usage

1. Clone the repository to your local machine.
2. Install the required Python libraries using `pip install -r requirements.txt`.
3. Run `app.py` to start the Flask web application.
4. Access the web application at `http://localhost:5000` in your browser.

## Web Application Structure

- **Home Page (`/`):**
  - Overview of the project with a link to access the prediction form.

- **Prediction Form (`/predict`):**
  - Form for users to input passenger details and receive survival probability predictions.

- **Result Page (`/result`):**
  - Display of the most recent prediction, survival probability, and a table of recent predictions.

- **About and Team Pages (`/about`, `/team`):**
  - Information about the project and the team involved.

## Contributors

- [Beltagy Mohamed]
- [Ali Mohamed]
- [Mohamed Ahmed]
- [Abdelrahman Ramadan]
- [Ziad Selim]
