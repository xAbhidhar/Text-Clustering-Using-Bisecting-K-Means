# Text clustering using Bisecting K-Means

## Introduction

This application shows the implementation of one of most importatnt clustering algorithm, Bisecting K-Means Clustering. Bisecting K-Means algorithm is implemeted in this python notebook. The appilicaftion deals with the data which is in the form of document term sparse matrix format. Implementation is done without using any imported function for the bisecting k-Means defined in library. Code is written from scrtach for implemetaion of this clustering algorithm.

## Clustering
Clustering is an unsupervised method for machine learning. The objective of clustering is to find groups of data points which are similar (or realted to) to one another and different from (or unrelated to) the objects in other groups. Clustering is performed such athat the in such a way that `Intra-Cluster distances are minimized` and `Inter-Cluster distances are maximized`. Clustering could be of two types
  - Hierarchical CLustering
  - Partitional Clustering

## Implementation

The implementation is `done without importing any library for the k-Means algorithm`. The objective is to implement the algorithm from scratch and learn to play with different cluster evaluation metrices. In the final run the k is set to 7 which yielded best results.

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

## Results

