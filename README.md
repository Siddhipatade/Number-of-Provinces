# Number of Provinces
# Province Counter

This Java program calculates the total number of provinces based on a given matrix of city connections. It uses a depth-first search (DFS) algorithm to identify the connected groups of cities.

## Problem Description

Given an `n x n` matrix `isConnected`, where `isConnected[i][j] = 1` if the `ith` city and the `jth` city are directly connected, and `isConnected[i][j] = 0` otherwise, we need to determine the total number of provinces.

A province is a group of directly or indirectly connected cities, where a city is considered connected indirectly if there is a path of connected cities leading from it.

## Solution Overview

The solution uses a depth-first search (DFS) algorithm to explore the cities and identify the provinces. It maintains a boolean array to keep track of visited cities and performs a DFS from each unvisited city. By counting the number of DFS iterations, we can determine the total number of provinces.

## Usage

To use the Province Counter program:

1. Make sure you have Java installed on your system.

2. Download the `ProvinceCounter.java` file from this repository.

3. Compile the Java file using the following command:
   ```shell
   javac ProvinceCounter.java
 
