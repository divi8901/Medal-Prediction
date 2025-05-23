# Olympic Medals Prediction using Linear Regression

This project focuses on predicting the number of medals each country will win in the Olympics using a Linear Regression model. It utilizes historical data on Olympic athletes and events to generate country-level medal forecasts.

## Objective

To build a predictive model capable of estimating the total medal count for each country in upcoming Olympic Games based on historical trends and athlete characteristics.

## Dataset

The dataset consists of historical Olympic records and includes the following attributes:

- Athlete, age, and nationality (team)
- Year of participation
- Previous medal achievements
- Medal won 

Data is aggregated at the country level to serve as input for modeling.

## Model Overview

- **Model Type:** Linear Regression
- **Target Variable:** Total medals won by a country
- **Input Features:**
  - Year
  - Average age of athletes
  - Indicator of previous medal wins
- Categorical data is encoded using one-hot encoding where necessary.

## Workflow

1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Aggregating data by country

2. **Feature Engineering**
   - Calculating average athlete age and previous medal counts per country

3. **Model Training and Evaluation**
   - Splitting data into training and testing sets
   - Training a Linear Regression model
   - Evaluating model performance using Mean Absolute Er
