# Cross-Validation_with_python
In previous notebooks, we split dataset to training and testing set for supervised learning(classification and regression). The training set is used to train the model, while the testing set is used to provide an unbiased evaluation of a model fit on the training set. This approach seems reasonable but there are two problems:  The training set is only a subset of the available data. The model trained on the training set may fail to adequately capture the characteristics of the whole dataset. Similarly, the evaluation metrics are generated based on testing set only. A different split may result in different metric values, making the metrics less reliable. To solve these problems, we introduce cross-validation, which is a method that attempts to maximize the use of the available data for training and then testing a model to provide a range of more accurate metrics.  We will use adult income data to demonstrate cross-validation
