# Machine-Learning-using-Decision-Tree-for-Marketing-Analysis
Why entropy in decision trees? In decision trees, the goal is to tidy the data. You try to separate your data and group the samples together in the classes they belong to. You know their label since you construct the trees from the training set. You maximize the purity of the groups as much as possible each time you create a new node of the tree (meaning you cut your set in two). Of course, at the end of the tree, you want to have a clear answer. Now on focusing at the depth changeable here what was found: at depth of 1: the shape is too short in two results and the entropy is closer to each other and they both close to 1 with Accuracy of 0.0.5936940164815478.

at depth of 2: the shape got too much leafs and with entropy that three of them got closer to 1 except one got far from 1, with accuracy of 0.5965603726262988 .

at depth of 3: the shape got too much leafs and with entorpy of 85% closer to 1 where the rest far from gaining 1, with accuracy of 0.599068434252956 .

at depth of 4: the shape got too much leafs and with entropy of 90% closer to 1 where the rest also far from 1, with accuracy of 0.6005016123253314 , and that shows the more we add on the depth the more we get closer to 1 from the accuracy and some of the leafs also gets to 1 but there still noisy data set .

at depth of 5: the shape gots too many leafs and with entropy 95% closer to 1 where the rest gets to 0 or in between, with accuracy 0.6176997491938373, from what it looks like the more we add on depth the more the accuracy gets to complete 1.

Conclusion: Decision Tree Classification Decision tree builds classification or regression models in the form of a tree structure. It breaks down a dataset into smaller and smaller subsets while at the same time an associated decision tree is incrementally developed. The final result is a tree with decision nodes and leaf nodes. and also A decision tree is built top-down from a root node and involves partitioning the data into subsets that contain instances with similar values (homogenous) The depth of a decision tree is the length of the longest path from a root to a leaf. The size of a decision tree is the number of nodes in the tree .

