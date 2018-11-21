# VBA_Confusion-Matrix

# 1. General structure of the project.
Our project is using the confusion matrix to evaluate the accuracy of some models used to predict cancer in a group of patients, we will also present results graphically using a ROC graph.

# Worksheets:
- Help: Contains all the definitions to help the user have a better understanding of the confusion matrix and its results.
- Raw data: Contains the complete data base from which the predictions were made
- Actual Diag: The first column refers to the actual values of the cancer diagnosis for a sample of patients. The second column contains the predicted probability of a patient having cancer.

- Results: This worksheet shows the result of the confusion matrix and other metrics and results that can be  interesting for final user's analysis.  We also include the definition and explanation of basic concepts to have a better understanding of these results.

- ROC: Presents the ROC graph associated to the confusion matrix presented.


# Modules:
- Confusion_matrix: Contains the code used to calculate the confusion matrix and related statistics.
- ROC : Contains the code to build the calculations needed to build the ROC graph for the given model.
- M_Inizialization: Initializes the User Form and populates it


# 2. Comments received from the discussion:

 - Evaluate the possibility to include the code to make our own regression model and evaluate the accuracy of it with the confusion matrix and not just use the result data for certains models.
- In the user form, They suggest us to include buttrons for present the graph, accuracy of each model, confusion matrix, explanations of concepts, etc.
- Pay attention to the visual part and clarify all the concepts used in the development of the code, in order to make it as user friendly as possible.
