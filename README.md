# Treasure Island Character Co-occurrence Graph
This project analyzes the relationships and interactions among the main characters in the classic novel Treasure Island by Robert Louis Stevenson. By creating a character co-occurrence graph using the NetworkX library, we explore the structure and influence of characters within the story.

In this project, we engineered a character co-occurrence graph to map the interactions among 15 main characters in Treasure Island. The graph reveals mutual connections and helps quantify character influence through various centrality metrics. Additionally, we identified distinct communities within the character network using advanced algorithms.

*Before running the scripts, ensure you have the following Python packages installed:*
 -> networkx
 -> matplotlib
 -> pandas

The following centrality metrics were used to quantify the influence of characters within the graph:

Degree Centrality: Measures the number of direct connections a character has.
Betweenness Centrality: Indicates the frequency at which a character acts as a bridge along the shortest path between two other characters.
Closeness Centrality: Reflects how close a character is to all other characters in the graph.
PageRank Centrality: Ranks characters based on the structure of the network, considering both direct and indirect connections.

We used advanced algorithms like
 -> Clique Percolation
 -> Girvann Newmann
 -> Louvain Algorithm
 to detect communities within the character network. These communities represent clusters of characters who are more closely related to each other within the story.
