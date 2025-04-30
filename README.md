# GraphTraversal
# Graph Traversal Assignment

## Overview
This Java project implements a directed graph traversal with dependency-aware execution. Nodes execute only after all parent nodes have completed, and multiple children are handled using parallel threads.

## Tools Used
- Java 17
- Standard Java libraries (no external dependencies)

## Files
- `DirectedGraph.java`: Contains the main logic
- `input.txt`: Sample input data
- `results.txt`: Output captured from sample run (optional)

## Assumptions
- Input is read from `input.txt` in the project root
- Node 1 is always the root
- Each node is printed only once, after all its parent dependencies are resolved

## Execution
1. Compile: `javac DirectedGraph.java`
2. Run: `java DirectedGraph < input.txt`

## Output Format
Node names in order of execution (respecting dependency rules), followed by the total number of nodes.
