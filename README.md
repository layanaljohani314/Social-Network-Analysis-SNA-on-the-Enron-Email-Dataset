## Enron Network Analysis & Link Prediction
## Overview
This project performs an in-depth Social Network Analysis (SNA) on the Enron Email Dataset. By transforming over 47,000 email records into a multidimensional graph, we uncover the hidden organizational power dynamics, identify key influencers, and predict future communication links using machine learning principles.

## Key Features
Scalable Graph Construction: Developed a network with 8,936 nodes and 10,035 edges using NetworkX.

1. Influence Metrics: Ranked key employees using three core centrality measures:

2. PageRank: To find the most "prestigious" figures.

3. Betweenness: To identify the "gatekeepers" of information.

4. Degree: To measure raw connectivity and activity.

5. Link Prediction: Implemented the Jaccard Coefficient algorithm to predict potential future collaborations between employees who haven't interacted yet.

6. Automated Visualization: High-resolution export of network maps and statistical distributions.

## Tech Stack
Language: Python 3.x

- Core Libraries: * NetworkX: Graph theory and network algorithms.

- Pandas: Data manipulation and cleaning.

- Matplotlib & Seaborn: Professional data visualization.

- Community-Louvain: For community detection and clustering.

## Key Insights
- The Power Hubs: Identified individuals like Sally Beck as central hubs with the highest PageRank and Degree.

- Information Gatekeepers: Found critical "bridges" (high Betweenness) whose absence would lead to communication breakdown between departments.

- Predictive Success: Successfully identified pairs of employees with a >50% probability of needing future collaboration based on mutual neighbors.

## Visualizations Produced
The analysis generates the following assets:

clear_enron_network.png: A filtered, force-directed graph of the top 25 influencers.

top_influencers_bar_chart.png: A ranked comparison of employee connectivity.

degree_distribution.png: An analysis of the network's density and connectivity spread.


## Conclusion
This project demonstrates that organizational hierarchy is often different from the "communication hierarchy." By analyzing the Enron corpus, we successfully mapped the real flow of influence, proving that Network Science is a powerful tool for corporate auditing, fraud detection, and team optimization.