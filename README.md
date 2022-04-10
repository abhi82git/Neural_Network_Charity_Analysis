# Neural_Network_Charity_Analysis

## Data Preprocessing
For this analysis and model, the target is  IS_SUCCESSFUL field.

### The following variable(s) are features

- ORGANIZATION
- STATUS
- INCOME_AMT
- ASK_AMT
- APPLICATION_TYPE
- AFFILIATION
- CLASSIFICATION
- USE_CASE

### The following variable(s) should be removed:
- NAME
- EIN
- SPECIAL_CONSIDERATIONS

### Compiling, Training, and Evaluating the Model

**Model Configuration:**

* hidden_nodes_layer1 = 80
* hidden_nodes_layer2 = 30
* number_input_features = len(X_train_scaled[0]) (43 in regular model, 42 in optimized)


### This model acheived 72.85% accuracy with several attempts to incraese the accuracy including:

- Increased the number of hidden nodes in layer 1 and 2
- Increasing the number of hidden layers to include a 3rd
- Changed the activation functions: tried lisigmoid
- Removed additional nois element - SPECIAL_CONSIDERATION