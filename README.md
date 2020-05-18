# bike_sharing_demand_sgd_n_rand_forest
Using machine learning to create a model that predicts use of a city bikeshare system (old 'Bike Sharing Demand' ML competition from Kaggle).

Bike sharing systems are a means of renting bicycles where the process of obtaining membership, rental, and bike return is automated via a network of kiosk locations throughout a city. Using these systems, people are able rent a bike from a one location and return it to a different place on an as-needed basis. The data generated by these systems makes them attractive for researchers. In this competition, participants are asked to combine historical usage patterns with weather data in order to forecast bike rental demand in the Capital Bikeshare program in Washington, D.C. Submissions are evaluated on the Root Mean Squared Logarithmic Error (RMSLE).

The dataset was provided by Hadi Fanaee Tork using data from Capital Bikeshare for 2011 and 2012 years.The dataset consist hourly rental data spanning two years. The training set is comprised of the first 19 days of each month, while the test set is the 20th to the end of the month. It's need to predict the total count of bikes rented during each hour covered by the test set, using only information available prior to the rental period. For a detailed description of the features, see the IPythonNotebook.

More information about the Kaggle competition 'Bike Sharing Demand' and data for this you can find on https://www.kaggle.com/c/bike-sharing-demand.

I created two models of machine learning: Stochastic Gradient Descent Regressor (a type of linear model) and Random Forest Regressor, that predict use of a city bikeshare system. Randon forest showed better results, so for the submission I chose Random Forest model, which achieves a score of 0.44 RMSLE, which is in the first quarter of all submission in the contest. I used IPythonNotebook and Python 3 with sklearn.
