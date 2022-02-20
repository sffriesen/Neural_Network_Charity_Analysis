# Neural_Network_Charity_Analysis

## Overview of the Analysis
  This project was to use Machine Learning and Neural Networks to predict whether funding applicants (for company Alphabet Soup) would be successful if funded. The dataset provided included more than 34,000 organizations that have received funding in the past, including metadata about each organization. This data was preprocessed and prepared for the neural network by dropping unnecessary columns, binning data, encoding categorical variables, splitting into testing and training sets, and standardizing numerical variables.

  This preprocessed data was then fed into a neural network using Tensorflow Keras, with multiple hidden layers, nodes, and activation functions. The model then went through several optimization attempts, changing the number of hidden layers, nodes, and activation functions, as well as how many epochs were run, and bin sizes.

## Results
### Data Processing
  - What variable(s) are considered the target(s) for your model?
    - The target variable was the `IS_SUCCESSFUL` variable
  - What variable(s) are considered to be the features for your model?
    - The features were all other variables, asides from identification variables such as `NAME` and `EIN`

### Compiling, Training, and Evaluating the model
  - How many neurons, layers, and activation functions did you select for your neural network model, and why?
    - In the most successful optimization attempt, I used three hidden layers, with 8 neurons each, and all with the relu function. Adding the third hidden layer brought up the accuracy, as well as adding additional neurons. Using the sigmoid function brought the accuracy down in other attempts.
  - Were you able to achieve the target model performance?
    - Unfortunately, I was unable to achieve the target model performance, and was only able to bring accuracy up a small percentage.
  - What steps did you take to try and increase model performance?
    - I had tried several different methods of bringing up the model performance, including adding additional hidden layers, neurons, changing activation functions, changing bin sizes, and changing the number of epochs that the neural network ran through. All of these had slight impacts on the model performance.
