# Forrest Gump Project Social Network Analysis (SNA)
This repository contains the code and resources for conducting Social Network Analysis (SNA) on Forrest Gump's characters.

## Project Overview
This project focuses on Social Network Analysis (SNA) of the movie "Forrest Gump." It involves analyzing character interactions to understand the social structure within the film.

## Repository Contents

- **edges.csv**: Contains data representing the relationships between characters.
- **nodes.csv**: Includes information about the characters involved in the network.
- **gprops.csv**: Details various properties of the movie.
- **projectsnaforrestgump.ipynb**: A Jupyter Notebook that performs the SNA, including data loading, processing, and visualization. It consists of the actual project with all the analysis.
  
### **Key Analysis Summary**
- Construct an **undirected weighted graph** using `networkx`, where:
  - **Nodes** = characters,
  - **Edges** = scene co-occurrences,
  - **Weights** = interaction frequency.
- Compute **graph metrics**: number of nodes/edges, average degree, density, clustering coefficient, transitivity.
- Analyze **centrality measures**: degree, betweenness, closeness; visualize distributions.
- Detect **communities** using clustering algorithms and modularity-based methods.
- Generate **final network visualization**: adjust node sizes (centrality) and edge widths (interaction strength).
- Interpret **social dynamics and key relationships** in the character network.
