# Longest-Substring-Without-Repeating-Characters
Given a string s, find the length of the longest substring without repeating characters.
Explanation:
Sliding Window Approach:
We use two pointers (left and right) to create a window of unique characters.

HashSet:
Maintains the characters currently in the window. If a duplicate is found, we slide the left pointer to remove characters until the duplicate is gone.

maxLength:
Keeps track of the longest valid substring found during the process.
