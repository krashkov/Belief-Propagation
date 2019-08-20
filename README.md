# Belief Propagation

Probabilistic graphical models describe joint probability distributions in a way that allows to exploit the independence properties in representation. Given a probability distribution, it is important to solve several computational inference problems (finding conditional distribution, maximum a-posteriori etc). Belief propagation is a message-passing algorithm for performing such inference efficiently. If the topology of the graph is that of a tree or a chain, this algorithm computes the marginal distributions exactly. The modification for graphs with loops is called loopy belief propagation. The message update rules are no longer guaranteed to return the exact marginals, however BP fixed-points correspond to local stationary points of the Bethe free energy.

Algorithms and data structures are implemented in Python using ```numpy``` and ```igraph``` packages.


**Contents**

1. Summary of probabilistic graphical models and belief propagation
([view](https://nbviewer.jupyter.org/github/krashkov/Belief-Propagation/blob/master/1-SummaryPGMandBP.ipynb))
2. Implementation of factor data structure and corresponding operations, such as factor product, marginalisation and reduction
([view](https://nbviewer.jupyter.org/github/krashkov/Belief-Propagation/blob/master/2-ImplementationFactor.ipynb))
3. Implementation of probabilistic graphical model (factor graph) data structure
([view](https://nbviewer.jupyter.org/github/krashkov/Belief-Propagation/blob/master/3-ImplementationPGM.ipynb))
4. Implementation of belief propagation and loopy belief propagation algorithms
([view](https://nbviewer.jupyter.org/github/krashkov/Belief-Propagation/blob/master/4-ImplementationBP.ipynb))
