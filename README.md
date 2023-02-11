# About_Train_Test_Split

WHAT IS TRAIN TEST SPLIT?
Train test split is a model validation process that allows you to simulate how your model would perform with new data.

What is the train test split procedure?
How to use train test split to tune models in Python.
Understanding the bias-variance tradeoff.

What Is the Train Test Split Procedure?

1. ARRANGE THE DATA
Make sure your data is arranged into a format acceptable for train test split. In scikit-learn, this consists of separating your full data set into “Features” and “Target.”

 

2. SPLIT THE DATA 
Split the data set into two pieces — a training set and a testing set. This consists of random sampling without replacement about 75 percent of the rows (you can vary this) and putting them into your training set. The remaining 25 percent is put into your test set. Note that the colors in “Features” and “Target” indicate where their data will go (“X_train,” “X_test,” “y_train,” “y_test”) for a particular train test split.

 

3. TRAIN THE MODEL
Train the model on the training set. This is “X_train” and “y_train” in the image.

 

4. TEST THE MODEL
Test the model on the testing set (“X_test” and “y_test” in the image) and evaluate the performance.

MORE ON DATA SCIENCE
Understanding Boxpolots

 

Consequences of Not Using Train Test Split
You could try not using train test split and instead train and test the model on the same data. However, I don’t recommend this approach as it doesn’t simulate how a model would perform on new data. It also tends to reward overly complex models that overfit on the data set.

![image](https://user-images.githubusercontent.com/82255110/218241461-a23698a1-292a-44b5-bff7-8a6c5448ad4f.png)
