# Mathematical Algorithms

This directory contains implementations of various mathematical algorithms in Go.

## Algorithms to be Implemented

### Number Theory

1. **Greatest Common Divisor (GCD)** - `gcd.go`
   - Time Complexity: O(log min(a, b))
   - Space Complexity: O(1)
   - Euclidean algorithm

2. **Least Common Multiple (LCM)** - `lcm.go`
   - Time Complexity: O(log min(a, b))
   - Space Complexity: O(1)
   - Uses GCD

3. **Extended Euclidean Algorithm** - `extended_euclidean.go`
   - Time Complexity: O(log min(a, b))
   - Space Complexity: O(1)
   - Find Bézout coefficients

4. **Modular Exponentiation** - `modular_exponentiation.go`
   - Time Complexity: O(log n)
   - Space Complexity: O(1)
   - Compute (base^exp) % mod efficiently

5. **Modular Inverse** - `modular_inverse.go`
   - Time Complexity: O(log n)
   - Space Complexity: O(1)
   - Find multiplicative inverse under modulo

### Prime Numbers

6. **Prime Check (Trial Division)** - `is_prime.go`
   - Time Complexity: O(√n)
   - Space Complexity: O(1)
   - Check if number is prime

7. **Sieve of Eratosthenes** - `sieve_of_eratosthenes.go`
   - Time Complexity: O(n log log n)
   - Space Complexity: O(n)
   - Find all primes up to n

8. **Segmented Sieve** - `segmented_sieve.go`
   - Time Complexity: O(n log log n)
   - Space Complexity: O(√n)
   - Memory-efficient prime finding

9. **Prime Factorization** - `prime_factorization.go`
   - Time Complexity: O(√n)
   - Space Complexity: O(log n)
   - Find all prime factors

10. **Miller-Rabin Primality Test** - `miller_rabin.go`
    - Time Complexity: O(k log³ n)
    - Space Complexity: O(1)
    - Probabilistic prime test

### Fibonacci and Sequences

11. **Fibonacci Numbers (Iterative)** - `fibonacci_iterative.go`
    - Time Complexity: O(n)
    - Space Complexity: O(1)
    - Calculate nth Fibonacci number

12. **Fibonacci (Matrix Exponentiation)** - `fibonacci_matrix.go`
    - Time Complexity: O(log n)
    - Space Complexity: O(1)
    - Fast Fibonacci calculation

13. **Catalan Numbers** - `catalan_numbers.go`
    - Time Complexity: O(n)
    - Space Complexity: O(n)
    - Calculate nth Catalan number

### Combinatorics

14. **Factorial** - `factorial.go`
    - Time Complexity: O(n)
    - Space Complexity: O(1) iterative, O(n) recursive
    - Calculate n!

15. **Binomial Coefficient (nCr)** - `binomial_coefficient.go`
    - Time Complexity: O(n × r)
    - Space Complexity: O(r)
    - Calculate n choose r

16. **Permutations (nPr)** - `permutations.go`
    - Time Complexity: O(n)
    - Space Complexity: O(1)
    - Calculate n permute r

17. **Pascal's Triangle** - `pascals_triangle.go`
    - Time Complexity: O(n²)
    - Space Complexity: O(n²)
    - Generate Pascal's triangle

### Power and Roots

18. **Fast Power (Exponentiation by Squaring)** - `fast_power.go`
    - Time Complexity: O(log n)
    - Space Complexity: O(1)
    - Calculate a^n efficiently

19. **Square Root (Binary Search)** - `sqrt_binary_search.go`
    - Time Complexity: O(log n)
    - Space Complexity: O(1)
    - Integer square root

20. **Newton-Raphson Method** - `newton_raphson.go`
    - Time Complexity: O(log n)
    - Space Complexity: O(1)
    - Find roots of equations

### Number Manipulation

21. **Reverse Integer** - `reverse_integer.go`
    - Time Complexity: O(log n)
    - Space Complexity: O(1)
    - Reverse digits of a number

22. **Palindrome Number** - `palindrome_number.go`
    - Time Complexity: O(log n)
    - Space Complexity: O(1)
    - Check if number is palindrome

23. **Power of Two** - `power_of_two.go`
    - Time Complexity: O(1)
    - Space Complexity: O(1)
    - Check if number is power of 2

24. **Count Set Bits** - `count_set_bits.go`
    - Time Complexity: O(log n)
    - Space Complexity: O(1)
    - Count 1s in binary representation

25. **Sum of Digits** - `sum_of_digits.go`
    - Time Complexity: O(log n)
    - Space Complexity: O(1)
    - Sum all digits of a number

### Random Number Generation

26. **Linear Congruential Generator** - `lcg.go`
    - Time Complexity: O(1)
    - Space Complexity: O(1)
    - Pseudorandom number generation

### Matrix Operations

27. **Matrix Multiplication** - `matrix_multiplication.go`
    - Time Complexity: O(n³) standard, O(n^2.807) Strassen's
    - Space Complexity: O(n²)
    - Multiply two matrices

28. **Matrix Determinant** - `matrix_determinant.go`
    - Time Complexity: O(n³)
    - Space Complexity: O(n²)
    - Calculate determinant

29. **Matrix Transpose** - `matrix_transpose.go`
    - Time Complexity: O(n²)
    - Space Complexity: O(1) in-place
    - Transpose a matrix

### Other Mathematical Algorithms

30. **Chinese Remainder Theorem** - `chinese_remainder_theorem.go`
    - Time Complexity: O(n log n)
    - Space Complexity: O(1)
    - Solve system of congruences

31. **Totient Function (Euler's Phi)** - `euler_totient.go`
    - Time Complexity: O(√n)
    - Space Complexity: O(1)
    - Count coprimes less than n

32. **Josephus Problem** - `josephus_problem.go`
    - Time Complexity: O(n)
    - Space Complexity: O(1)
    - Find survivor position

## Usage

Each algorithm will have:
- Implementation file (.go)
- Test file (_test.go)
- Example usage in tests
