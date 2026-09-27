Flight Cancellation Prediction

This project was developed by Stavros Lefakis and Nikos Apiranthitis given a dataset given by the team supervisor.

Objective
The goal is to predict whether a scheduled flight will be cancelled based on flight, airport, time, and weather information.

Dataset
https://www.kaggle.com/datasets/ioanagheorghiu/historical-flight-and-weather-data/data

Method
Exploratory data analysis was performed, followed by an XGBoost classification model. Data preprocessing included handling missing values, encoding categorical variables, and addressing class imbalance.

Evaluation
The model was evaluated using ROC-AUC, Average Precision, Precision, Recall, and F1-score, with greater focus on cancellation detection due to the low cancellation rate.

Results
The model achieved 98% overall accuracy, identified approximately 21% of actual cancellations, and achieved an F1-score of 22% for cancelled flights.

Conclusion
The results show that predicting flight cancellations is challenging using the available flight and weather information. Additional operational information such as previous delays, aircraft availability, crew constraints, and airport congestion could improve future predictions.