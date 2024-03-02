# -Laptop-Price-Prediction-App (https://github.com/1sdata/-Laptop-Price-Prediction-App.git)

Laptop Price Prediction App

## Overview

The Laptop Price Prediction App is a machine learning-powered tool designed to provide accurate price recommendations for both sellers and buyers in the laptop market. Leveraging advanced machine learning algorithms, the app analyzes key laptop specifications and market trends to generate reliable price predictions, facilitating informed decision-making for users.

## Key Features

---> Price Recommendations: The app offers personalized price recommendations based on various laptop specifications, including brand, processor type, RAM size, storage capacity, screen size, graphics card, and more.

- User-Friendly Interface: With an intuitive user interface, users can easily input laptop specifications and receive instant price predictions, making the app accessible to both novice and experienced users.

- Real-Time Updates: The app continuously updates its price predictions based on the latest market data and trends, ensuring users have access to the most up-to-date information.

- Performance Metrics: Users can evaluate the reliability of price predictions using performance metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).

- Comparison Tools: Offer comparison tools to compare multiple laptops side by side, highlighting differences in specifications and predicted prices.

- User Authentication and Security: Implement user authentication mechanisms to ensure data privacy and security, especially for users who save their preferences or historical data.

- Data Visualization: Visualize data and insights using charts, graphs, or interactive visualizations to enhance user understanding and engagement.

## Getting Started

## Project Description:

Machine Learning Model API Using Flask & Docker to Predict Laptop Prices based on Specs Data of Laptop, Once Running Docker Image, WSGI Server will be Running, HTTP Request Can be Send with JSON Data like below

```json
#sample
{
    "laptop_ID": 78,
    "Company": "HP",
    "Product": "",
    "TypeName": "Notebook",
    "Inches": 13.7,
    "ScreenResolution": "Full HD 3840x2160",
    "Cpu": "AMD A10-Series 9620P 2.5GHz",
    "Ram": "24GB",
    "Memory": "500GB HDD",
    "Gpu": "Intel Iris Plus Graphics 650",
    "OpSys": "Windows 10",
    "Weight": "1.5kg"
}
```
and Response will get back as the predicted value of Laptop Price
```json
# prediction of price
{
    "predicted_price": 1715.9983530577372
}
```
if there are Invalid Data, Response will be
```json
# example of invalid sample
{
    "error": "Invalid Data"
}
```
## Tech & Dependancies:

- Python 3.10
- Docker
- Github Actions-CI/CD Pipeline
- Knowledge About ML

## Data:

Brief description of the dataset used for training the model.

[Laptop Price](https://www.kaggle.com/datasets/muhammetvarl/laptop-price)

Preprocessing: Outline any preprocessing steps applied to the data before model training.
Model
Algorithm: Specify the machine learning algorithm(s) used for predicting laptop prices.
Evaluation: Summary of model performance metrics and validation techniques used.
Deployment: Instructions on how to deploy the model as part of the app.
Results
Performance: Present any performance metrics or results achieved by the model.
Visualization: Include visualizations of key insights or model outputs, if applicable.
Future Work
Enhancements: Ideas for future enhancements or features to be added to the app.
Maintenance: Suggestions for maintaining and updating the app over time.
Contributing
Provide guidelines for contributing to the project, including how to report bugs, submit feature requests, or contribute code.

License
Specify the license under which the app and its associated code are distributed.

Authors
List the authors or contributors who have contributed to the development of the app.

Acknowledgments
Acknowledge any individuals, organizations, or resources that have contributed to the project.

Contact
Provide contact information for users to reach out for support, feedback, or collaboration opportunities.