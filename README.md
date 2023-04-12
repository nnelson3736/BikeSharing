# Bike Sharing - Boom Bikes
> This is a case study to analyse the data of a bike rental company in US. We have 2 years data of 2018 and 2019. Using the available data we have created a model to better predict the behavious of Bike Rental in the coming years. We have created the model using Multiple Linear Regression.


## Table of Contents
* [Dataset]
* Splitting the Data
* Scaling the Data
* Model Creation using RFE
* Residual Analysis of the Data
* Testing the Model on the Test Dataset
* [Technologies Used]
* [Contact]

<!-- You can include any other section that is pertinent to your problem -->

## Dataset
- The original Dataset contained 730 entries with 16 columns or variables
- for better understanding we entered the correct values of the Variables like Season, Month and so on
- We then created Dummy Variables for creating the regression model.
- We also removed the variables which we felt were not needed for the model building

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Splitting the Data

The data was split into 2 parts training and test dataset. Training dataset with 70% of the values and Test dataset with 30% of the values.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
## Scaling the Data

The data needed to be scalled for better model creation as the values of the continuos variables had huge variations we used Min-Max Scaling for scaling the data

## Model Creation using RFE

We built the model using the RFE method
we also checked the VIF values to make sure that we dont have variables with high VIF Values
after dropping some variables we finalized the variables which gave us the best results

## Residual Analysis of the Data

We also cchecked if the the error values were normally distributed or not and if the mean was zero

## Testing the Model on the Test Dataset

The model was then finally tested on the Test Dataset and the relationship was linearly established


## Technologies Used
- Python 
- Pandas Library
- Matplotlib.pyplot Library
- Seaborn Library
- sklearn
- statsmodel


## Contact
Created by [@nnelson3736] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
