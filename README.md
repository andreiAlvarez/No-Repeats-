# No-Repeats
Return the number of total permutations of the provided string that don't have repeated consecutive letters. Assume that all characters in the provided string are each unique.

For example, aab should return 2 because it has 6 total permutations (aab, aab, aba, aba, baa, baa), but only 2 of them (aba and aba) don't have the same letter (in this case a) repeating.

VVVVVVVVVVVVVVVVV

This task requires us to return the number of total permutations of the provided string that don’t have repeated consecutive letters. It is to be assumed that all characters in the provided string are each unique. For example, aab should return 2 because it has 6 total permutations (aab, aab, aba, aba, baa, baa), but only 2 of them (aba and aba) don’t have the same letter (in this case a) repeating.

To achieve that, we’ll have to look at each possible permutation of a string. There are several ways to do that. A common interview question is building a function that collects all permutations of a string. There are several tutorials available on the internet on how to do that.

Potential Methods Used As Solution

Recursive Method

This task can be daunting even after watching a tutorial. To write a recursive solution, you will want to send each new use of the function three inputs:

A new string (or character array) that is being built.
A position in your new string that’s going to be filled next.
An idea of what characters (more specifically positions) from the original string have yet to be used.
