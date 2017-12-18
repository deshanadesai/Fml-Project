# GreedyBoost: Boosting Algorithms in the Online Setting


We study online boosting - the task of converting any weak online learner into a strong online learner. Boosting can be viewed as trying to find a linear combination of weak hypotheses to minimize the total loss of the training examples. We experiment with several online boosting algorithms such as Online Adaboost [1], Smoothboost, OSBoost, OCPBoost, EXPBoost along with different weak learners and analyze their performance.

A drawback for the online algorithm is that the discriminative complexity of the classifier is limited, because the number of weak classifiers is fixed. Moreover, if we combine too many weak learners, the result can be dominated by poorly performing weak learners that shouldn't have been included. We propose to modify the Online Boosting algorithm suggested by N. C. Oza and S. Russell [1] to use the greedy strategy of starting with one weak learner and adding a new weak learner after each misclassification. We perform various experiments to compare the accuracy of such a model and comment on different variants of the greedy strategy used.

[1] N. C. Oza and S. Russell. Online Bagging and Boosting. In In Artificial Intelligence and Statistics 2001, pages 105–112. Morgan Kaufmann, 2001.
