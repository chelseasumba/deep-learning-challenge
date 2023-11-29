# deep-learning-challenge
Overview:
  The purpose of this analysis was to use the neural network to identify a pattern, and further analyze that pattern to determine relationships between the data. At the end of the analysis we were able to get the exact percentage of losses and accuracy that the model outputs for us. 
Results:
    For the data preprocessesing, I dropped the columns "NAME" and "EIN" and our targeted variables were the "APPLICATION_TYPE" and "CLASSIFICATION."
    I used 2 hidden layers and 1 outer layer. 80 neurons for the 1st layer and 30 for the 2nd layer. I used 2 activation functions which are "relu" and it is used for the hidden layers. The "sigmoid" function is commonly used for the outer layer. In one of the module assignments, they had an example of the layers, neurons, and etc. and I used that model as a guide to create my neural network model.
Summary: 
  The Neural Network model output losses and accuracy. The loss came out to 0.56. The purpose of the loss is to minimize this percentage so we can determine how efficicient the model is. The accuracy came out to be 0.727 and it determines the correctly classified samples. During the performance, the neural network went through 268 epochs with a loss of 0.56 and accuracy of 0.727. 
