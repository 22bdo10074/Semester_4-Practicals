# Experiment- 7

### Aim:Perform Matrix Chain Multiplication Problem (MCM) using Dynamic Programming.

### 7.1 Objective:
Chain matrix multiplication is an optimization problem that can be solvedusing dynamic
programming. Given a sequence of matrices, the objective is tofind out the most efficient
way to multiply the matrices. The efficiencyparameter is number of multiplications steps.

### 7.2 Program Logic:
Matrix chain multiplication (or the matrix chain ordering problem) is an optimization
problem concerning the most efficient way to multiply a given sequence of matrices. The
problem is not actually to perform the multiplications, but merely to decide the sequence of
the matrix multiplications involved. The problem may be solved using dynamic
programming.
There are many options because matrix multiplication is associative. In other words, no
matter how the product is parenthesized, the result obtained will remain the same.

### 7.3 Program Code:

#include<stdio.h>

#include<limits.h>

// Matrix Ai has dimension p[i-1] x p[i] for i = 1..n

int MatrixChainMultiplication(int p[], int n)

{
 int m[n][n];
 
 int i, j, k, L, q;
 
 for (i=1; i<n; i++)
 
 m[i][i] = 0; //number of multiplications are 0(zero) when there is only one matrix
 
 //Here L is chain length. It varies from length 2 to length n.
 
 for (L=2; L<n; L++)
 
 {
 for (i=1; i<n-L+1; i++)
 
 {
 j = i+L-1;
 
 m[i][j] = INT_MAX; //assigning to maximum value
 
 for (k=i; k<=j-1; k++)
 
 {
 q = m[i][k] + m[k+1][j] + p[i-1]*p[k]*p[j];
 
 if (q < m[i][j])
 
 {
 m[i][j] = q; //if number of multiplications found less that number will
be updated.

 }
 }
 }
 }
 return m[1][n-1]; //returning the final answer which is M[1][n]
 
}
int main()

{
 int n,i;
 
 printf("Enter number of matrices\n");
 
 scanf("%d",&n);
 
 n++;
 
 int arr[n];
 
 printf("Enter dimensions \n");
 
 for(i=0;i<n;i++)
 
 {
 printf("Enter d%d :: ",i);
 
 scanf("%d",&arr[i]);
 
 }
 int size = sizeof(arr)/sizeof(arr[0]);
 
 printf("Minimum number of multiplications is %d ", MatrixChainMultiplication(arr,size));
 
 return 0;
 
}

### 7.4 Conclusion:
### 7.5 Analysis:

A simple inspection of the nested loop structure of MATRIX-CHAIN-ORDER yields a running
time of O(n3) for the algorithm.
