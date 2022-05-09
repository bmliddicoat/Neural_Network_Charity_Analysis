# Neural_Network_Charity_Analysis
## Overview 
The stakeholder, Beks, needs help in creating a binary classifier of predicting whether applicants will be successful if funded by Alphabet Soup.  A CSV with over 34,000 organization was used as the data for neural network.  The first steps were to preprocess this data for the neural network model.  When the data was effectively prepared, TensorFlow was used in designing the neural network.  
# Results: Using bulleted lists and images to support your answers, address the following questions.
## Data Preprocessing
* Variable considered the target: Column IS_SUCCESSFUL 
* Variables are the features: 'APPLICATION_TYPE','AFFILIATION','CLASSIFICATION','USE_CASE','ORGANIZATION','INCOME_AMT','SPECIAL_CONSIDERATIONS'
* Variables are neither targets nor features removed from the input data: EIN AND NAME
### Compiling, Training, and Evaluating the Model
* First attempt used two hidden layers (80 neurons and 30 neurons).  Activation for these hidden layers was "relu".  The outer layer was set to "sigmoid"
![alt text]()
* I was unable to achieve the target level of 75%.  The first attempt was at 65%.  I was only able to achieve 72.5% accuracy. 
 
 Original Attempt 
 ![alt text]()
last Attempt
 ![alt text]()
* I increased the number of hidden layers and associated neurons to help increase accuracy.  
![alt text]()
# Summary: 
The deep learning model was unable to achieve the desired level of 75% accuracy.  From the first attempt to last attempt, there was increase of 7% (65% TO 72.5%).  If another attempt was done, adjusting the data to determine outliers, use different activation functions and manipulating the number of epochs to the training program.  

One potential model that could be used is supervised machine learning algorithm, the Random Forest Model.  This model specializes in classification and regression problems.  The ability of the model in classification could help determine successful and unsuccessful programs.    
