# DecisionTree-Implementation-and-pruning
Building a Classification Decision Tree Model on Breast Cancer dataset and applying Pruning technique to imporve decision tree model

# Definition:
Decision Tree algorithm falls under Supervised Learning algorithm that can be used for both Classification and Regression problem.
There for it becomes necessary for every aspiring Data scientist and Machine Learning Engineer to have good knowledge of Decision trees.

# The Role of Pruning in Decision Trees
Pruning is one of the techniques that is used to overcome our problem of Overfitting. Pruning, in its literal sense, is a practice which involves the selective removal of certain parts of a tree(or plant), such as branches, buds, or roots, to improve the tree’s structure, and promote healthy growth. This is exactly what Pruning does to our Decision Trees as well. It makes it versatile so that it can adapt if we feed any new kind of data to it, thereby fixing the problem of overfitting.

It reduces the size of a Decision Tree which might slightly increase your training error but drastically decrease your testing error, hence making it more adaptable.

# Decision Tree Pruning
The DecisionTreeClassifier provides parameters such as ***min_sample_leaf*** and ***max_depth*** to prevent a tree from overfitting. Cost complexity pruning provides another option to control the size of a tree. and we are going to use Post ***Pruning with Cost Complexity Pruning*** Technique to prune our decision tree. It reduces the size of a Decision Tree which might slightly increase your training error but drastically decrease your testing error, hence making it more adaptable.

In ***DecisionTreeClassifier***, this pruning technique is parameterized by the cost complexity parameter, ccp_alpha. Greater values of ***ccp_alpha increase*** the number of nodes pruned. Here we only show the effect of ccp_alpha on regularizing the trees and how to choose a ccp_alpha based on validation scores.
