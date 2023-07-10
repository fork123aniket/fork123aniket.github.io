---
layout: archive
title: "Open Source Contributions"
permalink: /opensourceproject/
author_profile: true
---

{% include base_path %}

---

### Clustering for Graph-structured Data using Graph Neural Networks   [[PyTorch Geometric](https://pytorch-geometric.readthedocs.io/en/latest/generated/torch_geometric.nn.dense.DMoNPooling.html#torch_geometric.nn.dense.DMoNPooling)/[Code](https://github.com/fork123aniket/Graph-Clustering-using-Graph-Neural-Networks-from-scratch)]

<img align="right" src="../files/pool.PNG" width=200px height=120px hspace="50">

- This contribution relates to adding up a fast, yet effective graph clustering technique to *PyTorch Geometric* library
based on **Spectral Modularity Maximization**.
- A multi-layer graph convolutional network (GCN) is used to learn the hidden representations of each of the nodes
in the graph.
- <p>Softmax activation is then applied to the output of GCN to obtain <i>soft</i>, yet <i>differentiable<br>
  cluster assignments</i> being made for the input graph.</p>
- Designed and implemented unit tests to confirm the correctness of the clustering technique.
- Libraries/Framework: *PyTorch*, *PyTorch Geometric*, and *PyTest*

### Model-agnostic Graph Explainability   [[PyTorch Geometric](https://pytorch-geometric.readthedocs.io/en/latest/modules/contrib.html#torch_geometric.contrib.explain.GraphMaskExplainer)/[Code](https://github.com/fork123aniket/Model-agnostic-Graph-Explainability-from-Scratch)]

<img align="right" src="../files/gmask.PNG" width=300px height=100px hspace="50">

- This contribution aims at adding a **Graph Explainability solution** powered by **hard-concrete distribution** to *PyTorch Geometric*.
based on **Spectral Modularity Maximization**.
- <p>Implemented a <i>post-hoc model-agnostic graph explainability</i> technique, which,<br> 
  at every hidden layer of the GNN model, computed explanation weights for<br> 
  every edge in the population and produced explanatory subgraph as output.</p>
- <p>Softmax activation is then applied to the output of GCN to obtain <i>soft</i>, yet<br> 
  <i>differentiable cluster assignments</i> being made for the input graph.</p>
- <p>Implemented custom unit tests to ensure proper execution of the Graph<br>
  Explainability technique.</p>
- Libraries/Framework: *Numpy*, *tqdm*, *PyTorch*, *PyTorch Geometric*, and *PyTest*
  
### Relational Graph Attention Networks   [[PyTorch Geometric](https://pytorch-geometric.readthedocs.io/en/latest/generated/torch_geometric.nn.conv.RGATConv.html#torch_geometric.nn.conv.RGATConv)/[Code](https://github.com/fork123aniket/Relational-Graph-Attention-from-Scratch)]

<img align="right" src="../files/rgat.PNG" width=300px height=200px hspace="50">

- This contribution relates to bringing attention to heterogeneous (relational) graphs and incorporating this
relation-aware attention operator into *PyTorch Geometric* Library.
- Offers two different mechanisms to compute attention for relational graphs, i.e. **within-relation** and **across-relation**.
- <p>This implementation also provides four different cardinality preservation options<br>
  (<b>additive</b>, <b>scaled</b>, <b>f-additive</b>, and <b>f-scaled</b>) to further improve attention<br> 
  computation for the heterogeneous graphs.</p>
- Wrote custom unit tests to verify the technique’s accuracy.
- <p>Libraries/Framework: <i>torch-scatter</i>, <i>torch-sparse</i>, <i>PyTorch</i>, <i>PyTorch Geometric</i>, and<br>
  <i>PyTest</i></p>
