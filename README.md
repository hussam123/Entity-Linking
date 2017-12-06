# Entity-Linking


Many Entity Linking systems use collective graph-based methods to disambiguate the entity mentions within a document. Most of them have focused on graph construction and initial weighting of the candidate entities, less attention has been devoted to compare the graph ranking algorithms. In this work, we focus on the graph-based ranking algorithms, therefore we propose to apply five centrality measures: Degree, HITS, PageRank, Betweenness and Closeness. A disambiguation graph of candidate entities is constructed for each document using the popularity method, then centrality measures are applied to choose the most relevant candidate to boost the results of entity popularity method. We investigate the effectiveness of each centrality measure on the performance across different domains and datasets. Our experiments show that a simple and fast centrality measure such as Degree centrality can outperform other more time-consuming measures.


1. Hussam Hamdan, Jean-Gabriel Ganascia. [Graph Centrality Measures for Boosting Popularity-Based Entity Linking](https://arxiv.org/abs/1712.00044) arXiv 2017.
