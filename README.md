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

## Analysis of Result
[CPT212]([https://drive.google.com/file/d/1skiNcixn87_Hm97hzH65q1uY2YRLNz4Y/view](https://onedrive.live.com/personal/ff5f3ecf20665d92/_layouts/15/Doc.aspx?sourcedoc=%7B20665d92-3ecf-205f-80ff-7e0c00000000%7D&action=default&redeem=aHR0cHM6Ly8xZHJ2Lm1zL3cvcyFBcEpkWmlEUFBsX19tSDdyR2d3Yk10X3pSRFg5P2U9a2VJaDFa&slrid=53c36ca1-f057-4000-3593-813da21d2165&originalPath=aHR0cHM6Ly8xZHJ2Lm1zL3cvYy9mZjVmM2VjZjIwNjY1ZDkyL1FaSmRaaURQUGw4Z2dQOS1EQUFBQUFBQTZ4b01HekxmODBRMV9RP3J0aW1lPVBCR24zb2dhM1Vn&CID=6dd7d1cf-efa2-4cbd-a75d-455cdd476bbb&_SRM=0:G:47))
