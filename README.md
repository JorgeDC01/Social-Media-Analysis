# Social Network Analysis 📝
The content is divided into two main projects:

## 1. Community Detection and Analysis
In this project, a meso-level analysis of a social network is conducted. Using a dataset of hashtags collected during the 2020 U.S. elections, tasks include:

- Calculating communities using the Leiden algorithm.
- Collapsing the graph to represent communities as nodes.
- Applying and visualizing different metrics to analyze community structures.
- Investigating central nodes and macro-level metrics to understand network structure.
- Exploring the trade-offs between overlapping and non-overlapping communities.
- Analyzing the content of the largest and smallest communities, including characterizing communities by prominent hashtags.

## 2. GNN for Paper Category Prediction
This project focuses on implementing and evaluating a Graph Neural Network (GNN) with skip connections. The goal is to predict the category of academic papers based on text features and citation networks. The dataset comprises:

- Nodes representing papers with binary feature vectors indicating dictionary terms.
- Edges representing citations between papers.
- Labels for training and validation to predict categories for test nodes.

