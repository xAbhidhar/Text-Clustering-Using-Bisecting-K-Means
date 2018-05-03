# Text clustering

## Introduction

This python notebook shows the implementation of one of most importatnt clustering algorithm, k-Means Clustering.

## Implementation

The implementation is done without importing any library for the k-Means algorithm. The objective is to implement the algorithm from scratch and learn to play with different cluster evaluation metrices.

## Dataset

The input data is in the form of text records. These have been converted into sparse format. The training data has 8550 records. The input data does not contain any labels which makes this exercise even more interesting. 

## Input data format
The training data is in the form of Compressed Sparse Row matrix. 
Sparse matrices can be used in arithmetic operations. The operations supported by them are as follows:
  - addition
  - subtraction
  - multiplication
  - division
  - matrix power

Some of the advantages of the CSR format are :
  - efficient arithmetic operations CSR + CSR, CSR * CSR, etc.
  - efficient row slicing
  - fast matrix vector products
  - Disadvantages of the CSR format
  - slow column slicing operations (consider CSC)
  - changes to the sparsity structure are expensive (consider LIL or DOK)

## Evaluation


