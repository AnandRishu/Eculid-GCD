# Eculid-GCD
Euclidean algorithm to calculates the greatest common divisor (GCD) in Python for two numbers.
---
**Euclid's algorithm:** _Given two positive number m and n (m > n), find their greatest common divisor. i.e., the largest positive integer which evenly divide both m and n._
* step_1 [Find Remainder.] : _Divide m by n and let r be the remainder(0 <= r < n)._
* step_2 [Is remainder 0] : _if r = 0, the algorithm terminates; n is the answer._
* step_3 [Interchange] : _set m <- n, n <- r, and go back to step 1._
