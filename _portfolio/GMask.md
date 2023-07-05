---
title: "Model-agnostic Graph Explainability"
collection: opensource
---

- This contribution aims at adding a **Graph Explainability solution** powered by **hard-concrete distribution** to PyTorch Geometric.
based on **Spectral Modularity Maximization**.
- Implemented a **post-hoc model-agnostic graph explainability** technique, which, at every hidden layer of the GNN model, computed explanation
weights for every edge in the population and produced explanatory subgraph as output.
- Softmax activation is then applied to the output of GCN to obtain **soft**, **yet differentiable cluster assignments**
being made for the input graph.
- Implemented custom unit tests to ensure proper execution of the Graph Explainability technique.

[PyTorch Geometric](https://pytorch-geometric.readthedocs.io/en/latest/modules/contrib.html#torch_geometric.contrib.explain.GraphMaskExplainer)/[Code](https://github.com/fork123aniket/Model-agnostic-Graph-Explainability-from-Scratch)
