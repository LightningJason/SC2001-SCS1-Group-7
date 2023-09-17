# Project 1: Integration of Mergesort & Insertion Sort

## Contributors
1. Dion Lim ([@dion2910](https://github.com/dion2910))
2. Jason Lim Jia Sheng ([@LightningJason](https://github.com/LightningJason))
3. Tan Mu Hao ([@

## Introduction
For small arrays, the recursive overhead of merge sort can become a significant portion of the overall execution time, making it less efficient compared to non-recursive algorithms like insertion sort. Hence, this project implements a hybrid sort that integrates Merge Sort with Insertion sort. 


## Table of Contents
1. Algorithm Implementation
2. Time Complexity Analysis
3. Comparing with Merge Sort

## Algorithm Implementation

## Input Data
The algorithm was tested using inputs of arrays of sizes from (1000 to 510000).
For each of the sizes, a random dataset of integers were generated in the range of 1 to 100.

## Time Complexity

I) By recording the number of key comparisons performed in for each array size, we are able to analyse the time complexity of our hybrid sort algorithm.

Fixing the S value at 50, the number of key comparisons was plotted against different array sizes. In the figure below, we compared our empirical results with the theoretical analysis of time complexity. 



II) With the input size n fixed at 1 million integers, we plotted the number of key comparisons against different values of S. In the figure below, we compared our empirical results with our theoretical analysis of the time complexity.



III) Using different sizes of input datasets (100 to 1million), we study how to determine an optimal value of S for the best performance of this hybrid algorithm.




## Comparing with Original Merge Sort
After obtaining the optimal value of S, we compare the performance of the hybrid sort against merge sort in terms of key comparisons and CPU times on the dataset with 10 million integers.

