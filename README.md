# Enerygy Usage Intensity Prediction - WiDS 2022 

This project is a Kaggle competition hosted by Women in Data Science (WiDS) where the goal is to predict the energy usage intensity of a building which is the energy used per square foot each year. The code base is a work in progress. However, I am done with the EDA for this. 

### Data

The data can be found in : https://www.kaggle.com/c/widsdatathon2022/data

 * EUI is Total energy consumed by a building in a year/ total gross floor area of the building (sq ft)
 * Each row represents a single building for a given year 
 * Need to predict site eui for each row with specific building characteristics and weather information 
 
### Process 

* EDA : Exploratory Data Analysis is complete and the notebook has details of data distribution for the variables as well as the relationship among them and the response.
* Preprocessing : Checked for missing values and handled them
* Model selection : As this is a regression problem, tried out a few statistical models such as multi-linear regression, Random Forest and Gradient Boost. Tuning is in progress. 
* Feature selection & Outlier detection : TBD  
* Evaluation of models : TBD