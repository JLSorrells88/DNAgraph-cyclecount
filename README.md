# Overview
This repository contains a computational tool for the flexible-tile model of DNA self-assembly. This software is the implementation of an algorithms outlined in (arXiv link).

# Setup
This code runs on Python 3. You can download the latest release here: https://www.python.org/downloads/. This code uses the Python packages numpy, sympy, and copy.

# DNAgraph-cyclecount
Given the adjacency matrix of a k-regular target graph, the value of k, and an initial oriented edge e labeled with a given bond-edge type, this code computes the number of n-cycles for n=3,4,5 for the original graph and the graph created when edge e is "swapped" with another oriented edge of the graph. For each of n=3,4,5 the code outputs the list of oriented edges for which a swap with edge e alters the number of n-cycles.

Computes the number of n-cycles in a graph for n=3,4,5 for DNA graphs with exchanged bond-edges.

# Usage
The recommended way to use this software is to use a code editor to input the adjacency matrix, value of k, and initial edge. 
