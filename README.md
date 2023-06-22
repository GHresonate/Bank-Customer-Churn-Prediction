# Bank-Customer-Churn-Prediction
A little ML experiment, where I tried to predict customer churn, based on data from Kaggle - https://www.kaggle.com/datasets/adammaus/predicting-churn-for-bank-customers. I got a few interesting plots with correlation between features, and tried to predict churn based on that.
The best result I have is 0.86 with random forest, versus 0.79 with dummy. It is not a bad result, but it has room to grow.
## What needs to be done?
*1) In-depth work with features:* at first, remove some of them, and see what will happen if I leave only ones with a good correlation with leaving. Also, a few minor things to make the prediction better;

*2) Work with biases:* calculate biases of different models, then try to minimise them;
