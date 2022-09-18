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
* Variable considered a target for my model: IS_SUCCESSFUL Column;
* Variables considered to be features of my model: Every column in the dataset except my target column IS_SUCCESSFUL and the dropped columns;
* Variables that were neither targets nor features and removed: Columns dropped were EIN and NAME because they are non-beneficial to the dataset. 
### Compile, Train, and Evaluate the Model 
My neural network model had 2 hidden layers and an output layer. My first hidden layer had 8 neurons and the second hidden layer had 5 layers. The first and second hidden layers have the activation function "relu" and "sigmoid" activation function for the output layer. 


![deliverable 1 snip](https://user-images.githubusercontent.com/104453593/190316487-1cf4fdd6-e6b1-41c2-ae65-35c3f57cb3a9.PNG)




Was the model able to achieve the target model performance?
* My neural network model had an accuracy of 73% and wasn't able to reach the target accuracy of 75%.

![deliverable 1 snip a](https://user-images.githubusercontent.com/104453593/190316515-43327d9c-5169-42cb-ad14-05aeee4691c3.PNG)



### Model Optimization
Three attempts taken to increase the model performance are:
* Attempt 1: Dropped an additional non-beneficial column that is the 'USE_CASE' column and the other columns stayed the same.
I used the same number of hidden layers and neurons (i.e. first hidden layer with 8 neurons and second hidden layer with 5 neurons) and an output layer. The accuracy of the model stayed at 73%.


![attempt 1 snip](https://user-images.githubusercontent.com/104453593/190316583-bda38cfc-862e-4753-b3b0-f64c4d6864ca.PNG)


![attempt 1 snip a](https://user-images.githubusercontent.com/104453593/190316621-33ca81ac-e292-454b-8f84-318c90024cdc.PNG)


* Attempt 2: To optimize the neural network model, I added an extra hidden layer, and additional neurons was added to all hidden layers (i.e. hidden layer 1=200 neurons, hidden layer 2 = 100 neurons and hidden layer 3 = 30 neurons). However, the accuracy stayed the same at 73%.

![attempt 2 snip](https://user-images.githubusercontent.com/104453593/190316636-2d3b8c74-b3db-4a8f-8e84-4a87a29f83f9.PNG)


![attempt 2 snipa](https://user-images.githubusercontent.com/104453593/190316653-9dc90c2d-2346-4ebc-bd37-6e3398332af4.PNG)


* Attempt 3: I changed the activation function to "tanh" for the output layer and changed the Epochs to 200. Also, the accuracy stayed at 73%.

![attempt 3 snip](https://user-images.githubusercontent.com/104453593/190316671-eda13b1f-e2ba-499a-b66e-6f8a38475ec4.PNG)


![attempty 3 snip a](https://user-images.githubusercontent.com/104453593/190316681-48c8a853-a6c7-4f91-9631-0f347184b4a2.PNG)


# Summary
My neural network model had an accuracy of 73% and wasn't able to reach the target accuracy of 75%. After optimization, the neural network model still had an accuracy of 73%. We can further optimize the neural network model by removing some features or non-beneficial columns from the dataset. Since this is a binary classification, a supervised machine learning model such as Random Forest Classifiers can be used because it is a robust and accurate model and have a faster performance than neural network model.
