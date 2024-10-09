
# Tutorial 1

- minimum number of comparisons to find maximum
- minimum number of swaps needed to sort an arrray
- 

![[Screenshot 2024-09-11 at 9.25.41 PM.png]]

- finding 2nd largest number (tree approach)

![[Screenshot 2024-09-11 at 9.25.16 PM.png]]

- lg(n!) = $\theta$ (n logn)
### optional:
- master theorem explanatino


# Tutorial 2

Recurrence:
1. T(n) = 2T(n/4) + root(n)
2. T(n)=2T(2n​)+O(logn)

Divide and conquer: median of two sorted arrays

DP:
- House Robber -- #198
- Jump Game -- #55
- Partition equal subset -- #416
- Longest Increasing Subsequence
- Coin change
- Longest common subsequence


		# Tutorial 3

Recurrence:
1. `T(n) = 2T(n/4) + root(n)`
2. `T(n)= 2T(n/2​)+O(logn)`
3. `T(n) = T( sqrt(n) ) + 1, base case x = 2`

General Algorithm:
`Q1. You are given an array of n elements, and you notice that some of the elements are duplicates; that is, they appear more than once in the array. Show how to remove all duplicates from the array in time O(n log n)`

`Q2. Given an int array, A, construct M[], where M[i] = (the product of all the numbers in A) / A[i] in O(n) time. You can not use the divide operator. 
`
`Q3. You are given an infinite array A[·] in which the first n cells contain integers in sorted order and the rest of the cells are filled with ∞. You are not given the value of n. Describe an algorithm that takes an integer x as input and finds a position in the array containing x, if such a position exists, in O(log n) time.`

![[Screenshot 2024-10-06 at 6.04.50 PM.png]]`
DP:

`Given a string S, can you put spaces in between the string such that all the split strings are legal words. You have a helper function isValidWord(w) that tells if a string "w" is a valid word, in O(1) time. Your overall runtime should be O(n^2)`

