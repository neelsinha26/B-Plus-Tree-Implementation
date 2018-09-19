# B-Plus-Tree-Implementation
This program implements B+ Tree, reading the following instructions from the input file: 1.Search 2.Range Search 3.Insert


A B+ tree is an N-ary tree with a variable but often large number of children per node. A B+ tree consists of a root, internal nodes and leaves.[1] The root may be either a leaf or a node with two or more children.[2]

A B+ tree can be viewed as a B-tree in which each node contains only keys (not key–value pairs), and to which an additional level is added at the bottom with linked leaves.

Input:

The first line of a sample input file should reperesent the degree of the B+ Tree. The subsequent lines represent the following possible instructions:

Insert(65,234) (key is 65 valuye is 234) Search(12,89) - Range Search(Done on the key) Search(12) - Standard search

There is no output for the Insert, However the Search operation returns the key and value associated with the key search for both standard search and range search. The output is written to an output file. A make file is also created.
