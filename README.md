# Neural_Network_Charity_Analysis

### Overview

  In this challenge we help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. In this data set we have more than 34,000 organizations that have received funding from Alphabet Soup over the years. We preprocessed the data for a Neural Network Model then we Compile, Train, and Evaluate the Model. After this we optimized it to see the accuracy.
  
### Results

  * What variable(s) are considered the target(s) for your model? 
        
        The variable is the IS_SUCCESSFUL column.
        
  * variable(s) that are considered to be the features for your model
       
       The features that we are using are every column except the ones that we will drop.
       
  * What variable(s) are neither targets nor features were removed

      We drop are the 'EIN' & 'NAME' 
      
  
### Compiling, Training, and Evaluating the Model
  
  * How many neurons, layers, and activation functions did you select for your neural network model

      This model is made with an input features & two hidden. The first hidden layer has 80 neurons, the second has 30 with an output layer. The first and second hidden layers have an activation function "relu" & the output layer is "sigmoid".

  * Was the model able to achieve the target model performance?

     The target for the model was 75% or above, I was not able to reach the target.

  * What steps were taken to try and increase model performance?

      I Tried changing the activation type, changing the number of epochs and changing the number of neurons in each layer, and adding hidden layers
      
      
### Summary

In the end we ended with a 72.8% accuracy. We tried to predict whether or not the project would be successful on all of the features that we used after dropping two 'EIN' and 'Name'. If we had more data i believe we could of improved the accuracy. Also having more specific data i believe we could of also improved the accuracy.
