#Introduction
MapReduce is a programming model based on the idea of dividing a large computational problem into smaller sub-problems that can be processed separately in parallel. The framework consists of two main components: a map phase and a reduce phase. The input data is first split into a set of key-value pairs in the mapper, then passes these pairs to the reducer phase, aggregating them to produce a set of output values. In some complicated cases, it also allows running multiple rounds of MapReduce to get the desired results. It allows multiple machines to handle the tasks in a cluster, making it possible to analyze large datasets efficiently. This project aims to solve two data analysis problems using Hadoop MapReduce-based program. For the first part, we concentrated on the New York City (NYC) Parking Violations data to identify the most common time and location tickets issued, the most usual years and types of cars being ticketed, and the color of cars that get parking tickets the most frequently. The second part involved analyzing the NBA shots taken during the 2014-2015 seasons. We aimed to determine each player's "most unwanted defender" based on the fear score. Additionally, we aimed to classify each player's records into four comfortable zones and then considered which zone was the best for James Harden, Chris Paul, Stephen Curry, and LeBron James with the hit rate. To do this, we developed our own Python implementation of the MapReduce framework to analyze the data. Our implementation followed one or multiple rounds of the MapReduce approach. 