# Olympic Medals Prediction

This project aims to predict the number of Olympic medals a country will win based on historical data. The prediction is made using a Linear Regression model, which takes into account the number of athletes and previous medals as features.

**Project Steps**

1. Forming a hypothesis.
2. Finding and exploring the data.
3. Reshape the data to predict your target.
4. Clean the data for ML.
5. Pick an error metric.
6. Spliting the data.
7. Training a model.

## Dataset

The dataset used in this project contains historical records of Olympic Games, including the number of athletes a country sent to the games, the number of medals won, and the number of previous medals. The data can be found in the `teams.csv` file.

### Sample Data Format
Year,Team,Athletes,Prev_Medals,Medals
2000,IND,200,5,2
2004,IND,220,2,3
2008,IND,240,3,4

File overview:

* `machine_learning.ipynb` - the main project code
* `teams.csv` -athlete-level dataset

# Python packages used
    * pandas
    * numpy
    * scikit-learn
    * seaborn
    *matplotlib
    *sklearn

## Data
We are using data from the Olympics, which was originally on [Kaggle](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results).
