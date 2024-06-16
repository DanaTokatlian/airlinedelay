# Airlines Delay Prediction

Applying machine learning classification techniques to predict if a specific flight will be delayed or not.

Brief Summary
- Providing predictions of flight delays can be very efficient to the airlines management.
- It can reduce the losses caused by the delays.
- Can also increase passenger satisfaction and airline revenue and improve the aviation system.
Getting accurate predictions is a complex issue since there are many factors influence this.

Data Source
Used a dataset from Kaggle, a dataset with large number of flight observations and nine different features.
link

Machine learning techniques used to make predictions
- Logistic Regression
- K Nearest Neighbors
- Decision Tree
- Random Forest

Results
- After doing Data Analysis, we can clearly see that some airlines have more delays than others.
- Using Decision Tree and Random Forest, we find that the Airline feature is the most important predictor and the second one is the Time feature.
- After applying the mentioned classification models and trying to improve their performance by grid searching over the hyperparameters, we couldn't get more than 64% scoring.
- The available features in this dataset are not enough.

Next Steps
- Looking for other datasets that contain information about the weather and time of year.
