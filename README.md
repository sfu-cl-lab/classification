# classification
Model-based propositionalization for classification. Under construction.

Transforms features learned with a relational BN model into a single table to be used in a classifier.

Input: 

1. A relational database
2. A target feature (column in the database or relationship table)
3. A learned Bayesian network (using [FactorBase](https://github.com/sfu-cl-lab/FactorBase).

Output: A single data table where each row represents a target instance and each column represents a conjunctive relational feature.
