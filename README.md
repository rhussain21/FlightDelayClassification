# Project Report: Flight Delays Prediction 

This repository contains a comprehensive analysis detailing the methodology, results, and insights derived from predicting flight delays within a 2-hour window using historical flight and weather data.

## Overview:

The aviation industry faces significant challenges due to flight delays. This project aims to assist airline companies in mitigating these challenges by accurately predicting flight delays using machine learning models. Data was sourced from the US Department of Transportation and the National Oceanic Atmospheric Administration. The project encompasses several steps, including preprocessing, feature engineering, model creation, hyperparameter tuning, and model evaluation. 

It is structured into four phases:
1. Data Description, Project Plan, Joins, Metrics
2. EDA, Pipeline
3. Feature Engineering, Model Creation, Hyperparameter Tuning
4. Selecting the Optimal Model, Model Evaluation, Conclusion

## Dataset:

1. **Flights Data**: Contains detailed information about flight schedules, times, delays, cancellations, and other flight-related metadata.
2. **Weather Data**: Provides comprehensive weather details from 2015-2021, vital for analysis as weather significantly influences flight delays.
3. **Airports Data**: Offers in-depth information about the airports, enhancing the geographical analysis of delays.

## Models:
1. Baseline - Always Predict Delay
2. Logistic Regression
3. Random Forest
4. Gradient-Boosted Tree
5. Multilayer Perceptron
   
## Results:

In the context of the business challenge, success was gauged by the number of customers boarding their flights. A false negative implied that a delay occurred but went undetected, resulting in passengers missing their flights. Conversely, a false positive meant that a predicted delay did not materialize; while this led to changes in flight routing, passengers still managed to board their flights. Given these definitions, recall became paramount, prompting the use of the F2-score for model evaluation.

Among all models tested, logistic regression boasted the highest F2-score.
