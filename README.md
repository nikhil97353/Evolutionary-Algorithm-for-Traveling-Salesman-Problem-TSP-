Evolutionary Algorithm for Traveling Salesman Problem (TSP) with Graph Visualization
This project implements an Evolutionary Algorithm (EA) to solve the Traveling Salesman Problem (TSP), utilizing XML files that contain graph representations of various city maps. The project also includes visualizations of the cities and their connections using NetworkX and Matplotlib. The dataset includes two example XML files: burma14.xml and brazil58.xml.

Features
Graph Parsing: Reads the XML file representing cities and distances between them and constructs a graph using NetworkX.
EA for TSP: Implements an evolutionary algorithm to find near-optimal solutions for the TSP, including improved initialization, tournament selection, crossover, and mutation.
Visualization: Graph visualizations are generated for the city maps, showing city connections and distances.
Convergence Curve: Plots the convergence curve to track the fitness (total travel cost) over iterations.
Scatter Plot: Generates scatter plots to observe how population size influences the solution's fitness.
Getting Started
Prerequisites
To run this project, you will need the following dependencies:

Python 3.x
Libraries: xml.etree.ElementTree, networkx, matplotlib, numpy
You can install all the required libraries via the requirements.txt file.
