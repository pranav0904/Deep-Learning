# Deep Learning Model

Objective of this Repository is to check whether the CNN model can be applied on multivariate tabular dataset or not. If yes then improve the performance of the model by setting proper values for hyperparameters and network architecture. For this purpose, I have taken s&p500 data to predict whether Consumer Price Index will increase or decrease based on the other economic indicators such as SP500, Dividend, Earnings, Long Interest Rate, Real Price, Real Dividend, Real Earnings.

Multivariate CNN Models: Although traditionally developed for two-dimensional image data, CNNs can be used to model Multivariate time series forecasting problems.

Multivariate time series data means data where there is more than one observation for each time step with a temporal ordering and a model is required to learn from the series of past observations to predict the next value in the sequence.

File s&p500.ipynb is divided in two parts.
```
A.Data Preparation
B.CNN Model
```

Data Source:  https://datahub.io/core/s-and-p-500

Dependencies:
- Pandas
- numpy
- matplotlib
- keras
