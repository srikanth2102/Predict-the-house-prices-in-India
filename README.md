# HOUSE PRICE PREDICTION

## OVERVIEW
* In this project we predict the price of house in india using Machine Learning.
* See the data analysis pdf for understanding the data.
* The data for this is taken from [here.](https://www.kaggle.com/anmolkumar/house-price-prediction-challenge)

## DATA DESCRIPTION
* Train.csv - 29451 rows x 12 columns
* Test.csv - 68720 rows x 11 columns

## ATTRIBUTES DESCRIPTION

|Column                   | Description                                       |
| --------                | ---------------                                   |
|POSTED_BY                |	Category marking who has listed the property      |
|UNDER_CONSTRUCTION       |	Under Construction or Not                         |
|RERA                     |	Rera approved or Not                              |
|BHK_NO.                  |	Number of Rooms                                   |
|BHK_OR_RK                |	Type of property                                  |
|SQUARE_FT	              | Total area of the house in square feet            |
|READYTOMOVE              |	Category marking Ready to move or Not             |
|RESALE	                  | Category marking Resale or not                    |
|ADDRESS                  | Address of the property                           |
|LONGITUDE	              | Longitude of the property                         |
|LATITUDE	              | Latitude of the property                          |

## MODELS USED
 
The Machine Learning models used in this project are 
* Linear Regression
* Decision Tree
* Random Forest
* Gradient Boosting

## MODEL PERFORMANCE
![model performance](https://i.ibb.co/L9912Jp/Capture.jpg)

## BEST MODEL
* From the BarPlot we can see that Gradient Boosting has the highest score.
* We will use Gradient Boosting to make predictions on the test dataset.

## RESULT 
* The result of the model is saved in csv file named "prediction.csv". 