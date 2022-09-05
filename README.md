# Exploratory Data Analysis Of Car Features Using Machine Learning

In statistics, Exploratory Data Analysis is an approach to analyzing data sets to summarize their main characteristics, often with visual methods. A statistical model can be used or not, but primarily EDA is for seeing what the data can tell us beyond the formal modeling or hypothesis testing task. Exploratory data analysis was promoted by John Tukey to encourage statisticians to explore the data, and possibly formulate hypotheses that could lead to new data collection and experiments. EDA is different from initial data analysis (IDA) which focuses more narrowly on checking assumptions required for model fitting and hypothesis testing, and handling missing values and making transformations of variables as needed. EDA encompasses IDA.

So in this project, we will explore the data and make it ready for modeling.

![image](https://user-images.githubusercontent.com/69813792/188486379-0dc3c270-6611-4bdd-9c8e-83e085e59aa8.png)


### Data Description

The data comes from the Kaggle dataset "Car Features and MSRP". It describes almost 12,000 car models, sold in the USA between 1990 and 2017, with the market price and some features. 

### Objective

The objective of the project is to do data pre-processing and exploratory data analysis of the given dataset.

### Libraries

1. Pandas
2. Numpy
3. Matplotlib
4. Seaborn
5. Sklearn

### Machine Learning Models

1. Linear Regression
2. Random Forest Reggresion
3. Support Vector Regression
4. Decision Tree

### Data Processing

Data is being cleaned and processed. Irrelevant columns, null values and duplicates are dropped from the dataset. an outlier is an observation point that is distant from other observations.The outliers can be a result of a mistake during data collection or it can be just an indication of variance in your data. Sometimes they can be very high or very low. It's often a good idea to detect and remove the outliers. Because outliers are one of the primary reasons for resulting in a less accurate model. Often outliers can be seen with visualizations using a box plot. 

Correlation matrix and other various plots depicting outliers, missing values, correlations, etc are plotted for visualiztion and analysis of data.

Correlation Matrix

![image](https://user-images.githubusercontent.com/69813792/188486473-a2d1c711-ee73-42ce-af4f-7caac066a7ec.png)


### Inference from Exploratory Data Analysis

From both the heatmap and the plots above, we can see a negative correlation between highway and city mpg ( how far the car is able to travel for every gallon of fuel it uses in the highway and around the city) and the Engine HP.

Horsepower is a measure of work that can be performed over a given time by an engine. The more power you have the higher the speed you can do it at during a period of time. Generally, higher horsepower comes from burning more fuel, so get lower mpg, more horsepower means less fuel economy.

Basically, race cars and sports cars such as Corvette Have a High Engine Horsepower and a low mpg since they can speed and thus burn more fuel.

Cars like FIAT have a lower Engine Horsepower but a higher mpg since the speed is limited and considered to be more fuel economy.

Cars with all drive modes, large size, Automated manual transmission and Convertible Style marks high Price Values.

There was an increase in price of cars every year.

More popular a car brand, higher is its Price.

### Machine Learning 

A machine learning model is a file that has been trained to recognize certain types of patterns. You train a model over a set of data, providing it an algorithm that it can use to reason over and learn from those data.

![image](https://user-images.githubusercontent.com/69813792/188486747-80bc4bb7-ea72-4dfa-8f9a-779db8b5d453.png)


### Inference from Machine Learning Models

Among all the models built, one can infer that the Random Forest Regression model predicts the given dataset more precisely and accurately than other models.
Features such as the safety measures and resale value can be added to improve the model.

