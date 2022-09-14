# Neural_Network_Charity_Analysis
# Overview
For this project, I used Machine Learning and Neural Networks with the TensorFlow platform in Python to analyze and classify the prediction of successful applicants funded by Alphabet Soup.
This analysis was done using the following methods:
* Preprocessing Data for a Neural Network Model;
* Compile, Train, and Evaluate the Model;
* Optimize the Model.
# Resources
* Dataset: [charity_data.csv](https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-online/module_19/charity_data.csv)
* Softwares used: Jupyter Notebook
* Libraries: TensorFlow, Pandas, Scikit-learn
# Results
### Data Preprocessing
### Compile, Train, and Evaluate the Model 
My neural network model had 2 hidden layers and an output layer. My first hidden layer had 8 neurons and the second hidden layer had 5 layers. The first and second hidden layers have the activation function "relu" and "sigmoid" actication function for the output layer. 

Was the model able to achieve the target model performance?
* My neural network model had an accuracy of 73% and wasn't able to reach the target accuracy of 75%.


### Model Optimization
Three attempts taken to increase the model performance are:
* Attempt 1: Dropped an additional non-beneficial column that is the 'USE_CASE' column and the other columns stayed the same.
I used the same number of hidden layers and neurons (i.e. first hidden layer with 8 neurons and second hidden layer with 5 neurons) and an output layer. The accuracy of the model stayed at 73%.
* Attempt 2: To optimize the neural network model, I added an extra hidden layer, and additional neurons was added to all hidden layers (i.e. hidden layer 1=200 nuerons, hidden layer 2 = 100 neurons and hidden layer 3 = 30 neurons). However, the accuracy stayed the same at 73%. 
* Attempt 3: I changed the activation function to "tanh" for the output layer and changed the Epochs to 50. Also, the accuracy stayed at 73%.

# Summary
