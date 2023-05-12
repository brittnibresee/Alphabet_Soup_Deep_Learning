# Alphabet_Soup_Deep_Learning


## Overview
The purpose of this project was to create a binary classifier that can predict whether or not an applicant will be successful if funded by the Alphabet Soup Charity. A dataset of 34.000 records was used to train and test the model using various steps to further optimize. These steps include binning and converting categorical data to numerical, using various combinations of activation methods, varying numbers of neurons and deep learning layers, and EPOCH's.

## Data Processing
1. The model targets the IS-SUCCESSFUL column using the below variables
![image](https://github.com/brittnibresee/Alphabet_Soup_Deep_Learning/assets/111385077/5819b081-1a69-42d4-99d8-04f5a2800246)

2. What variable(s) are the features of your model?
- APPLICATION TYPE & CLASSIFICATION

3. What variable(s) should be removed from the input data because they are neither targets nor features?
- The dropped non-beneficial columns were EIN, NAME, and ORGANIZATION.

## Compiling, Training, and Evaluating the Model

1. How many neurons, layers, and activation functions did you select for your neural network model, and why? 
- I added 20 neurons to layer 1 and layer 2 while adding a third layer and assigning it 15 neurons. I chose those numbers to avoid the default activation functions for the hidden layers.
- I chose the sigmoid function so I could take the negative values and maps them close to 0 in an effort to achieve higher accuracy. 

2/3. Were you able to achieve the target model performance? 
- I did not achieve the target model performance with the following steps and attempts:

### Attempt #1
- Dropping more or fewer columns. (Dropped the ORGANIZATION column)
- Creating more bins for rare occurrences in columns. 
(Changing the threshold of the APPLICATION TYPE and CLASSIFICATIONS columns)
- Increasing or decreasing the number of values for each bin.

![image](https://github.com/brittnibresee/Alphabet_Soup_Deep_Learning/assets/111385077/83ed448a-87fb-44b6-b687-e2d3010ad569)


### Attempt #2
- Add more neurons to a hidden layer. ( Adding more hidden nodes to hidden layers one and two.)
- Add more hidden layers. (Adding a third hidden layer.)

![image](https://github.com/brittnibresee/Alphabet_Soup_Deep_Learning/assets/111385077/336babee-330b-436f-b02e-b409d591535c)


### Attempt #3¶
- Use different activation functions for the hidden layers. (Change the activation function - for all the hidden layers to the sigmoid.)
- Add or reduce the number of epochs to the training regimen. (Increasing the epochs to 200.)

![image](https://github.com/brittnibresee/Alphabet_Soup_Deep_Learning/assets/111385077/6007720f-2406-489f-9208-b9f1c6da5177)


## Summary: My recommendation for working with this model would be to break down each step further. Given more time you could adjust the columns, layers, and functions until you've hopefully achieved the desired goal. Another method would be to use a different supervised learning model to see if achieving the desired goal is more efficient. 




