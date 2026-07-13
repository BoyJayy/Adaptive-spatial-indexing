# Adaptive Spatial Indexing

A C++20 research project for efficient fixed-radius neighbor search in
dynamic particle systems.

The project compares brute-force search, uniform grids, hashed grids, spatial
sorting, BVH-based methods, index-reuse strategies, and parallel CPU and GPU
implementations.

The main goal is to build an adaptive system that analyzes the current
particle distribution and movement and automatically selects an efficient
spatial index, its parameters, and its update or rebuild strategy.

The methods will be evaluated on uniform, sparse, clustered, and dynamically
changing workloads using correctness, construction time, query latency,
throughput, memory usage, scalability, and performance relative to the best
specialized method.

The resulting repository will contain a reusable C++ library, deterministic
workload generators, correctness tests, benchmark tools, an adaptive method
selector, CPU and GPU implementations, experiment results, performance maps,
and a reproducible technical report.
