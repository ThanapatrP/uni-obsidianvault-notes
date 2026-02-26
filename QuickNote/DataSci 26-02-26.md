## Decision tree
- *Node* represent field / feature
- *Edges (line)* represent value in Node
- *Leaf* represent final class prediction

## Feature filtering and selection
-> *Select feature that its leafs reduce impurity of the classes*


### Gini Impurity
*NOTE: performance on gini and entropy are not much different*

#### Formula : `GINI = 1 - P(YES)^2 - P(NO)^2`

0 -> **NO Impurity** (pure as fuck -> ==GOOD==)
0.5 -> **Equal mix** (->==BAD==)

"*the closer to 0 -> the better*"


### Decision Boundary
*Plane that split classes by data*
"Depth" -> time split

### Overfitting
when the *Decision Boundary* are **too sensitive** for data that it try to cover data that is spiking out of most of their class

-> Instead we should just ignore some data that is spiked out too much

by setting some limitation for splitting / branching would relieve this problem




