# 📘 Prime Number Law and Accurate Calculation of π(m)

This project presents a new theoretical framework on the distribution of prime numbers, introducing a structured approach to build sequences and calculate the prime-counting function π(m) with improved accuracy.

## 📌 Overview

Prime numbers appear irregular at first glance, but this research reveals a recursive structure governing their distribution. By defining specific sets and rules, we construct a deterministic method for counting primes up to any number `m`.

## 📂 Key Components

- `X(n)`: Initial sequences of candidate numbers.
- `R(n)`: Filtered sets obtained from `X(n)` by removing multiples of the first `n` primes.
- `A(n)`: Union of sets `R(1)` through `R(n)` used to approximate or calculate π(m).

## 📈 Methodology

The core idea is to construct `X(n)` recursively:
- `X(0) = {1 + 2k | k ∈ ℕ}`  (odd numbers)
- `X(1) = {x ∈ X(0) | x mod 3 ≠ 0}`
- `X(2) = {x ∈ X(1) | x mod 5 ≠ 0}`, and so on.

From these sequences, we define:
- `R(n) = X(n) \ {multiples of p(n+1)}`

The union of these refined sets helps estimate the number of primes up to any bound.

## 📊 Prime Numbers Grouped up to 210



|     | 2 | 3 | 5 | 7  | 11 | 13 | 17 | 19 | 23 | 29 |
|-----|---|---|---|----|----|----|----|----|----|----|
| 31  |   |   |   | 37 | 41 | 43 | 47 |    | 53 | 59 |
| 61  |   |   |   | 67 | 71 | 73 |    | 79 | 83 | 89 |
|     |   |   |   | 97 |101 |103 |107 |109 |113 |    |
|     |   |   |   |127 |131 |    |137 |139 |    |149 |
|151  |   |   |   |157 |    |163 |167 |    |173 |179 |
|181  |   |   |   |    |191 |193 |197 |199 |    |    |

The arrangement above facilitates the identification of potential patterns underlying the distribution of prime numbers.
## 📂 Files

- `Prime Number Law.pdf`: Full research paper with formal definitions, examples, and diagrams.
- `README.md`: Overview and illustration of the main concepts.

## 📧 Contact

Author: **Khong Nguyen**  
Email: [khongnguy3n@gmail.com](mailto:khongnguy3n@gmail.com)  
GitHub: [github.com/khongnguy3n](https://github.com/khongnguy3n)

---

⭐ If you find this project interesting or useful, please consider sharing or starring it to spread the idea.
