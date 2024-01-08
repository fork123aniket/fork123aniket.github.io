---
layout: archive
title: "Production-ready ML Apps"
permalink: /deployed_apps/
author_profile: true
---

{% include base_path %}

---

Below is a list of my production-ready deployed apps. You can also check out a complete list of my other machine learning projects [here](https://github.com/fork123aniket?tab=repositories).

### Graph Representation Learning for Classification   [[Code](https://github.com/fork123aniket/End-to-End-Node-and-Graph-Classification-and-Explanation-App)] [[Deployed App](https://graph-explainability.streamlit.app/)]

<img align="right" src="../files/Graph Explainability.png" width=200px hspace="50"> 

- Developed an end-to-end Node and Graph classification app, which classifies a node or a graph on different datasets (*Cora* and *ENZYMES*).
- Utilized an abstract variant of *Binomial Distribution* to compute feature and edge importance weights that result in providing explained feature mask and explanation subgraph.
- Libraries/Framework: *PyTorch*, *PyTorch Geometric*, *DVC*, *MLFlow*, *Optuna*, and *Streamlit*

<hr style="border:2px solid gray">

### LLM-RAG-powered-QA-App   [[Code](https://github.com/fork123aniket/LLM-RAG-powered-QA-App)]

<img align="right" src="../files/App Architecture.jpg" width=200px hspace="50">

- Fine-tuned a 20B parameters Large Language Model (LLM) by leveraging the distributed training paradigm.
- Developed a production-ready, scalable Retrieval Augmented Generation (RAG)-based context-aware Question Answering (QA) App that first finds contexts relevant to the incoming query by implementing fast vector similarity search within the pre-defined embedding space and then sends these contexts alongside the query to the fine-tuned LLM model to generate the answer.
- Libraries/Framework used: *PyTorch*, *Transformers*, *Ray*, *LangChain*, and *FastAPI*
