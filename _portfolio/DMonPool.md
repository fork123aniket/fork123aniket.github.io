---
title: "Clustering for Graph-structured Data using Graph Neural Networks"
collection: opensource
---

- This contribution relates to adding up a fast, yet effective graph clustering technique to PyTorch Geometric library
based on **Spectral Modularity Maximization**.
- A multi-layer graph convolutional network (GCN) is used to learn the hidden representations of each of the nodes
in the graph.
- Softmax activation is then applied to the output of GCN to obtain **soft**, **yet differentiable cluster assignments**
being made for the input graph.
- Designed and implemented unit tests to confirm the correctness of the clustering technique.

[PyTorch Geometric](https://pytorch-geometric.readthedocs.io/en/latest/generated/torch_geometric.nn.dense.DMoNPooling.html#torch_geometric.nn.dense.DMoNPooling)/[Code](https://github.com/fork123aniket/Graph-Clustering-using-Graph-Neural-Networks-from-scratch)
