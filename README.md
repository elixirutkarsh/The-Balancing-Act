# The-Balancing-Act
Problem Statement: You are given a set of positive integers. Your task is to divide these integers into two groups, such that the difference between the sum of integers in each group is minimized. You need to write an algorithm to determine the minimum difference possible.

Solution:
To solve this problem, you can use a dynamic programming approach. Start by calculating the total sum of all the integers in the set. Then create a 2D array with dimensions [n+1][sum+1], where n is the number of integers and sum is the total sum. Use dynamic programming to fill in the array, considering each integer and each possible sum value. Finally, find the minimum difference between the two groups by iterating through the last row of the array. The value at array[n][sum/2] will give you the minimum difference.
