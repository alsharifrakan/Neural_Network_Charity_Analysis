# Neural_Network_Charity_Analysis

## **Overview of the Analysis**

With our knowledge of machine learning and neural networks, we’ll use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

in this project we will be having 4 main delverables as follows:
**Deliverable 1**: Preprocessing Data for a Neural Network Model
**Deliverable 2**: Compile, Train, and Evaluate the Model
**Deliverable 3**: Optimize the Model
**Deliverable 4**: A Written Report on the Neural Network Model (README.md)


## **Results**

### **Data Processing**
**Targeted Variable** : IS_SUCCESSFUL Column
**Features Variables** : Columns other than IS_SUCCESSFUL 
**Neither Targeted nor Features Variables** :  dropped comulmns such as EIN, NAME due to minor impact on the results


### **Compiling, Training, and Evaluating the Model**
- 2 Hidden layers
- first layer had 80 neurons
- second layer had 30 neurons
- The model was not able to achieve the target 75% with an accuracy of 69%
Steps taken to icnrease performance:
-Attempt 1 : Removed "USE_CASE" Column which resulted in accuracy dropping to 63%
-Attempt 2: Adding additional neuros and hidden layers which also dropped the accuracy to 53%
-Attempt 3: changed acctivation function to "tanh" which resulted in model accuracy dropping to 50%



## **Summary**
After opitmization the model had 50% accuracy which means that the model is overfitted . In addition,we could optimize our model by removing more features and/or adding more data in order to increase model accuracy. we could have used the random  forest classifier because it is a more robust  model and its also faster than neural networks avoiding the data to be overfitted as well.
