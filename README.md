# PageRank-Algorithm

#### Contents
### graph.py
This module takes care of generating and visualizing a randomised Graph object with a specified number of nodes and edges.
This graph will be treated as a Web-Network with links as edges and pages as the nodes.

#### pagerank.py
```get_all_ranks``` function in this module calculates the PageRank for all pages (nodes) using the attributes of a Graph object generated by ```generate_graph``` function in graph.py.

The PageRank algorithm used here is based on the ["Random Walk Method"](https://en.wikipedia.org/wiki/Random_walk).

### Usage Example
[Demo](https://github.com/SanchiMittal/PageRank-Algorithm/blob/main/outputs.ipynb)

### Creating the virtual environment 

Use [environment.yml](https://github.com/SanchiMittal/PageRank-Algorithm/blob/main/environment.yml) with conda package manager to create the pagerank-algo environment.

    $ conda env create -f environment.yml

Then activate the environment using:

    $ conda activate pagerank-algo

