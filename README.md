This is an assignment from 02-713 Algorithms and DataStructures.

Programming Assignment : Traveling Salesman and A*
Write a Python program that nds the optimal traveling salesman tour. You can
use any Python library that is part of the standard Python distribution1. You can also use the networkx2, numpy3, and matplotlib4 libraries. You can use any code that is on the 02-713 website. You can use any algorithm you want to nd the optimal TSP tour; one suggestion is given below. Input will be provided as a graph in GEXF format, which can be read using the networkx.read_gexf() function. The graph is undirected and guaranteed to be complete (there's an edge between every pair of nodes). Every edge will have an attribute `weight' that gives the length of the edge.

Output should consist of two lines of the following format:

Tour: a b c d e f g h i j

Cost: 10.2345

These lines should start in column 0 and be printed to standard output (using, e.g., the Python
print statement). The first line gives the optimal tour that you compute. The tour should start
with the node that has the lexicographically first name. The node names then should be listed in
the order of the optimal tour, each separated by a single space. The first city should not be listed
twice. The second line gives the cost of the tour reported on the previous line. Your program can
print other lines of output, but only the two above should start with Tour: and Cost: . Zero points will be give for assignments that fail to format the output correctly.

