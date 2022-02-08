# Neural_Network_Charity_Analysis

### **Purpose**
Using a 34K organization dataset from Alphabet Soup’s business team, the following analysis gathers different features and data to develop a Neural-Network model to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

#

### **Results**
After reprocessing the database, the NN model was build using over 40 different features and two different layers as shown below:

**NN. Model Summary**<br>
![NN_Model](https://github.com/AxisAngeles/Neural_Network_Charity_Analysis/blob/main/Challenge/Resources/NN_Model.PNG)

**Considerations:**
* **Target variable:** The "Is Successfull" variable was chosen as target to train and test the model.
* **Model Features:** Over 40 different variables were used as input for the model: from application_type, affiliation, classification, to income and amount request data.
* **Removed variables:** "EIN" and "NAME" columns were not considered for the analysis.
* **Model sturcture:** The final model consists of 160 neurons divided among 2 hidden layers with "tahn" functions. This was selected due to the feature number (43) and the different itterations that were tested.
* **Final Performance:** The overall model achieved a 72% accuracy, below the expected 75% target.
* **Optimizations:** To optimize the model we first increased the number of nodes, worked on the data bins and changed the activation functions.

#

### **Conclussion**

At the end, the model achieved a regular performance and may still be improved by analyzing the different variables and features.
For example, some variables of major importance (conceptually) like "INCOME_AMT" are gather with a lot of null values or as categorical data instead of a more usefull numerical data.



