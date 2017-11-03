# Adaptive Algorithms for Online boosting


We study online boosting - the task of converting any weak online learner into a strong online learner. Boosting can be viewed as trying to find a linear combination of weak hypotheses to minimize the total loss of the training examples, usually using functional gradient descent. We experiment with several online boosting algorithms such as Online BBM, Adaboost. OL, OSBoost and analyze their performance.

We further compare the online boosting algorithms and batch versions to find whether they converge to similar results given enough training data.  We also propose the usage of weak learners trained by offline boosting methods followed by a second round of online training to fine-tune the models as newer data becomes available. A drawback for the on-line algorithm,
is that the discriminative complexity of the classifier is limited, because the number of weak classifiers is fixed (since also the number of selectors is fixed). We propose to make an educated guess about the number of classifiers required by initially training weak classifiers in an offline setting on a small dataset followed by training using an online learning algorithm.
Finally, we compare how the speed of convergence and accuracy of such a model differs from a strictly online-based boosting algorithm. 
