# This is a classification project developed on imbalanced credit card transactions dataset.

### Approach:

### Used undersampling and oversampling techniques.

Undersampling: Undersampling refers to a group of techniques designed to balance the class distribution for a classification dataset that has a imbalance class distribution.
An imbalanced class distribution will have one or more classes with few examples (the minority classes) and one or more classes with many examples (the majority classes). It is best understood in the context of a binary (two-class) classification problem where class 0 is the majority class and class 1 is the minority class.
Undersampling techniques remove examples from the training dataset that belong to the majority class in order to better balance the class distribution, such as reducing the skew from a 1:100 to a 1:10, 1:2, or even a 1:1 class distribution.

Oversampling is the scenario where we will produce synthetic data for minority class with the available examples and make the distribution balanced.

### Precaution while sampling
But these oversampling and under sampling should be done while cross validation but not before cross validation because if we sample the data before CV, we are providing the artificial data to the validation which will lead us to wrong assumptions about the model. Instead if we sample the data while CV we can provide the real scenario for validation set which will give us the flavour of test scenario and can fine tune the model appropriately. **MAIN POINT TO KEEP IN MIND**.
