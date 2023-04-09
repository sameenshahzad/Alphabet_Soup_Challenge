# Alphabet Soup Analysis
----------------------

## Purpose

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
- 

## Results


Data Preprocessing

What variable(s) are the target(s) for your model?
What variable(s) are the features for your model?
What variable(s) should be removed from the input data because they are neither targets nor features?
Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
Were you able to achieve the target model performance?
What steps did you take in your attempts to increase model performance?
Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

## Summary



Describe how you could use a different model to solve the same problem, and explain why you would use that model (6)
