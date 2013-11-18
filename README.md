Kloud Kd Tree (KdKdT)
=====================

Introduction
------------
Kloud Kd Tree implements Kd Tree in a map reduce framework. Details are in [this](http://www.vision.caltech.edu/malaa/publications/aly11distributed.pdf) paper.

Two implementations
-------------------

* under `./MapReduceKDT/`

* Independent Kd Trees

* Distributed Kd Trees

Index operations
----------------

* Run `./ikdt_index.sh` or `./dkdt_index.sh` under `./MapReduceKDT/`

* Index trees are stored in `ikdt_index_output.py` as a python variable.

Query operations
----------------

* Run `./ikdt_query.sh` or `./dkdt_query.sh` under `./MapReduceKDT/`

* Output stored in `ikdt_query_output.py` as a python variable.

Benchmarking
------------

* `./generate.py` provides basic functionality to generate test data with various rows/dimensions/distributions.

* `./index.py` can perform single machine Kd tree tests.

* `./index_lsh.py` can perform single machine indexing using E2LSH [scheme](http://www.mit.edu/~andoni/LSH/).