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
- pandas==0.25.3
- numpy==1.17.4
- matplotlib==3.1.2
- keras==2.2.5


## Conclusion:
After performing analysis on the CNN model, it is observed that,
```
1. For the baseline model, Loss is Higher and Accuracy on validation data is 63%.
2. The cost function logcosh is appropriate for this model than hinge.
3. Higher the number of epochs, better the model is.
4. Change in Optimizer can increase the accuracy and it helps to reduce the loss. Adagrad is better suit for this type of model than RMSprop.
5. Network architecture is as important as hyperparameters. By adding more layers and with proper use of hyperparamters, we can achieve higher accuracy.
6. After changing the kernel initialization, accuracy on validation set got increase.
7. For Multivariate Tabular data, Convolution Neural Network can produce good results but handling of data For the CNN model is difficult.

```


## Citation:
References:
- https://keras.io/models
- https://machinelearningmastery.com/
- https://karpathy.github.io/2019/04/25/recipe

