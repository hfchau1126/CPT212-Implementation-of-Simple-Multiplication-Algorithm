# Simple-Multiplication-Algorithm VS Kartsuba Algorithm
## Overview
The multiplications of 2 numbers in base 10 can be done using simple multiplication algorithm. The algorithm is explained below:
- Step 1: Multiply each digit in the multiplicand by each digit of the multiplier, keep the partial product and carriers if there is any (e.g. 3x8=24, “4” is the partial product and “2” is the
carrier). Print out the partial and carrier at every step.
- Step 2: Add up all the properly shifted partial product and carriers.
In addition to the standard multiplication algorithm, another algorithm that can be used to calculate a multiplication is the Karatsuba algorithm. It offers a more efficient approach to multiplication, particularly for large numbers. It employs a divide-and-conquer strategy to reduce the number of single-digit multiplications required.
This project compares the two algorithms, focusing on:
- Performance results obtained through experiments.
- Theoretical time complexity analysis of both algorithms.
- Practical implications of the experimental results, highlighting the trade-offs between simplicity and computational efficiency.

