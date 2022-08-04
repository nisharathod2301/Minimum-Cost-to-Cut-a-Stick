# Minimum-Cost-to-Cut-a-Stick
Given a wooden stick of length n units. The stick is labelled from 0 to n. For example, a stick of length 6, Given an integer array cuts where cuts[i] denotes a position you should perform a cut at.  You should perform the cuts in order, you can change the order of the cuts as you wish.  The cost of one cut is the length of the stick to be cut, the total cost is the sum of costs of all cuts. When you cut a stick, it will be split into two smaller sticks (i.e. the sum of their lengths is the length of the stick before the cut).  Return the minimum total cost of the cuts.

https://leetcode.com/problems/minimum-cost-to-cut-a-stick/

Input: n = 7, cuts = [1,3,4,5]
Output: 16

Constraints:


2 <= n <= 106
1 <= cuts.length <= min(n - 1, 100)
1 <= cuts[i] <= n - 1
All the integers in cuts array are distinct.
