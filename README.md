# Longest Valid Parentheses

## Problem

Given a string containing only '(' and ')', return the length of the longest valid (well-formed) parentheses substring.

## Approach

This solution uses a stack to keep track of indices of unmatched parentheses.

- Initialize the stack with -1.
- Push indices of '('.
- Pop when ')' is found.
- If the stack becomes empty, push the current index.
- Otherwise, calculate the current valid substring length.

## Time Complexity

O(n)

## Space Complexity

O(n)

## Language

Python
