# Matrix_Search
Given an n x m matrix, where every row and column is sorted in increasing order, and a number x .
Find if element x is present in the matrix or not.   
Input Format: First line consists of two space separated integers N and M, denoting the number of element in a row and column respectively. 
Second line of each test case consists of N*M space separated integers denoting the elements in the matrix in row major order. 
Third line of each test case contains a single integer x, the element to be searched.  

Constraints: 1 &lt;= N,M &lt;= 30 0 &lt;= A[i] &lt;= 100 
Output Format: Print 1 if the element is present in the matrix, else 0.  
Sample Input: 
3 
3 3 30 
38 44 52 
54 57 60 
69 
62  

1 6 
18 21 27 38 55 67 
55 

Sample Output: 0 1 
Explanation: Search the element in the sorted matrix. If the element is present print 1 otherwise print 0. In the sample input,in first case 62 is not present in the matrix so 0 is printed. Similarly, for second case 55 is present in the matrix so 1 is printed.  
Time Limit: 1 sec
Language used : cpp
