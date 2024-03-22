# ft_is_prime

This repository contains the implementation of the `ft_is_prime` function, a custom method for determining if a given integer is a prime number. Prime numbers are integers greater than 1 that have no divisors other than 1 and themselves. This function provides an efficient way to identify prime numbers, which is a fundamental concept in number theory and has applications in various areas of computer science, including cryptography.

## Function Overview

The `ft_is_prime` function checks whether a given integer `nb` is a prime number. It does so by attempting to divide `nb` by all integers from 2 up to half of `nb`, as no divisor larger than half of `nb` could possibly yield a whole number.

### Function Prototype

```c
int ft_is_prime(int nb);
