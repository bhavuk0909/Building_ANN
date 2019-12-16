# Building_ANN

It is using Keras (Using TensorFlow Backend). Steps to be followed are:

1. Building ANN -Import important libraries (Numpy, Matplotlib, Pandas) -Dataset -Encoding Categorical Data (if needed) -Splitting Data      into Train and Test -Feature Scaling

2. Building ANN -Import Keras and Models (Sequential, Dense)

3. Initialising ANN (Two ways: Defining as a sequence of layers or defining a graph) -Creating object from Sequential class (classifier) -    Adding layers (input and hidden)

4. Adding final layer

5. Compiling ANN (SGD applied)

6. Choosing the number of epochs -Fitting the ANN to training set

7. Making predictions (initialising the threshold)

8. Confusion Matrix and Accuracy

The file contains the evaluation, improvement of the ANN and parameter tuning.

1. K-fold Cross Validation is used for evaluating the ANN
2. Dropout regularisation is implemented.
3. Grid search with cross validation is used to tune the hyperparameters.
