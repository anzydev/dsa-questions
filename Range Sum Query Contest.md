# Range Sum Query Contest

Fork this repository and solve the following problem.
---

You are given an array arr of size N containing positive integers. You are also given Q queries.

Each query consists of two integers L and R, representing the starting and ending indices of a range (both inclusive and 0-based).

Your task is to process each query and print the sum of elements from index L to R (inclusive).

## Input
The first line of input contains a single integer N, representing the size of the array arr.  
The second line contains N space-separated integers, representing the elements of the array arr.  
The third line contains a single integer Q, representing the number of queries.  
The next Q lines each contain two space-separated integers L and R, representing the starting and ending indices of the range, respectively.

Example Input:
5  
10 20 30 40 50  
3  
1 3  
0 4  
2 4  

## Output
For each query, output the sum of the elements from index L to R, with each result printed on a new line.

Example Output:
90  
150  
120
