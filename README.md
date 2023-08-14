# tsp_problem

The traveling salesman problem (TSP) involves finding the shortest path that visits n specified locations, starting and ending at the same place and visiting the other n-1 destinations exactly once. To the layman, this problem might seem a relatively simple matter of connecting dots, but that couldn’t be further from the truth.

The TSP is actually one of the most significant problems in the history of applied mathematics. In 1952, three operations researchers (Danzig, Fulkerson, and Johnson, the first group to really crack the problem) successfully solved a TSP instance with 49 US cities to optimality. This breakthrough paved the way for future algorithmic approaches to the TSP, as well as other important developments in the field (like branch-and-bound algorithms). Consequently, it’s fair to say that the TSP has birthed a lot of significant combinatorial optimization research, as well as help us recognize the difficulty of solving discrete problems accurately and precisely.

The TSP’s wide applicability (school bus routes, home service calls) is one contributor to its significance, but the other part is its difficulty. It’s an NP-hard combinatorial problem, and therefore there is no known polynomial-time algorithm that is able to solve all instances of the problem. Some instances of the TSP can be merely understood, as it might take forever to solve the model optimally.

Consequently, researchers developed heuristic algorithms to provide solutions that are strong, but not necessarily optimal. In this blog post, I’ll show you the why and the how of two main heuristics for the TSP.
