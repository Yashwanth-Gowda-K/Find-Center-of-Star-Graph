# Find-Center-of-Star-Graph


Given an undirected star graph with n nodes labeled from 1 to n, where:

There is one center node connected to all other n-1 nodes.

All other nodes are connected only to the center.

The task is to find the center node given a list of edges edges[i] = [u, v] representing connections between nodes u and v.

Solution Approach
Optimal Solution (O(1) Time)
Key Insight:
The center node appears in every edge, while all other nodes appear in only one edge.

Method:

Compare the first two edges.

The common node between them is the center.

Alternative Solution (O(E) Time)
General Approach:

Count the degree (number of connections) of each node.

The node with degree n-1 is the center.
