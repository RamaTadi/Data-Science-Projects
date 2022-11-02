# Project Overview 
---
This project is based on the dataset available on the kaggle provided by [KultureHire](https://www.kaggle.com/datasets/kathir1k/youtube-influencers-data). In this project in the first part, we will do the Exploratory Data Analysis(EDA) and in second part we fit a linear regressin model to the cleaned dataset and check whether the assumptions fo regression are satisfied. We will load the data and preprocess the data. We will convert the column data types to suitable formats, impute the missing values, drop the duplicate rows and null values and we feature engineer new columns. In EDA, we focus majorly on how the *number of likes, video views*  are varying across different variables and draw those visualizations. 

In the second part, we load the cleaned dataset and fit a linear regression fit with  number of views the video got as target variable and other columns as independent variables. We will check whether the assumptions of regression , `Linear Relationship between Dependent and Independent variable`, `Homoskedasticity`, `Normal Distributin of the resiudals`, `No Autocorrelation`, `No Multicollinearity` and try to improve the model . 

# Code 
You can find the code for the first part EDA [here](https://github.com/RamaTadi/Data-Science-Projects/blob/main/Youtube%20Analysis%20and%20Modelling/%20eda-on-youtube-channels.ipynb) and 
You can find the code for the second part Linear Regression [here](https://github.com/RamaTadi/Data-Science-Projects/blob/main/Youtube%20Analysis%20and%20Modelling/linear-regression-assumptions.ipynb)

## Setup

### Installation 

The project is done online on kaggle notebook. 
To to this one needs

* Kaggle Notebook or Jupyter Notebook
* Python 3.7.12
* Python packages
    * Pandas
    * Numpy
    * Matplotlib
    * Seaborn 
    * Sklearn 
    * Statsmodel

### Data 
The data used for this project can be downloaded from the kaggle [here](https://www.kaggle.com/datasets/kathir1k/youtube-influencers-data) and the cleaned dataset is available [here](https://github.com/RamaTadi/Data-Science-Projects/blob/main/Youtube%20Analysis%20and%20Modelling/Data%20Sets/youtube_cleaned.csv)
