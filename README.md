# Neural_Network_Charity_Analysis

## Background and Purpose

With my knowledge of machine learning and neural networks, I will use the features in the provided dataset to help create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. From Alphabet Soup’s business team, I received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. 

My goal is to :

* Preprocess Data for a Neural Network Model
* Compile, Train, and Evaluate the Model
* Optimize the Model



## Results 

* Data Preprocessing

  * What variable(s) are considered the target(s) for your model?
  
    * That would be the variable which shows if money was used effecitvely which is : "Is-Succesful" column.
  
  * What variable(s) are considered to be the features for your model?
  
    * Feautures : EIN,	NAME,	APPLICATION_TYPE,	AFFILIATION	CLASSIFICATION,	USE_CASE,	ORGANIZATION,	INCOME_AMT,	ASK_AMT	IS_SUCCESSFUL
    
  * What variable(s) are neither targets nor features, and should be removed from the input data?
  
    * SPECIAL CONSIDERATIONS AND STATUS because both are not significnat values.
  
* Compiling, Training, and Evaluating the Model

  * How many neurons, layers, and activation functions did you select for your neural network model, and why
  
    * Im not sure about the number of neurons but there are three layers which they are contained within.
    
  * Were you able to achieve the target model performance?
  
    * Yes i was able to achieve target model performance (78.6%)
  
  * What steps did you take to try and increase model performance?
  
    * The biggest change that made the model performance more efficient was converting the NAME column to data points.
    
    
 ## Summary and Conclusion
 
WE learned in this deep learning model that by adding extra layers and using different activation functions that we can get the accuracy of the model above seventy-five percent which in turn means that accurately identify the test points. Im not sure exactly what model/ algorithm would make this more accurate, either a random forest algorithm or a SVM (Support Vector Machine) but it needs a hyperparameter search to determine the best learning parameters.
