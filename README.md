# ddl-dag

## Problem Statement:
You are given a DAG which may be disjointed. The graph main represent for instance courses in university that must be
taken in a perticular order but many represent different streams.

Write code to read an input file describing the graph, identify all nodes with 0 in-degree and for each such node
generate all possible paths that originate from that node.

The first line of input contains total number of nodes, every subsequent line represents an edge between the nodes.
### Input:
    7
    0, 1
    0, 2
    1, 3
    1, 5
    2, 5
    6, 2
    4

Given the above graph following should be the output.
### Output:
    0->1->3
    0->1->5
    0->2->5
    4
    6->2->5


