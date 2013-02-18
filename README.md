mlia-examples
=============

book/
=====

Examples from Peter Harrington's Machine Learning in Action (MLIA).

The code is __not__ a direct copy of whats in the book or in the github site, but does the same thing. I have tried to make the code shorter and (at least to me) more understandable.

Data files are not copied over. You will find the data files (of the same name as in the code) in the [book's source code site on GitHub](https://github.com/pbharrin/machinelearninginaction).

event_reco/
===========
My solution for the Kaggle Event Recommendation Challenge. Given a training set of users who are interested/not_interested in events, and user and event metadata and some social (user's friends information) metadata, the objective is to order the events in the test set per user, so events with higher probability are recommended first. The approach I have taken is to construct a set of different kinds of recommenders, and construct features from the recommender scores, then build a predictive model (SGD) to predict the value of interested. The distance from the separating hyperplane is the measure of the likelihood of recommendation.

