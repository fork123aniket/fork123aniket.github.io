---
layout: archive
title: "Open Source Contributions"
permalink: /opensourceproject/
author_profile: true
---

{% include base_path %}

### Clustering for Graph-structured Data using Graph Neural Networks   [[PyTorch Geometric](https://pytorch-geometric.readthedocs.io/en/latest/generated/torch_geometric.nn.dense.DMoNPooling.html#torch_geometric.nn.dense.DMoNPooling)/[Code](https://github.com/fork123aniket/Graph-Clustering-using-Graph-Neural-Networks-from-scratch)]

<img align="right" src="../files/pool.PNG" width=200px height=120px>

- This contribution relates to adding up a fast, yet effective graph clustering technique to PyTorch Geometric library
based on **Spectral Modularity Maximization**.
- A multi-layer graph convolutional network (GCN) is used to learn the hidden representations of each of the nodes
in the graph.
- Softmax activation is then applied to the output of GCN to obtain **soft**, **yet differentiable cluster assignments**
being made for the input graph.
- Designed and implemented unit tests to confirm the correctness of the clustering technique.
- Libraries/Framework: *PyTorch*, *PyTorch Geometric*, and *PyTest*

### Model-agnostic Graph Explainability   [[PyTorch Geometric](https://pytorch-geometric.readthedocs.io/en/latest/modules/contrib.html#torch_geometric.contrib.explain.GraphMaskExplainer)/[Code](https://github.com/fork123aniket/Model-agnostic-Graph-Explainability-from-Scratch)]

<img align="right" src="../files/gmask.PNG" width=300px height=100px>

- This contribution aims at adding a **Graph Explainability solution** powered by **hard-concrete distribution** to PyTorch Geometric.
based on **Spectral Modularity Maximization**.
- <p>Implemented a <i>post-hoc model-agnostic graph explainability</i> technique, which, at every hidden layer of the GNN model, computed explanation weights for<br> 
  every edge in the population and produced explanatory subgraph as output.</p>
- <p>Softmax activation is then applied to the output of GCN to obtain <i>soft</i>, yet<br> 
  <i>differentiable cluster assignments</i> being made for the input graph.</p>
- <p>Implemented custom unit tests to ensure proper execution of the Graph<br>
  Explainability technique.</p>
- Libraries/Framework: *Numpy*, *tqdm*, *PyTorch*, *PyTorch Geometric*, and *PyTest*
  
### Relational Graph Attention Networks   [[PyTorch Geometric](https://pytorch-geometric.readthedocs.io/en/latest/generated/torch_geometric.nn.conv.RGATConv.html#torch_geometric.nn.conv.RGATConv)/[Code](https://github.com/fork123aniket/Relational-Graph-Attention-from-Scratch)]

<img align="right" src="../files/rgat.PNG" width=300px height=200px>

- This contribution relates to bringing attention to heterogeneous (relational) graphs and incorporating this
relation-aware attention operator into PyTorch Geometric Library.
- Offers two different mechanisms to compute attention for relational graphs, i.e. **within-relation** and **across-relation**.
- This implementation also provides four different cardinality preservation options (**additive**, **scaled**, **f-additive**, and
**f-scaled**) to further improve attention computation for the heterogeneous graphs.
- Wrote custom unit tests to verify the technique’s accuracy.
- Libraries/Framework: *torch-scatter*, *torch-sparse*, *PyTorch*, *PyTorch Geometric*, and *PyTest*
