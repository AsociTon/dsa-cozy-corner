# dsa-cozy-corner
[![Build Status](https://travis-ci.org/holmgr/dsa-cozy-corner.svg?branch=master)](https://travis-ci.org/holmgr/dsa-cozy-corner)

A collection of implementations of prominent algorithms and data strucutres by U-students @ LiU

Read the [Contribution Guidelines](CONTRIBUTE.md) before coding to ensure that your implementation will be accepted.

## Getting started

The project uses `CMake` and `make` as its build tools and the [Google Test](https://github.com/google/googletest) framework for unit testing.

Use the following steps (make sure that you are standing in the build directory:

1. Generate make files for the project

    ```
    mkdir build
    cd build
    cmake ..
    ```
1. Compile and link source code:

    ```
    make
    ```
2. Run all unit tests:

    ```
    ./dsa_test
    ```

There also exists some python scripts in the root directory (`install.py` and `run_tests.py`) which will do these two steps automatically for you.

Furthermore there exists some sample code for you to get started, specifically `src/sample.cpp`, `src/sample.h` and `test/sample_unittest.cpp`.

Get hacking!

## Implementation suggestions
The following lists are some suggestions for algorithms and data structures which
has not yet been implemented or only implemented in a very limited fashion.
You can of cource pick any algorithm/data structure you want!

Algorithms:

- [] AC-3
- [] Hill Climbing (normal and enforced)
- [] A*
- [] DFS
- [] BFS
- [] Quicksort
- [] Mergesort
- [] Heapsort
- [] Insertion sort
- [] 2opt
- [] Alpha-Beta pruning
- [] Minimax

Data structures
- [] Search trees
- [] Balanced trees (AVL, Splay and Red-Black)
- [] Persistant rope
- [] Priority Queue (min or max heap)
- [] Prefix tree
