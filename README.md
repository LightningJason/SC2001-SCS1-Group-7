# Project 1: Integration of Mergesort & Insertion Sort

## Contributors
1. Dion Lim ([@dion2910](https://github.com/dion2910))
2. Jason Lim Jia Sheng ([@LightningJason](https://github.com/LightningJason))
3. Tan Mu Hao ([@

# Steps on what to do
- Draft basic hybrid code! (DONE)
- Figure out what data to collect: Just need get at least up to 15million, because the qn require us to compare against merge sort for 15 million integers
- Draft code to get that data
- Plot graph
- Figure out time complexities
- Presentation Slides

## Introduction
For small arrays, the recursive overhead of merge sort can become a significant portion of the overall execution time, making it less efficient compared to non-recursive algorithms like insertion sort. Hence, this project implements a hybrid sort that integrates Merge Sort with Insertion sort. 

##A. Algorithm Implementation

##B. Input Data
The algorithm was tested using inputs of arrays of sizes from (1000 to 510000).
For each of the sizes, a random dataset of integers were generated in the range of 1 to 100.

##C. Time Complexity

I) By recording the number of key comparisons performed in for each array size, we are able to analyse the time complexity of our hybrid sort algorithm.

Fixing the S value at 50, the number of key comparisons was plotted against different array sizes. In the figure below, we compared our empirical results with the theoretical analysis of time complexity. 

![image](https://github.com/LightningJason/SC2001-SCS1-Group-7/assets/103420694/bec48f78-c8a1-400a-a16c-3a599608800e =250x250)


II) With the input size n fixed at 1 million integers, we plotted the number of key comparisons against different values of S. In the figure below, we compared our empirical results with our theoretical analysis of the time complexity.

![image](https://github.com/LightningJason/SC2001-SCS1-Group-7/assets/103420694/7521087a-acad-429e-8b00-53328449c03a)


III) Using different sizes of input datasets (100 to 1million), we study how to determine an optimal value of S for the best performance of this hybrid algorithm.

![image](https://github.com/LightningJason/SC2001-SCS1-Group-7/assets/103420694/bbe2bd78-1953-4cb1-a0dd-af4e08c8c9e8) ![image](https://github.com/LightningJason/SC2001-SCS1-Group-7/assets/103420694/de5f1994-f094-4be4-84d3-c273110433bc) ![image](https://github.com/LightningJason/SC2001-SCS1-Group-7/assets/103420694/b931c7bb-1ca4-438d-9364-5c52252c298f)








## Comparing with original Merge Sort
After obtaining the optimal value of S, we compare the performance of the hybrid sort against merge sort in terms of key comparisons and CPU times on the dataset with 10 million integers.

