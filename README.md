# Churn Prediction - Ride Sharing Services
Predicted possibility of customer churning, thereby targeting special campaigns to increase retention rate. Built random forest model to predict churn and developed profit curves to tune parameters. Improved recall rate by 15% from the baseline model through feature reduction, decreasing false predictions.


## Files in src and it's use

* collection_app.py - Collects live data from a Heroku App and stores it into a MongoDB
* model.py - Compares the performance of models and stores the best model in pickle format
* my_app.py - Loads pickled model and performs the predictions on live data and pushes it to the Web app using Flask
* predict.py - Predicts the fraud risk level based on the probability

## Rough timeline 

* First 3 hours: EDA, Feature Engineering
* Next 3 hours: Model building and deployment


## Credits
This project would not be possible without the efforts of my fellow teammaates Anusha Mohan, Joseph Wiley, Jianda Zhou

