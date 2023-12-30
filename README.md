<center><h1> Air Pollution in Madrid </h1></center>
<center><h1> Data Science project </h1></center>
<center><h1> King Faisal Universisty </h1></center>

## Project Description
This project is about building a model that can predict the Air quality in Madrid based on 170k rows of an hourly recorded data from 2001 to 2022 

## Dataset
The dataset is downloaded from Kaggle and can be found [here](https://www.kaggle.com/datasets/ignacioqg/20012022-hourly-dataset-of-pollution-in-madrid)

## Project Structure
```
├── data
│   ├── MadridPolution2001-2022.csv
│   ├── MadridPolution2001-2022_cleaned.csv
|
├── notebooks
│   ├── 1 - EDA - Air pollution.ipynb
│   ├── 2 - Data preprocessing - Air pollution.ipynb
│   |── 3 - Modelling implementation & assessment Air pollution.ipynb
|
├── README.md
```

## Project Steps
1. Exploratory Data Analysis
    1. Found that the data is not clean and need to be cleaned
    1. remove the outliers
    1. find the correlation between the features
    1. find the distribution of the features
1. Data Preprocessing
    1. fill the missing values
    1. group the data by year and month
    1. get the mean of each year
    1. split the data into train and test
1. Modelling implementation & assessment
    1. build 3 models
        1. Logistic Regression
        1. Random Forest
        1. XGBoost
    1. evaluate the models
        1. accuracy
        1. precision
        1. recall
    1. choose the best model
        1. XGBoost
        1. accuracy: 0.77
        1. precision: 0.77
        1. recall: 0.77
        1. f1-score: 0.77
## Project Results
The best model is XGBoost with an accuracy of 0.77
