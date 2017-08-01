# RUT_Index_Prediction

This Project tries to predict the Russell Index price based on the 25 years of Historical Data from Yahoo Finance Api.

Initially 25 years of data is cleansed in first phase, then passed through R-TTR Package and 148 Technical Indicators were generated.

In later phase Correlation between 148 Technical parameters is found using correlation matrix.

in the sub phase the highly correlated Technical Indicators, historical data is fed to the model then trained and tested.
