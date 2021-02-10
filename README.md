# Generalized QAOA to solve the weighted max cut problem
This algorithm applies QAOA to solve MaxCut for weighted graphs, finding the optimal cut given the input graph specifications (number of nodes and edges). In the notebook, I demonstrate the algorithm on the following weighted graph:

![](./images/download%20(1).png)

After applying the algorithm, we arrive at the probability distribution for the circuit over the optimal parameters:

![](images/download.png)

This algorithm is generalized and can be used to solve any MaxCut problem for a weighted graph, hope you find it useful. 

*Inspired by [Jack Ceroni's QAOA MaxCut implementation for unweighted graphs](https://lucaman99.github.io/new_blog/2020/mar16.html)*
### If the notebook is failing to load, try this [link](https://nbviewer.jupyter.org/github/Sinestro38/Using-QAOA-to-make-a-generalized-weighted-MaxCut-solver/blob/main/Weighted%20max-cut%20graph.ipynb) to view the notebook on NBViewer
