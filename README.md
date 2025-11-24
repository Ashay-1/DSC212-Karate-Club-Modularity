DSC212 Research Assignment: Modularity on the Karate Club Graph
Course: DSC212 - Graph Theory Module
Student Name: Satyam Vedant
Roll Number: IMS24216
Date: November 20, 2025

Assignment Overview
This repository contains a complete implementation of recursive spectral modularity partitioning for community detection on the famous Karate Club social network. The assignment implements the spectral bipartition algorithm from scratch, visualizes community evolution, and tracks how centrality metrics change across iterations.

Objectives
Implement recursive spectral modularity partitioning from scratch

-Detect multiple communities in the Karate Club graph

-Visualize the graph after each split with different colors for communities

-Compute node metrics (degree, betweenness, closeness, clustering centrality)

-Plot metric evolution across iterations

-Analyze which nodes remain central and how community structure influences metrics

-> Repository Structure
text
.
├── DSC212_Assignment_Satyam_Vedant_IMS24216.ipynb  # Main Jupyter notebook
├── README.md                                        # This file
├── iteration_*.png                                  # Community visualization plots (generated)
├── *_evolution.png                                  # Metric evolution plots (generated)
└── *_heatmap.png                                   # Metric heatmaps (generated)
Requirements
Python Libraries
bash
pip install networkx numpy matplotlib
Required packages:

networkx (>= 2.5)

numpy (>= 1.19)

matplotlib (>= 3.3)

Python Version
Python 3.7 or higher

How to Run
Option 1: Jupyter Notebook
bash
jupyter notebook DSC212_Assignment_Satyam_Vedant_IMS24216.ipynb
Then run all cells in order (Cell → Run All)

Option 2: JupyterLab
bash
jupyter lab DSC212_Assignment_Satyam_Vedant_IMS24216.ipynb
Option 3: Google Colab
Upload the notebook to Goog

