# Our Machine Learning Model consists of some steps:
1. Loading the dataset  
2. Doing some statistics on the dataset
3. Pre-processing Stage:  
    * Missing Values
    * Factorize the dependent variable
    * Feature Scaling
4. Applying the classifiers:
    * K-NN Classifier
    * Logistic Regression Classifier
    * Naive Bayes Classifier
    
5. Comparing the results

## Loading the Data Set
```markdown
dataset <- read.csv("hcc-data.txt", header=TRUE, na.strings = "?")
```




