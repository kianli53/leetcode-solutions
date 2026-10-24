# 2022. Convert 1D Array Into 2D Array

**Difficulty:** Easy
**Link:** https://leetcode.com/problems/convert-1d-array-into-2d-array/
**Topics:** Array, Matrix, Simulation

## Approach
First created an empty matrix with m rows and n columns. Checked to see if the size of m*n corresponds with the given vector size.
Continued to use to for-loops to iterate through each element in the created matrix, using the formula n*i+j to find the list position of each element needed.

## Complexity
- Time: O(m·n)
- Space: O(m·n)

## Notes / Mistakes
Used `<` instead of `!=` in the size check.
