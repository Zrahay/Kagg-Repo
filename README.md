This Repo consists of my Kaggle Competitions and the each submission that I am making is being pushed seperately.

For example, the Beats Prediction competition is the one where we are supposed to predict the beats per second according to the input
features that we have been given. I have initially performed some data pre - processing on the input features. For ex, scaling down
one of the features between 0 to 1 so that the model doesn't end up giving that feature the highest importance. In the model parts, I 
started off with Linear Regression which is a curve fitting process followed by Ridge and Lasso Regression which are Linear Regression
with Regularization terms. As for the next step, I switched to the Bagging Regressor from sklearn and it gave me worse results prompting me
to use Boosting which again hasn't given me a better result that Linear Regression.
