# Graph-Analysis-with-NetworkX
Graph Analysis with NetworkX

## Notebook 1: Graph Types:

[Click here to see the notebook](https://github.com/KangboLu/Graph-Analysis-with-NetworkX/blob/main/01_graph_types.ipynb)

This notebook covers how to create the following graphs using NetworkX:
1. Undirected graph
2. Directed graph
3. Signed graph
4. Weighted graph
5. Multigraph
6. Bipartite Graph
7. Projected Graph

## Notebook 2: Spring Layout:

[Click here to see the notebook](https://github.com/KangboLu/Graph-Analysis-with-NetworkX/blob/main/02_graph_layouts_spring_layout.ipynb)

This notebook covers how to create visualization using the spring layout in NetworkX for Genshin Impact character network:  
![genshin_impact_character_network](https://github.com/KangboLu/Graph-Analysis-with-NetworkX/blob/main/graph_img/02_genshin_impact_character_network.png)

## Notebook 3: Graph Statistics:

[Click here to see the notebook part 1](https://github.com/KangboLu/Graph-Analysis-with-NetworkX/blob/main/03_graph_statistics_part_1.ipynb)

Notebook 3 part 1 covers how to calculate and interpret graph statistics for the following topic:
1. Triadic Closer:  
    * Local Clustering Coefficient (LCC)  
    * Global Clustering Coefficient (GCC): Average LCC and Transitivity  
2. Distance Measures:
    * Average Distance (Average Shortest Path Length)  
    * Eccentricity
    * Diameter
    * Radius
    * Center
    * Periphery

![Karate Network](https://github.com/KangboLu/Graph-Analysis-with-NetworkX/blob/main/graph_img/03_karate_graph_overall.png)

#### Karate Network with Center Visualized:
![Karate Network with Center Visualized](https://github.com/KangboLu/Graph-Analysis-with-NetworkX/blob/main/graph_img/03_karate_graph_center.png)

#### Karate Network with Periphery Visualized:
![Karate Network with Periphery Visualized](https://github.com/KangboLu/Graph-Analysis-with-NetworkX/blob/main/graph_img/03_karate_graph_periphery.png)

[Click here to see the notebook part 2](https://github.com/KangboLu/Graph-Analysis-with-NetworkX/blob/main/03_graph_statistics_part_2.ipynb)

Notebook 3 part 2 covers how to calculate and interpret graph statistics for the following topic:
1. Connectivity:  
    * Strongly Connected
    * Weakly Connected
2. Robustness:
    * Density
    * Node Connectivity
    * Min Node CUt
    * Edge Connectivity
    * Min Edge Cut
    * Isolates

![Sucrose Neighbors](https://github.com/KangboLu/Graph-Analysis-with-NetworkX/blob/main/graph_img/03_sucrose_neighbor_nodes.png)

#### Mutual Connection:
![Mutual Connection](https://github.com/KangboLu/Graph-Analysis-with-NetworkX/blob/main/graph_img/03_genshin_impact_mutual_connection.png)

#### Min Node Cut Example:
![Min Node Cut](https://github.com/KangboLu/Graph-Analysis-with-NetworkX/blob/main/graph_img/03_genshin_impact_min_node_cut.png)

#### Min Edge Cut Example:
![Min Edge Cut](https://github.com/KangboLu/Graph-Analysis-with-NetworkX/blob/main/graph_img/03_genshin_impact_min_edge_cut.png)

[Click here to see the notebook part 3](https://github.com/KangboLu/Graph-Analysis-with-NetworkX/blob/main/03_graph_statistics_part_3.ipynb)

Notebook 3 part 3 covers how to calculate and interpret graph statistics for the following topic:
1. Centreality (Node Importance):  
    * Degree Centrality
    * CLoseness Centrality
    * Node Betweenness Centrality
    * Edge Betweenness Centrality
    * PageRank Centrality with PageRank Algorithm
    * Auth and Hub Centrality with HITS Algorithm
2. Centrality Ranking by Averging Centrality Measures
#### Summary Table for Centrality Measures:
![Summary Table for Centrality Measures](https://github.com/KangboLu/Graph-Analysis-with-NetworkX/blob/main/graph_img/03_genshin_impact_centrality_summary.png)

#### Final Output of Averaging Centrality Ranking:
![Final Output of Averaging Centrality Ranking](https://github.com/KangboLu/Graph-Analysis-with-NetworkX/blob/main/graph_img/03_genshin_impact_average_rank.png)

## Notebook 4: Graph Link Prediction:

[Click here to see the notebook part 1](https://github.com/KangboLu/Graph-Analysis-with-NetworkX/blob/main/04_link_prediction_measures_part_1.ipynb)

Notebook 4 part 1 covers how to calculate and interpret the below common link prediction features: 
1. Non-community Based Measures
    * The Number of Common Neighbors
    * Jaccard Coefficient
    * Resource Allocation Index
    * Adamic-Adar Index
    * Preferential Attachment
#### Visualizing the Common Neighbors for Potential Connection between Node 2 and Node 33
![Common Neighbors for Potential Connection between Node 2 and Node 33](https://github.com/KangboLu/Graph-Analysis-with-NetworkX/blob/main/graph_img/04_karate_graph_common_neighbors_node_2_33.png)

