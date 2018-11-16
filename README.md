# Eculid-GCD
Euclidean algorithm to calculates the greatest common divisor (GCD) in Python for two numbers.
---
**Euclid's algorithm:** _Given two positive number m and n (m > n), find their greatest common divisor. i.e., the largest positive integer which evenly divide both m and n.
step 1 [Find Remainder.] : Divide m by n and let r be the remainder(0 <= r < n).
step 2 [Is remainder 0] : if r = 0, the algorithm terminates; n is the answer.
step 3 [Interchange] : set m <- n, n <- r, and go back to step 1._
