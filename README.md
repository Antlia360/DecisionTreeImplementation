# Decision Tree

You can get the dataset from 'decision-tree.csv' file.

Decision trees are graphical models that make decisions based on conditions, branching into outcomes or actions. They represent choices in a tree-like structure, aiding in classification or regression tasks by recursively partitioning data based on features, enabling interpretable and effective decision-making.

## 1. Data Preparation

- Split the dataset into 80% for training and 20% for testing.
- Normalize/Regularize data if necessary.
- Encode categorical variables using appropriate encoding method if necessary.

## 2. ID3 Decision Tree Algorithm

Implement the standard ID3 Decision tree algorithm using Information Gain to choose which attribute to split at each point. Stop splitting a node if it has less than 10 data points. Do NOT use scikit-learn for this part.

## 3. Reduced Error Pruning

Perform reduced error pruning operation over the tree obtained in (2). Plot a graph showing the variation in test accuracy with varying depths. Print the pruned tree obtained in hierarchical fashion with the attributes clearly shown at each level.

## 4. Evaluation Metrics

Report the mean macro accuracy, macro precision, and macro recall for the classifier. You may or may not use the scikit-learn implementations for computing these metrics.
