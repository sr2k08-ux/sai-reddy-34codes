Math With Python – 34 Beginner Programs
This repository contains thirty-four beginner-friendly Python programs designed to demonstrate mathematical concepts through code. Each script is concise, well-documented, and intended to help learners strengthen both their programming and mathematical reasoning skills. Topics include number theory, sequences, geometry, combinatorics, probability, algorithmic puzzles, and basic computational techniques.
The projects are suitable for beginners, students, and educators who want practical, accessible examples of math implemented in Python.
Features
Covers essential math topics with runnable Python scripts
Clean, readable programs with inline explanations
No external dependencies required for most scripts
Ideal for hands-on learning, classroom exercises, and self-study
Organized and modular structure for easy navigation and extension

Repository Structure

math-with-python/
│
├── README.md
├── requirements.txt
├── programs/
│   ├── 01_primes.py
│   ├── 02_sieve_of_eratosthenes.py
│   ├── 03_gcd_lcm.py
│   ├── 04_fibonacci.py
│   ├── 05_arithmetic_sequence.py
│   ├── 06_geometric_sequence.py
│   ├── 07_factorial.py
│   ├── 08_permutations_combinations.py
│   ├── 09_prime_factorization.py
│   ├── 10_modular_arithmetic.py
│   ├── 11_palindrome_checker.py
│   ├── 12_armstrong_numbers.py
│   ├── 13_collatz_sequence.py
│   ├── 14_binary_search.py
│   ├── 15_sort_visualizer.py
│   ├── 16_tower_of_hanoi.py
│   ├── 17_pythagorean_triples.py
│   ├── 18_polygon_area.py
│   ├── 19_circle_geometry.py
│   ├── 20_matrix_multiplication.py
│   ├── 21_linear_equation_solver.py
│   ├── 22_random_walk.py
│   ├── 23_monte_carlo_pi.py
│   ├── 24_coin_flip_simulation.py
│   ├── 25_binomial_distribution.py
│   ├── 26_prime_gap_analysis.py
│   ├── 27_eight_queens_solver.py
│   ├── 28_sudoku_checker.py
│   ├── 29_pascals_triangle.py
│   ├── 30_decimal_to_base_n.py
│   ├── 31_fraction_simplifier.py
│   ├── 32_continued_fractions.py
│   ├── 33_caesar_cipher.py
│   └── 34_sequence_visualizer.py
│
└── docs/
    └── explanations_and_theory.md


Installation and Setup
Requirements:Python 3.8 or later
Optional: virtual environment (recommended)

Clone the Repository
git clone https://github.com/yourusername/math-with-python.git
cd math-with-python
Create a Virtual Environment (Recommended)
python -m venv venv
Activate the environment:
macOS/Linux:
source venv/bin/activate
Windows:
venv\Scripts\activate
Install Dependencies
Most scripts use only the Python standard library.
If optional dependencies are included:
pip install -r requirements.txt

How to Run Any Program
Execute a script directly:
python programs/04_fibonacci.py
Scripts that require input will prompt the user or provide default parameters inside the code.
Each file contains:
A module description
Function definitions
A main() block wrapped in
if _name_ == "_main_":
This allows the code to be imported without auto-executing.

Program Index and Technical Details
Below is a summary of all 34 programs and what they demonstrate.
Number Theory
1. Primes – basic primality testing via trial division
2. Sieve of Eratosthenes – efficient prime generation using arrays
3. GCD and LCM – Euclidean algorithm and least common multiple
4. Prime Factorization – decomposition into prime factors
5. Modular Arithmetic – modular exponentiation and inverses
6. Prime Gap Analysis – difference between consecutive primes
Integer Sequences
7. Fibonacci Sequence – iterative, recursive, and generator versions
8. Arithmetic Sequence – term generation and series sum
9. Geometric Sequence – ratio-based sequences and formula verification
10. Collatz Sequence – hailstone numbers with iterative computation
11. Pascal's Triangle – binomial coefficient generation
12. Sequence Visualizer – ASCII or optional plotted visualization
Logic, Patterns, and Numeric Properties
13. Palindrome Checker – numeric and string-based checks
14. Armstrong Numbers – power-sum identity validation
15. Decimal to Base-N Converter – supports bases 2 to 36
16. Fraction Simplifier – reduces using GCD
17. Continued Fractions – evaluation and expansion
Algorithms and Data Structures
18. Binary Search – iterative and recursive search
19 Sorting Visualizer – bubble and selection sort, step-by-step output
20. Tower of Hanoi – recursive strategy demonstration
21. Eight Queens Solver – backtracking solution generator
22. Sudoku Checker – constraint validation for 9x9 puzzles
Geometry and Linear Algebra
23. Pythagorean Triples – primitive and scaled sets
24. Polygon Area Calculator – shoelace formula implementation
25. Circle Geometry – circumference, area, and chord calculations
26. Matrix Multiplication – naive O(n^3) implementation
27. Linear Equation Solver – 2x2 system using Cramer's Rule
Probability, Statistics, and Simulation
28. Random Walk Simulation – 1D or 2D walk modeling
29. Monte Carlo Estimation of Pi – random sampling estimation
30. Coin Flip Simulation – large-trial probability visualization
31. Binomial Distribution – probability mass function computation
32. Permutations and Combinations – factorial-based formulas

Cryptography and Encoding
33. Caesar Cipher – shift-based encoding and decoding


Example Usage

Fibonacci

python programs/04_fibonacci.py
Enter n: 10
Sequence: 0 1 1 2 3 5 8 13 21 34

Monte Carlo Pi
 python programs/23_monte_carlo_pi.py --trials 50000
Estimated pi: 3.14212

Tower of Hanoi

python programs/16_tower_of_hanoi.py
Enter number of disks: 3
Move disk 1: A -> C
Move disk 2: A -> B


Code Style Guidelines
Follows general PEP 8 conventions
Functions include docstrings describing purpose, parameters, and returns
Variable names are descriptive and mathematically meaningful
No unnecessary external libraries to maintain beginner accessibility
Scripts are self-contained and runnable individually
Contributing
Contributions are welcome. Recommended contribution workflow:
1. Fork the repository
2. Create a feature branch
3. Add or improve a program
4. Ensure the script is beginner-friendly and well-commented
5. Submit a pull request with a clear, concise description


