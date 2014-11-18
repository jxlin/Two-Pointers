Two-Pointers
============
Valid Palindrome

O(n) runtime, O(1) space:

The idea is simple, have two pointers – one at the head while the other one at the tail. Move them towards each other until they meet while skipping non-alphanumeric characters.

Implement strStr()

O(nm) runtime, O(1) space – Brute force:

You could demonstrate to your interviewer that this problem can be solved using known efficient algorithms such as Rabin-Karp algorithm, KMP algorithm, and the Boyer- Moore algorithm. Since these algorithms are usually studied in an advanced algorithms class, it is sufficient to solve it using the most direct method in an interview – The brute force method.
