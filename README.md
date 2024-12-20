# Cache-Simulator-Project

Memory Hierarchy Simulator

This project is a simulation of a multi-level memory hierarchy, specifically focused on modeling the behavior of data and instruction caches. It simulates memory accesses, tracks cache hits and misses, and calculates various performance metrics to evaluate the efficiency of the memory hierarchy. The simulator is highly configurable, allowing users to specify memory parameters, cache configurations, and memory access patterns.

Features:

  Cache Simulation:

    Models a multi-level cache system for both data and instruction caches.
    Supports direct-mapped cache for both data and instructions.
    Each cache level can be customized with different sizes, line sizes, and access times.
    Memory Access Tracing:
    
    The program outputs detailed trace information for every memory access, including the          address, index, tag, validity bit, and whether the access resulted in a cache hit or miss.

    
  Hit and Miss Tracking:

    For each cache level, the simulator tracks the number of hits and misses, along with their     ratios (hit ratio, miss ratio) over the entire access sequence.
    Performance Metrics:
    
    The simulator calculates and displays Average Memory Access Time (AMAT) for each cache         level.
    AMAT is calculated based on cache access times and miss ratios, giving a measure of the        cache system's efficiency.
    
    
  Configurable Cache Levels:

    Users can configure the number of cache levels, cache sizes, line sizes, and access times      for both data and instruction caches.
    The program allows for different configurations for each cache level to simulate complex       hierarchical cache structures.

    
  Input Handling:

    The simulator reads memory access addresses from external text files (one for instruction      addresses and another for data addresses).
    Users input memory parameters, cache sizes, line sizes, and access times interactively.

    
  Final Cache State:

    After processing all memory accesses, the simulator displays the final state of each cache     level, including the valid bits and tags of all cache lines.

    
How It Works:

    The simulation starts by initializing memory and cache parameters based on user input.
    For each memory access, the simulator checks each cache level for a hit or miss, updating      the cache as necessary.
    Cache performance is calculated for both data and instruction caches, and the results are      displayed, including hit and miss counts, ratios, and AMAT values for each cache level.
    The simulator provides a detailed breakdown of cache performance for both instruction and      data caches, allowing for performance tuning and analysis.
