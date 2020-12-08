# Dynamic-Array

https://www.hackerrank.com/challenges/dynamic-array/problem

Create a list, , of  empty sequences, where each sequence is indexed from  to . The elements within each of the  sequences also use -indexing.
Create an integer, , and initialize it to .
There are  types of queries that can be performed on the list of sequences:
Query: 1 x y
Find the sequence, , at index  in .
Append integer  to sequence .
Query: 2 x y
Find the sequence, , at index  in .
Find the value of element  in  (where  is the size of ) and assign it to .
Print the new value of  on a new line
Note:  is the bitwise XOR operation, which corresponds to the ^ operator in most languages. Learn more about it on Wikipedia.  is the modulo operator.

Function Description

Complete the dynamicArray function below.

dynamicArray has the following parameters:
- int n: the number of empty sequences to initialize in 
- string queries[q]: an array of query strings

Returns

int[]: the results of each type 2 query in the order they are presented
