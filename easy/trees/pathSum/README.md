## Description:

Given the root of a binary tree and an integer targetSum, return true if the tree has a root-to-leaf path such that adding up all the values along the path equals targetSum.

A leaf is a node with no children.

## Example 1:

![alt text](https://assets.leetcode.com/uploads/2021/01/18/pathsum1.jpg)

Input: root = [5,4,8,11,null,13,4,7,2,null,null,null,1], targetSum = 22  
Output: true  
Explanation: The root-to-leaf path with the target sum is shown.

## Example 2:

![alt text](https://assets.leetcode.com/uploads/2021/01/18/pathsum2.jpg)

Input: root = [1,2,3], targetSum = 5  
Output: false  
Explanation: There two root-to-leaf paths in the tree:  
(1 --> 2): The sum is 3.  
(1 --> 3): The sum is 4.  
There is no root-to-leaf path with sum = 5.

## Source:

https://leetcode.com/problems/path-sum/