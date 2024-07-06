# Grouping based on learning method
- Supervised learning
- Unsupervised learning
- Semi-supervised learning
- Reinforcement learning

## Supervised learning
Supervised learning is an output prediction algorithm of new input data base on known pairwise data (input, output), this pairwise data also called (data, label). Supervised learning is most common algorithm in machine learning.

### Math theory
- Have set of input variable $X = \{x_{1}, x_{2}, ..., x_{n}\}$ and corresponding set of label $Y = \{y_{1}, y_{2}, ..., y_{n}\}$ ($xi, yi$ are vector).
- $(x_{i}, y_{i}) \in X \cdot Y$ is training data, from this training data we need to create a function that maps each element from the set $X$ to one element (approximately) of set $Y$:

    $y_{i} \approx f(x_{i}), \forall i = 1, 2, ..., N $ 
- Target is approximately function $f$ for if have new $x$ data we can caculate corresponding label $y = f(x)$

Supervised learning algorithm divided into 2 types:
- Classification: If label of input data are divided into finite group.
- Regression: If label not divide into groups but is a specific value.

## Unsupervised learning
In this algorithm, we don't know outcome or label and only have input data. algorithm will base on data structure to work. For example clustering or dimension reduction.

### Clustering
A problem of clustering all $X$ data into smaller group based on relatedness of datas on each group. For example, customer classification based on purchasing behavior.

### Association
A problem of finding the rule based on a lot of existing data. For example base on customer trends create a suggestion system.

## Semi-Supervised Learning

## Reinforcement Learning