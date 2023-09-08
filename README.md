# Project 1: Integration of Mergesort & Insertion Sort

# Steps on what to do
- Draft basic hybrid code!
- Figure out what data to collect 
- Draft code to get that data
- Plot graph
- Figure out time complexities
- Presentation Slides

## Introduction
For small arrays, the recursive overhead of merge sort can become a significant portion of the overall execution time, making it less efficient compared to non-recursive algorithms like insertion sort. Hence, this project implements a hybrid sort that integrates Merge Sort with Insertion sort. 

## Algorithm Implementation

## Input Data
The algorithm was tested using inputs of arrays of sizes from (1000 to 510000).
For each of the sizes, a random dataset of integers were generated in the range of 1 to 100.

## Time Complexity
By recording the number of key comparisons performed in for each array size, we are able to analyse the time complexity of our hybrid sort algorithm.

1) With the value of S fixed, plot the number of key comparisons over
different sizes of the input list n. Compare your empirical results with 
your theoretical analysis of the time complexity.

I fixed the S value at 15, then I ran my version of the algorithm 
![image](https://github.com/LightningJason/SC2001-SCS1-Group-7/assets/103420694/42b2a34a-69f7-44d2-83bc-4ff5d5859156)


3) With the input size n fixed, plot the number of key comparisons over 
different values of S. Compare your empirical results with your 
theoretical analysis of the time complexity.

4) Using different sizes of input datasets, study how to determine an 
optimal value of S for the best performance of this hybrid algorithm

## Comparing with original Merge Sort
After obtaining the optimal value of S, we compare the performance of the hybrid sort against merge sort in terms of key comparisons and CPU times on the dataset with 10 million integers.

