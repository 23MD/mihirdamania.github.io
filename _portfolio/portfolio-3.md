---
title: "Capstone Project: Prediction of SpaceX Falcon 9 Rockets Launch Outcome"
excerpt: "This project aims to predict the outcomes of SpaceX launches, specifically determining whether a launch will be successful or result in a failure. The dataset used in this project includes various features related to the launch conditions, rocket types, and other relevant factors.<br/><img src='/images/Telangana_Project.png'>"
collection: portfolio
---

## Overview
This project aims to predict the outcomes of SpaceX launches, specifically determining whether a launch will be successful or result in a failure. The dataset used in this project includes various features related to the launch conditions, rocket types, and other relevant factors.

## Features
The main features in the dataset include:
- **Rocket Type**: The type of rocket used for the launch.
- **Launch Site**: The geographical location from where the rocket is launched.
- **Payload Mass (kg)**: The weight of the payload that the rocket is carrying.
- **Orbit**: The intended orbit for the payload.
- **Launch Outcome**: The result of the launch, categorized as either 'Success' or 'Failure'.

## Objectives
- To analyze the factors influencing the success or failure of SpaceX launches.
- To build a predictive model that can forecast the outcome of a launch based on the available features.

## Data Preprocessing
The dataset has undergone several preprocessing steps to ensure that it is ready for modeling:
- **Handling Missing Values**: Imputation strategies were used for missing values in the dataset.
- **Encoding Categorical Variables**: Categorical variables like Rocket Type and Launch Site were encoded to numerical formats.
- **Feature Engineering**: Additional features were created to capture important information from the existing data.

## Modeling
The project explores several machine learning models, including:
- **Logistic Regression**: Used to predict the probability of a launch being successful.
- **Random Forest**: Employed for its ability to handle both categorical and continuous variables efficiently.
- **Support Vector Machine (SVM)**: Implemented to classify launch outcomes with high accuracy.

## Evaluation
The models were evaluated based on the following metrics:
- **Accuracy**: The percentage of correct predictions made by the model.
- **Precision**: The ability of the model to avoid false positives.
- **Recall**: The ability of the model to identify all actual positive cases.
- **F1 Score**: The harmonic mean of precision and recall.

## Dashboard UI

![Piechart](https://github.com/23MD/DataScience_Capstone_Project/blob/02ffd8b1eaf80a4d14d2f7c54d74252243b6f38a/images/dash%20pie.PNG)

![sliderChart](https://github.com/23MD/DataScience_Capstone_Project/blob/02ffd8b1eaf80a4d14d2f7c54d74252243b6f38a/images/slider%20chart.PNG)

## Results

All classification model 
performed similarly on the test dataset and showed 
same accuracy score.However there seems overfitting with Decision Tree Classifier model since the accuracy score on test dataset was fluctuating showing huge variation.
![Confusion matrix](https://github.com/23MD/DataScience_Capstone_Project/blob/02ffd8b1eaf80a4d14d2f7c54d74252243b6f38a/images/confusion_matrix.png)

![scores](https://github.com/23MD/DataScience_Capstone_Project/blob/02ffd8b1eaf80a4d14d2f7c54d74252243b6f38a/images/scores.PNG)

![accuracy](https://github.com/23MD/DataScience_Capstone_Project/blob/02ffd8b1eaf80a4d14d2f7c54d74252243b6f38a/images/Accuracy_score.png)

## Conclusion
The project successfully demonstrates the ability to predict the outcomes of SpaceX launches using machine learning techniques. The models developed in this project can be further fine-tuned and extended with additional data to improve predictive performance.


## Technology Stack
- **Programming Language**: Python
- **Development Environment**: Jupyter notebook
- **Mysql**: Database

## Libraries Used
- **Pandas**: Data manipulation
- **NumPy**: Numerical computations
- **Matplotlib**: Data visualization
- **Plotly**: Data visualization
- **Dash**: Dashboard and visualization
- **BeautifulSoup**: Web Scrapping
- **Request**: For making HTTP requests

## Acknowledgment
- Data sourced from [SpaceX API](https://docs.spacexdata.com/) and [Wikipedia](https://en.wikipedia.org/w/index.php?title=List_of_Falcon_9_and_Falcon_Heavy_launches&oldid=1027686922).
