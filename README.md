# Alphabet Soup Analysis

---------------------
## Purpose
---------------------
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. We will use machine learning models and neural networks to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

1. Preprocess the Data

- Use pd.get_dummies() to encode categorical variables.
- Split the preprocessed data into a features array, X, and a target array, y. Use these arrays and the train_test_split function to split the data into training and testing datasets.
- Scale the training and testing features datasets by creating a StandardScaler instance, fitting it to the training data, then using the transform function.

2. Compile, Train, and Evaluate the Model
- Create a neural network model by assigning the number of input features and nodes for each layer using TensorFlow and Keras.
- Create hidden layers with appropriate activation function.
- Create an output layer with an appropriate activation function.
- Compile and train the model.
- Evaluate the model using the test data to determine the loss and accuracy.

3. Optimize the Model to achieve a target predictive accuracy higher than 75%


---------------------
## Results
---------------------

### 1. Data Preprocessing

1. What variable(s) are the target(s) for your model?
- Variable 'IS_SUCCESSFUL' is the target variable for the model, such that '1' is reprsentative of successful.

2. What variable(s) are the features for your model?
- 'IS_SUCCESSFUL' is the feature column chosen for the model.

3. What variable(s) should be removed from the input data because they are neither targets nor features?
- Variables 'EIN' and 'Name' can be removed from the input data because they are neither targets nor features
 
### 2. Compiling, Training, and Evaluating the Model

1. How many neurons, layers, and activation functions did you select for your neural network model?

![Screen Shot 2023-04-09 at 7 43 11 PM](https://user-images.githubusercontent.com/115905342/230801962-10b5cd4d-9b0c-494e-93c6-20ce940e94e2.png)


2. Were you able to achieve the target model performance?

The target for the model achieved a 73% model performance despite optimization of the code.

3. What steps did you take in your attempts to increase model performance?

For the optimization, the following steps were taken:
-  Dropped additional columns ('EIN', 'NAME','AFFILIATION','SPECIAL_CONSIDERATIONS','USE_CASE','ORGANIZATION')
-  Incrased the number of application types to include values >150
-  Classification count > 200
-  Change activation hidden layer from ***relu*** to ***tanh***. 

However, the accuracy did not reach 75%. Accuracy, in fact, decreased to 63%.


---------------------
## Summary
---------------------


Describe how you could use a different model to solve the same problem, and explain why you would use that model (6)
