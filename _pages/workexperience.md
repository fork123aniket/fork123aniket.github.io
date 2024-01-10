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
  - Built a machine learning platform from scratch for monitoring and tracking the traversed path of vessels.
  - Implemented various regressive prediction algorithms such as feedforward networks, support vector regression, etc. as a part of the platform to predict the 	movement of vessels in terms of multi-output regressive values (longitudes and latitudes).
  - Implemented automated _MS Azure machine learning pipelines_ to fulfill various purposes: (i) pulling data (containing 39 features for each of the 120k 		vessels) from the PostgreSQL database; (ii) training and evaluating the regression algorithm; (iii) to implement efficient batch-inference method to 		predict regressive outputs; (iv) to deploy the platform using _Azure CI/CD actions_ that made the platform accessible to more than 2k customers in 		real-time.
  - Integrated an intuitive data visualization framework, built using the _Dash-Plotly_ library, into the platform for creating intuitive as well as 			user-interactive visualizations to discover daily patterns in moving directions of vessels that could further aid our prediction algorithm.
  - Implemented an explainability solution by computing _Shapley Additive Explanation_ values for the features present in the dataset using the _Scikit-Learn_ 		library. Features that had higher _Shapley_ values were considered more important for the prediction made by the prediction algorithm.

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
  - Worked on creating a framework to transform the domain-specific ontologies into large-scale enterprise heterogeneous knowledge graphs (each comprises billions 	of nodes and edges connecting them). The framework consumes an ontology as a property graph (unique to different domains), models the various available 	relations in the knowledge graph using a multi-layered Relational Graph Convolutional Network (RGCN), and generates a domain-level importance weight for 	each relation present in the input relational graph as output.
  - To make the overall approach interpretable, introduced an explainability component in the framework to produce human-intelligible explanations for every single 	prediction being made for the input knowledge graph.
  - Developed and analyzed an automated approach to further evaluate GNN explanations to boost their applicability to end users, thereby promoting the creation of 	more complex as well as trusted AI systems for the Graph-structured domain. Work got published in the [<ins>**_Explainable AI Workshop at ICML 2021_**</ins>](https://arxiv.org/html/2107.08821#:~:text=title%3A%20towards%20automated%20evaluation%20of%20explanations%20in%20graph%20neural%20networks).
  - The developed framework was also employed to create a novel large-scale graph representation learning dataset called the _TACRED people_ dataset, which is 		being used by other teams in the lab to accelerate graph ML research.
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
  - Developed a novel unsupervised contrastive learning-based approach for the detection of similar bugs to facilitate
	faster log analysis. The approach extracts documents from the corpus of bug text and then implements Text Variational Autoencoders (T-VAEs)-based 		unsupervised anomaly detection technique to detect anomalies in the bugs corpus. Subsequently, learns a latent representation
	using a pre-trained BERT language model to form a document embedding for each document, and then measures
	the degree of similarity between these learned document embeddings of all extracted documents using newly
	proposed Word Centroids (WC) and Word Mover Distance (WMD) algorithms.
  - Upon obtaining the semantic-similarity scores, the approach clusters the similar bugs together based on semantic
	textual similarity indexing, which is governed by these computed scores.
  - Included main measures to evaluate the approach (e.g. novel and repeated). Experiments conducted on the
	synthetic bugs corpus strongly recommended the complete elimination of manual detection of similar bugs.

<hr style="border:2px solid gray">

<img align="right" src="../files/newibmsystemstorage.png" width=200px height=100px>

**Organization: *IBM Systems Development Lab, India***
- ***Apr 2022 - June 2023: Software Developer***
  - Created a multivariate time series-based neural learning framework for predicting the capacity of storage systems.
  - Utilized generic machine learning algorithms (LSTM, GRU, and RNN) to impeccably predict run-out memory times of storage systems in the resources 	pool.
  - Developed a novel approach to segment storage systems based on their respective predicted behaviors in terms of average growth in usable capacity over a 		specific forecasting window period, which in turn helped fill the missing data present in the time series.
  - Designed and implemented pipelines for various stages of development, starting from extracting high-dimensional data in the form of multivariate time series 	(with underlying non-continuous dynamic) from a storage data lake to deploying the whole approach as a fully functional ML-powered product accessible to 	numerous customers. Work done in close collaboration with *IBM Research, Almaden*.

