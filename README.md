## Graph

A graph is a representation of a set of objects where some pairs of objects are connected by links. 
The interconnected objects are represented by mathematical abstractions called vertices, 
and the links that connect some pairs of vertices are called edges.

- Graph() creates a new, empty graph.
- add_vertex(vert) adds an instance of Vertex to the graph.
- add_edge(from_vert, to_vert) Adds a new, directed edge to the graph that connects two vertices.
- add_edge(from_vert, to_vert, weight) Adds a new, weighted, directed edge to the graph that connects two vertices.
- get_vertex(vert_key) finds the vertex in the graph named vertKey.
- get_vertices() returns the list of all vertices in the graph.

### Implementation of Graph

- graph.py
