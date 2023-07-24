Graph Convolutional Networks (GCN) on Cora Dataset

This repository contains my implementation of Graph Convolutional Networks (GCN) on the Cora dataset. The goal of this project was to explore semi-supervised classification on graph-structured data using GCNs. The dataset was taken from Planetoid, and the initial codebase was referenced from the GitHub repository arshren/Graphs.

Dataset - Cora
The Cora dataset is a citation network where nodes represent documents, and edges represent citation links between the documents. The task is to classify the documents into one of seven classes, which makes it a multi-class classification problem. 

Graph Convolutional Networks (GCN)
GCN is a powerful approach for node classification tasks on graphs. It leverages graph structures to propagate information from labeled nodes to unlabeled nodes in a semi-supervised setting. The model employs a layer-wise aggregation mechanism to iteratively update node representations, capturing both local and global information from the graph.


Results
In my experiment, I achieved an accuracy of 81.10% on the test set after training the GCN model for 200 epochs. However, this result might not be optimal, and there is room for improvement.

Citation
If you use this codebase or the implementation of GCN in your research, please consider citing the original paper:

"SEMI-SUPERVISED CLASSIFICATION WITH GRAPH CONVOLUTIONAL NETWORKS" by Thomas N. Kipf and Max Welling.

Conclusion
This project demonstrates the application of Graph Convolutional Networks on the Cora dataset for semi-supervised node classification. The implementation can be improved by experimenting with various hyperparameters, model architectures, and data preprocessing techniques.