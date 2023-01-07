
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

### Inference from Exploratory Data Analysis

From both the heatmap and the plots above, we can see a negative correlation between highway and city mpg ( how far the car is able to travel for every gallon of fuel it uses in the highway and around the city) and the Engine HP. Horsepower is a measure of work that can be performed over a given time by an engine. The more power you have the higher the speed you can do it at during a period of time. Generally, higher horsepower comes from burning more fuel, so get lower mpg, more horsepower means less fuel economy. Basically, race cars and sports cars such as Corvette Have a High Engine Horsepower and a low mpg since they can speed and thus burn more fuel. Cars like FIAT have a lower Engine Horsepower but a higher mpg since the speed is limited and considered to be more fuel economy. Cars with all drive modes, large size, Automated manual transmission and Convertible Style marks high Price Values. There was an increase in price of cars every year. More popular a car brand, higher is its Price.

### Inference from Machine Learning Models

Among all the models built, one can infer that the Random Forest Regression model predicts the given dataset more precisely and accurately than other models. Features such as the safety measures and resale value can be added to improve the model.

