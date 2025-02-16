## Cab Fare Prediction Web Application

## Overview

Our Cab Fare Prediction Web Application utilizes machine learning algorithms to predict cab fares based on various factors such as distance, time, and location. The application is built using frontend and backend technologies, including integration with Google Maps API for location services.

## Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Machine Learning Models Used](#machine-learning-models-used)
5. [License](#license)


## Features

- Predict cab fares based on input parameters such as distance, time and weather.
- Integration with Google Maps API for location services and route calculation.
- Responsive design for optimal viewing.
- User-friendly interface for inputting ride details.
- Integration with machine learning model trained on a dataset from Kaggle.

## Installation
To run the Cab Fare Prediction Web Application locally, follow these steps:

1. **Download the Code:**
   - Clone the repository using Git:
     ```bash
     https://github.com/aryansingla45/Cab-Fare-Prediction-.git
     ```
   - Alternatively, you can download the code as a ZIP file and extract it to your desired location.

2. **Navigate to the Project Directory:**
   - Open a terminal or command prompt.
   - Change directory to the project directory:
     ```bash
     cd Cab-Fare-Prediction
     ```

3. **Install Required Libraries:**
   - Make sure you have Python installed on your machine.
   - Use `pip` to install the required libraries from the `requirements.txt` file:
     ```bash
     pip install -r requirements.txt
     ```
   - This will install Flask, pandas, numpy, scikit-learn, gunicorn, requests, and any other dependencies specified in the file.

4. **Start the Web Server:**
   - Run the Flask application using the following command:
     ```bash
     python app.py
     ```
   - This will start the web server.

5. **Access the Application:**
   - Open your preferred web browser and go to http://localhost:5000.

6. **Use the Application:**
   - Input ride details, view predicted fares, and utilize the map integration for real-time estimations.

## Usage

Use the Cab Fare Prediction Web Application as follows:

- **Input Ride Details**: Enter details such as pickup and drop-off locations, date, and time.
- **View Predicted Fare**: Get the predicted fare for the ride based on the entered details.
- **Map Integration**: View the route on Google Maps and get real-time fare estimation.

## Future Scope
- **Secure Transactions**: Ensure secure transactions with user authentication and encryption.
- **GPS Integration**: Integrate GPS Technology to calculate dynamic fare based on traffic and different routes.

  
## Machine Learning Models Used

The Cab Fare Prediction Web Application utilizes various machine learning models for predicting cab fares based on input parameters such as distance, time, and location. The models employed in this project include:

1. Linear Regression
2. Decision Trees
3. Random Forest
4. Gradient Boosting
5. Support Vector Machines (SVM)
6. Neural Networks
7. k-Nearest Neighbors (k-NN)
8. XGBoost
9. LightGBM

These models are trained on historical data to provide accurate fare predictions for different ride scenarios.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


```

Feel free to adjust any details or add additional sections as needed!
