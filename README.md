# Decision-Tree-and-Random-Forest

<div align="justify">
  
## Decision Tree
A Decision tree is a graphical representation of all the possible solutions to a decision based on certain conditions.<br />

### Terminologies
**Nodes**: Split for the value of a certain attribute.<br />
**Edges**: Edges are the outcome of a split to next node.<br />
**Root**: Root node is the base node of a tree. It is the node that performs the first split.<br />
**Leaf node**: Node that cannot be further segregated into further nodes. These are the terminal nodes that predict the outcome.<br />

### Intuition Behind Splits
Entropy and Information gain are the mathematical methods of choosing the best split.<br />
**Entropy**: It is the measure of impurity. It defines randomness in the data.<br />
**Information Gain**: Measures the reduction in entropy. It decides which attribute should be selected as the decision node.<br />

<div align="center"><img src="https://github.com/Harshita9511/Decision-Tree-and-Random-Forest/blob/master/entropy_and%20_gain.png" width="550" height="300" /></div>

## Random Forest
Random forest is an ensemble learning method for classification, regression and other tasks. It is a meta estimator that fits a number of decision tree classifiers on various sub-samples of the dataset and uses averaging to improve the predictive accuracy and control over-fitting.

## Dataset
The sinking of the Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, during it's maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.<br />
Data Source: [Titanic Dataset](https://www.kaggle.com/c/titanic)<br />
<br />

<div align="center"><img src="/attributes.png" width="550" height="350" /></div><br />
*pclass:* A proxy for socio-economic status (SES)<br />
1st = Upper<br />
2nd = Middle<br />
3rd = Lower<br />

*age:* Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5<br />

*sibsp:* The dataset defines family relations,<br />
Sibling = brother, sister, stepbrother, stepsister<br />
Spouse = husband, wife (mistresses and fiancés were ignored)<br />

*parch:* The dataset defines family relations,<br />
Parent = mother, father<br />
Child = daughter, son, stepdaughter, stepson<br />
Some children travelled only with a nanny, therefore parch=0 for them.<br />

</div>
