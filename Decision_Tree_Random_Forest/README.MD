# Decision Tree and Random Forest

Tree based algorithms are considered to be one of the best and mostly used supervised learning methods. 

It works for both categorical and continuous input and output variables.

A decision tree is a non-parametric supervised machine learning algorithm that can be used for both classification and regression problems. Random Forest is a tree-based machine learning algorithm that leverages the power of multiple decision trees for making decisions. As the name suggests, it is a “forest” of trees!

But why do we call it a “random” forest? That’s because it is a forest of randomly created decision trees. Each node in the decision tree works on a random subset of features to calculate the output. The random forest then combines the output of individual decision trees to generate the final output. The Random Forest Algorithm combines the output of multiple (randomly created) Decision Trees to generate the final output.

Random Forest is a versatile machine learning method capable of performing both regression and classification tasks. It is a type of ensemble learning method, where a group of weak models combine to form a powerful model.  The forest chooses the classification having the most votes (over all the trees in the forest) and in case of regression, it takes the average of outputs by different trees.

Disadvantages of Random Forest
It surely does a good job at classification but not as good as for regression problem as it does not give precise continuous nature predictions. In case of regression, it doesn’t predict beyond the range in the training data, and that they may over-fit data sets that are particularly noisy.
Random Forest can feel like a black box approach for statistical modelers – you have very little control on what the model does. You can at best – try different parameters and random seeds!

In simple words, random forest is more suitable for large dataset cases compare to decision tree, as decision tree is more easier to interpret algorithm.

Both the trees follow a top-down greedy approach known as recursive binary splitting. We call it as ‘top-down’ because it begins from the top of tree when all the observations are available in a single region and successively splits the predictor space into two new branches down the tree. The decision of making strategic splits heavily affects a tree’s accuracy. The decision criteria is different for classification and regression trees.

The algorithm selection is also based on type of target variables. Let’s look at the four most commonly used algorithms in decision tree:
1. Gini
2. Chi-Square
3. Entropy / Information Gain
4. Reduction in Variance (For continous variable/regression problems)

On the other hand if we use pruning, we in effect look at a few steps ahead and make a choice.



Source:
1. https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html

2. https://www.analyticsvidhya.com/blog/2016/04/tree-based-algorithms-complete-tutorial-scratch-in-python/?utm_source=blog&utm_medium=decision-tree-vs-random-forest-algorithm
