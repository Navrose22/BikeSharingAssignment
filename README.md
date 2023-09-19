# Bike Sharing Assignment
> Created multi linear regression model to predict the demand of shared bikes so that the company can manipulate their business strategies to meet the consumer's expectations.
> This repository contains the code and resources for a bike sharing assignment, where I have developed a multiple linear regression model to predict bike rental demand.



## Table of Contents
* [Introduction](#Introduction)
* [Data](#Data)
* [Predictions](#Predictions)
* [Conclusions](#Conclusions)
* [Technologies Used](#Technologies Used)
* [Acknowledgements](#Acknowledgements)
* [Contact](#Contact)

<!-- You can include any other section that is pertinent to your problem -->

## Introduction
* In this project, we aim to predict bike rental demand based on various factors such as weather conditions, time of day, and more using a multiple linear regression model. This README provides an overview of the project, instructions on how to use the code, and insights into the results.

  

## Data

### Data Sources

- Data set based on the data provided by the US company "BoomBikes" (Bike sharing company)

### Data Understanding

- This involves reading and understanding the data
- Check for the null values if any

### Data Visualisation

- Visualises the data to check the linear relationship
- Invloves plots of numerical as well as categorical variables

### Data Preparation

- Prepares data for multi linear regression
- Checks for the outlinears and drop out those from the data set to make the most reliable model
- Creates dummy variable out of the categorical variables

### Traning and Testing data

- Creates training and testing data from the data set
- Rescaling the features to get the best outcome

### Building model

- Calculates RFE
- Builds model to get the best fit
- Residual analysis of the data helps in predicting the nature of the residuals (in this case they are normally distributed)
   



## Predictions
- Predicts the model for the actual v/s predict variable
- Calculates R^2 after getting a linear fit for the predicted model



## Conclusions
- Significant variables to predict the demand are
- temp, working day, saturday, windspeed and more..

  
## Technologies Used
- Jupiter Notebook
*  Libraries:
  - Numpy
  - Pandas
  - statsmodels
  - matplotlib
  - seaborn
  - sklearn




## Acknowledgements
Give credit here.
- This project was inspired by upgrad


## Contact
Created by [@Navrose22] - feel free to contact me!

