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

- Developed and deployed an end-to-end Node and Graph classification app, enabling real-time node or graph classification on different datasets (*Cora* and *ENZYMES*).
- Utilized an abstract variant of *Binomial Distribution* to compute feature and edge importance weights that result in providing explained feature mask and explanation subgraph.
- Libraries/Framework: *PyTorch*, *PyTorch Geometric*, *DVC*, *MLFlow*, *Optuna*, and *Streamlit*
- Below video shows the deployed Graph Representation Learning app in action:

<iframe width="700" height="300" src="https://github.com/fork123aniket/fork123aniket.github.io/assets/92912434/ae74e66a-2057-429e-bc68-23e60e1c8ea7" frameborder="0" allowfullscreen></iframe>

<hr style="border:2px solid gray">

### LLM-RAG-powered-QA-App   [[Code](https://github.com/fork123aniket/LLM-RAG-powered-QA-App)]

<img align="right" src="../files/App Architecture.jpg" width=200px hspace="50">

- Fine-tuned a 20B parameters Large Language Model (LLM) in a multi-GPU cluster environment by leveraging the distributed training paradigm.
- Developed a production-ready, scalable Retrieval Augmented Generation (RAG)-based context-aware Question Answering (QA) App that first finds contexts relevant to the incoming query by implementing fast vector similarity search within the pre-defined embedding space and then sends these contexts alongside the query to the fine-tuned LLM model to generate the answer.
- Implemented scalable major ML workloads for contexts (load, embed, and index the contexts in the vector database) across multiple workers with different compute resources and served the LLM App in a highly robust and scalable manner.
- Libraries/Framework used: *PyTorch*, *Transformers*, *Ray*, *LangChain*, and *FastAPI*
- Below video shows the deployed LLM app in action:

<iframe width="700" height="300" src="https://github.com/fork123aniket/fork123aniket.github.io/assets/92912434/df0a2876-3033-4cbb-b006-63529db139c7" frameborder="0" allowfullscreen></iframe>
