# Airline-Passenger-Referral-Predication-Project
Table of Content

    Introduction
    Abstract
    Dataset Information
    Problem Statement
    Conclusion

-----------------------------------------------------
📖 Introduction:

    One of the most difficult business challenges is predicting airline passenger referrals.

    The dataset includes airline reviews with multiple choice and free text questions from 2006 to 2019 for popular airlines across the world. In the spring of 2019, data will be scraped.

    So our major goal was to anticipate whether or not passengers will recommend the flight to their friends and Family.

    Once we've accomplished our main goal, any passenger reviews in the air transport industry will be predicted, and the task can be completed while the results are studied and business demands are expanded. As a result, the aviation industry may see an increase in growth.


-----------------------------------------------------
📖 Abstract:

    In order to gain a comprehensive grasp of the data, we conducted extensive analysis in this project. We can extract a lot of information from the analysis by using exploratory data analysis, data wrangling, visualization, and other techniques.

    After conducting the investigation, we have come to the conclusion that our primary purpose is to forecast if a traveller will positively recommend his or her Flight to their family and friends.

    Based on our business expert knowledge, which we obtained through EDA. We were able to extract essential features that were required for our problem

    The majority of the attributes are related to Airline ratings, and these features are crucial to our forecasting model.

    Our mission is to develop a prediction model for our classification task. With the help of a number of machine learning algorithms and hyperparameter tuning, the optimal model must be built in order to produce the most effective and realistic results.

-----------------------------------------------------
📖 Dataset information:

    Airline: Name of the Airline

    Overall: Overall rating is given to the trip between 1 to 10.

    Author: Name of the Author to provide reviews about the trip

    Review Date: Date of the Review

    Customer review: Review of the customers in a text format

    Aircraft: Type of the Aircraft

    Traveler type: Type of traveler (Labels: Business, Family Leisure,Solo Leisure & Couple Leisure)

    Cabin: Cabin at the flight (Labels: Economy Class,Business Class,Premium Class & First Class)

    Date flown: Flight date

    Seat comfort: Rating between 1-5

    Cabin Service: Rating between 1-5

    Foodbev: Rating between 1-5

    Entertainment: Rating between 1-5

    Groundservice: Rating between 1-5

    Value For Money: Rating between 1-5

    Recommended: Binary Labels(Target Variable)

-----------------------------------------------------
📖 Problem Statement:

    This data comprises airline reviews for popular airlines around the world from 2006 to 2019.

    The first objective is to do some EDA to obtain a better knowledge of the problem from a business perspective.

    Following our analysis, We've determined that our primary goal is to create a model that can predict whether a traveller will gladly recommend his or her flight to their family,friends and the public.

-----------------------------------------------------
📖 Conclusion:

    After the dataset has been loaded, we remove unnecessary columns, null value treatment, and multicollinearity features, among many other things.

    The Logistic Regression Model, the Decision Tree Model, the Random Forest Model, and the Gradient Boosting Model are the models utilised to solve this classification problem.

    We used the Grid search CV approach to do hyperparameter tuning for the Decision Tree Model, Random Forest Model, and Gradient Boosting Model.

    This is done in order to improve accuracy while avoiding overfitting criteria. The hyperparameters for the Gradient Boosting model were then finalised.

-----------------------------------------------------
