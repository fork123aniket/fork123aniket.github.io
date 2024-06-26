---
layout: archive
title: "Research & Work Experience"
permalink: /workexperience/
author_profile: true
---

{% include base_path %}

---

<img align="right" src="../files/ibmconsulting.png" width=200px>

**Organization: *IBM Consulting, India***
- ***Nov 2018 - July 2020: Data Scientist***
  - Built a machine learning platform from scratch for monitoring and tracking the traversed path of 120k vessels.
  - Wrangled 1.5TB of vessel trading data (containing 39 features for each of the 120k vessels) stored in the Synapse database to train a Machine Learning 		regressive prediction algorithm and implemented an offline batch inference method for vessel trajectory prediction (in terms of longitudes and 			latitudes), which reduced the overall vessel traversal logistics time by 27%.
  - Optimized the developed ML platform by developing and including an explainability solution to identify influential features in the data for the prediction 		algorithm, resulting in improved trained ML model accuracy from 65% to 86%.
  - Integrated a data visualization framework, built using the _Dash-Plotly_ library, into the platform for creating intuitive as well as user-interactive 		visualizations and launched the developed machine learning platform for production use, allowing 2k+ end clients to discover, on the fly, daily patterns 	in vessels movement and track the regular impact of vessel trades on liquidity.

<hr style="border:2px solid gray">

<img align="right" src="../files/tudortmund.png" width=200px hspace="10">

**Organization: *Technical University of Dortmund, Germany***
- ***Dec 2020 - June 2021: Research Intern***
  - Designed and implemented a unique post-hoc model-agnostic Graph Neural Networks (GNNs) explainability framework. Unlike other traditional GNN explainability 	methods, the implemented approach does not require retraining to generalize explanations to new instances for node and graph classification, and link 		prediction tasks.
  - The framework takes a trained GNN model along with some meta-data information of the input graph as input, computes layer-wise edge importance weights, and 	outputs an explanatory subgraph.
  - The implemented GNN explanation framework is available on PyTorch Geometric. [(<ins>**_link_**</ins>)](https://pytorch-geometric.readthedocs.io/en/latest/generated/torch_geometric.explain.algorithm.GraphMaskExplainer.html#torch_geometric.explain.algorithm.GraphMaskExplainer)

<hr style="border:2px solid gray">

<img align="right" src="../files/ibmresearch.png" width=200px>

**Organization: *IBM Research, India***
- ***July 2020 - Dec 2022: Research Associate***
  - Worked on creating a framework to transform the domain-specific ontologies into large-scale enterprise heterogeneous knowledge graphs (each comprises billions 	of nodes and edges connecting them). The framework consumes an ontology as a property graph (unique to different domains), models the various available 	relations in the knowledge graph using a multi-layered Relational Graph Convolutional Network (RGCN), and generates predicted label for each domain-level 	entity in the property graph as output.
  - To make the overall approach interpretable, introduced an explainability component in the framework to produce human-intelligible explanations for every 		single prediction being made for the input knowledge graph.
  - Proposed a novel automated approach to evaluate GNN explanations to boost the reliability of predictions made by complex ML models applied to the Graph-		structured data domain. Work was published in the [<ins>**_Explainable AI Workshop at ICML 2021_**</ins>](https://arxiv.org/html/2107.08821#:~:text=title%3A%20towards%20automated%20evaluation%20of%20explanations%20in%20graph%20neural%20networks).
  - Deployed the developed framework as a production-ready API that was also employed to create a novel large-scale graph representation learning dataset called 	the _TACRED people_ dataset, which is being used by other teams in the lab to accelerate graph ML research.
  - Developed and implemented an unsupervised and computationally light framework that facilitates clustering to
	partition each heterogeneous graph associated with every single entity present in Master Data to generate the
	smallest possible graph sub-structures for each entity having only monumental similar nodes clustered together.
	Moreover, the framework takes into account the primitive structure as well as node embeddings of each entity’s
	heterogeneous graphs to cluster the nodes according to the graph topology (nodes in the same cluster should be
	strongly connected) and to the node features (nodes in the same cluster should have similar features).

<hr style="border:2px solid gray">

<img align="right" src="../files/ibmresearchzurich.png" width=200px>

**Organization: *IBM Research, Zurich***
- ***Feb 2021 - Dec 2021: Research Associate***
  - Developed a novel unsupervised contrastive learning-based approach for the detection of similar bugs on 3TB of unstructured
	bug text corpus to facilitate faster log analysis.
  - The approach extracts documents from the corpus of bug text and then implements Text Variational Autoencoders (T-VAEs)-
	based unsupervised anomaly detection technique to detect anomalies in the bugs corpus. Subsequently, learns a latent
	representation using a fine-trained BERT language model to form a document embedding for each bug document, and then
	measures the degree of similarity between these learned document embeddings of all extracted documents using novel Word
	Centroids (WC) and Word Mover Distance (WMD) algorithms.
  - Introduced quantization techniques to optimize this transformer-based similarity detection method, achieving a 38% smaller
	and 1.8× faster model and attaining 3× inference speedup and 5% improvement on both CPU and GPU.
  - Upon obtaining the semantic-similarity scores, the approach clusters the similar bugs together based on semantic textual
	similarity indexing, which is governed by these computed scores.
  - Included main measures to evaluate the approach (e.g. novel and repeated). Experiments conducted on the bugs corpus
	strongly recommended the 100% elimination of manual detection of similar bugs.
  - Rolled out the devised method as a real-time IBM Storage Insights product feature functionality, accessible to a broad customer
	spectrum.


<hr style="border:2px solid gray">

<img align="right" src="../files/newibmsystemstorage.png" width=200px height=100px>

**Organization: *IBM Systems Development Lab, India***
- ***Apr 2022 - June 2023: Software Developer***
  - Created a multivariate time series-based neural learning framework that utilizes generic machine learning algorithms (LSTM, GRU, and RNN) to impeccably 		predict run-out memory times of 300k+ storage systems in the resources pool, which resulted in the reduction of resource exhaustion time by 85%.
  - Developed a novel approach to segment storage systems based on their respective predicted behaviors in terms of average growth in usable capacity over a 		specific forecasting window period, which in turn helped fill the missing data present in the time series.
  - Designed and implemented pipelines for various stages of development, starting from extracting high-dimensional data in the form of multivariate time series 	(with underlying non-continuous dynamic) from a storage data lake to training ML time-series algorithms and predicting the storage systems’ capacities.
  - Created and optimized online inference approach to quickly serve the incoming requests for storage systems’ capacity predictions at scale, leading to a 70% 	decrease in the framework’s time to respond to user traffic requests.
  - Introduced the entire framework as a fully operational machine learning-driven IBM Storage Insights product feature with low latency and high throughput, 		serving numerous customers’ requests in real-time. Work done in close collaboration with *IBM Research, Almaden*.
