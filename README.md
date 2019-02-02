# node-connectivity-fast

This repo contains the source code, data and results that accompany a manuscript under review in the ACM Journal of Experimental Algorithms. After (hopefully) acceptance, we'll update with reference to journal article.

**Abstract**

For a graph G, the node connectivity *K* is defined as the minimum number of nodes that must be removed to make the graph disconnected. The determination of *K* is a computationally demanding task for large graphs since even the most efficient algorithms require many evaluations of an expensive *max flow* function. Approximation methods for determining *K* replace the max flow function with a much faster algorithm that gives a lower bound on the number of node independent paths, but this frequently leads to an underestimate of *K*. We show here that with minor changes, the approximate method can be adapted to retain most of the performance benefits while still guaranteeing an accurate result.

## Files and directories

+ node connectivity fast.ipynb is the main notebook containing code and benchmark problems

+ startnode fig generator.ipynb contains code used to create manuscript figure

The results directory contains the following file:

+ barabasi-albert_benchmarks.txt
+ erdos-renyi_benchmarks.txt
+ watts-strogatz_benchmarks.txt
+ social_benchmarks.txt
+ start-node-effect_benchmarks.txt
+ worst-case_benchmarks.txt
+ startnode.csv (start node experiments in csv format)
+ benchmark_results.xlsx (benchmark results summarized in Excel spreadsheet)

The social_network directory contains k-components and related subgraphs generated from a large anonymized social network

