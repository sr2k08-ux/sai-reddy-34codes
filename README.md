Number Theory & Mathematical Functions Library
A Comprehensive Collection of 34 Mathematical & Number-Theoretic Utilities in Python Overview: This project is a complete collection of 34 essential mathematical and number-theory functions, implemented in Python. It covers a wide range of topics including: Basic number properties Digit-based operations Prime number utilities Modular arithmetic Special sequences Advanced number-theoretic algorithms Factorization techniques Probabilistic primality tests Partition functions and zeta approximations The goal of this project is to provide accurate, efficient, and easy-to-understand implementations for educational, research, and computational uses. Functions Included (Summary)

Basic Number Properties factorial(n) is_palindrome(n) mean_of_digits(n) digital_root(n) is_harshad(n) multiplicative_persistence(n)
Divisor & Abundance Checks is_abundant(n) is_deficient(n) aliquot_sum(n) are_amicable(a, b) count_divisors(n) is_highly_composite(n)
Prime-Related Functions prime_factors(n) count_distinct_prime_factors(n) is_prime_power(n) is_mersenne_prime(p) twin_primes(limit) is_prime_miller_rabin(n, k) pollard_rho(n)
Modular Arithmetic mod_exp(base, exponent, modulus) mod_inverse(a, m) crt(remainders, moduli) order_mod(a, n)
Special Number Properties is_automorphic(n) is_pronic(n) is_fibonacci_prime(n) lucas_sequence(n) is_perfect_power(n) is_carmichael(n) is_quadratic_residue(a, p)
Advanced Mathematical Utilities collatz_length(n) polygonal_number(s, n) zeta_approx(s, terms) partition_function(n) Project Purpose This project is designed for: Students learning number theory Developers needing mathematical utilities Competitive programmers Researchers experimenting with primality testing or factorization Anyone wanting a clean Python library of useful numerical functions
Project Structure Example layout: number-theory-library

├── README.md

├── number_functions.py

├── prime_utils.py

├── modular_arithmetic.py

├── advanced_math.py

└── examples.ipynb

Each file groups related operations for clarity and modularity.

How to Use:

from number_functions import factorial, digital_root

from prime_utils import prime_factors, twin_primes

print(factorial(5)) # 120

print(digital_root(9872)) # 8

print(prime_factors(84)) # [2, 2, 3, 7]

print(twin_primes(50)) # [(3, 5), (5, 7), (11, 13), ...]

Key Features Beginner-friendly implementations Covers both basic and advanced number theory Efficient algorithms such as Pollard Rho, Miller–Rabin, CRT, and modular exponentiation Clean, well-structured Python code Easily extendable

Contribution: Contributions are welcome.You may:Add new number-theory functions Improve algorithmic efficiency Provide optimizations Add usage examples
