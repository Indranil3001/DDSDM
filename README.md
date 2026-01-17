📊 Data-Driven Strategic Decision Making
Social Network Analysis of Facebook Pages
📌 Project Overview

This project applies network science and data-driven analysis to study a social network of mutually liked Facebook pages. Using real-world data, the analysis explores network structure, centrality, robustness, community formation, and influence propagation to support strategic decision-making insights.

The project compares the real Facebook network with three well-known synthetic network models to better understand how real social networks behave.

🗂 Dataset

Source: Network Repository (GEMSEC – Graph Embedding with Self Clustering)

Collection Date: November 2017

Network Type: Blue-verified Facebook pages

Nodes: 5,908 Facebook pages

Edges: 41,729 mutual likes

Each node represents a Facebook page, and each edge represents a mutual like relationship between pages.

🧠 Network Models Analyzed

The real network is compared against the following models:

Real Facebook Network

Erdős–Rényi Random Graph

Barabási–Albert Scale-Free Network

Watts–Strogatz Small-World Network

This comparison helps identify which theoretical model best reflects real social media behavior.

📈 Network Properties & Metrics
🔗 Structural Characteristics

The network is highly connected

A single giant component exists across all models

The entire network is traversable

📊 Degree Distribution

The real network follows a power-law distribution

A small number of pages have very high influence

Most pages have low connectivity

The Barabási–Albert model most closely resembles the real network

📏 Path Length & Diameter

Network	Avg. Path Length	Diameter

Real Network	4.66	14

Erdős–Rényi	3.58	5

Barabási–Albert	3.23	5

Watts–Strogatz	17.36	38

🧩 Clustering & Density

Network	Avg. Clustering	Density

Real Network	0.385	0.00239

Erdős–Rényi	0.0023	0.00239

Barabási–Albert	0.0119	0.00236

Watts–Strogatz	0.6874	0.00237

🎯 Centrality Analysis

The project evaluates multiple centrality measures to identify influential nodes:

Degree Centrality

Eigenvector Centrality

PageRank

Closeness Centrality

Betweenness Centrality

🔑 Key Findings

Node 1864 has the highest degree centrality

Node 5800 ranks highest in closeness and betweenness centrality

These nodes act as influencers and bridges within the network

Synthetic models show significantly weaker centrality concentration

🛡 Network Robustness

Two robustness experiments were conducted:

Random node removal

Targeted removal of high PageRank nodes

Observations:

The real and scale-free networks are robust to random failures

They are highly vulnerable to targeted attacks

Random networks degrade more uniformly

🧑‍🤝‍🧑 Community Detection

Louvain Algorithm was applied

30 distinct communities were detected

Communities represent clusters of pages with strong internal connections

🔥 Influence Propagation

A Linear Threshold Model was used

Initially activated nodes caused cascading activations

Demonstrates how influence spreads strategically through key nodes

🛠 Tools & Technologies

Python

NetworkX

Pandas

Matplotlib

Jupyter Notebook

▶️ How to Run

Clone the repository

Open the notebook or related scripts

Run all cells sequentially in Jupyter Notebook or Google Colab

👤 Author

Indranil

📚 References

GEMSEC: Graph Embedding with Self Clustering (2019)

Network Repository – Facebook Page Networks

Indranil (2025), GitHub Project Repository[Uploading Data Driven Strategic Decision Making_GH1026152.docx…]()
