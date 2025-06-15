# 📘 Prime Number Law and Accurate Calculation of π(m)

This project presents a new theoretical framework on the distribution of prime numbers, introducing a structured approach to build sequences and calculate the prime-counting function π(m) with improved accuracy.

## 📌 Overview

Prime numbers appear irregular at first glance, but this research reveals a recursive structure governing their distribution. By defining specific sets and rules, we construct a deterministic method for counting primes up to any number `m`.
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
## 📂 Key Components

**P(n)**: The set of all prime numbers up to the *n*-th level.

**R(n)**: The set of multiples of *pₙ* that aren’t divisible by any of *p₀, p₁, …, pₙ₋₁*.

**X(n)**: The base prime table of level *n*; this contains the reduced residues modulo *A(n)*,  
where all primes greater than *pₙ* are congruent to some *xᵢ ∈ X(n)* modulo *A(n)*.

**A(n)**: The prime coefficient product of level *n*, defined as: &nbsp;&nbsp;&nbsp;&nbsp;*A(n) = p₀ × p₁ × p₂ × ... × pₙ*

## 📈 Methodology

The core idea is to construct `X(n)` recursively:
- `X(0) = {1, }
- `X(1) = 3.X(0)-3*X(0) = {1, , , ,5, }
- `X(2) = 5(X(1)) –5*X(1)}= {1, , , , , ,7, , , ,11, ,13, , , ,17, ,19, , , ,23, , , , ,29, }

The union of these refined sets helps estimate the number of primes up to any bound.



## Document

The full paper is provided in: https://github.com/khongnguy3n/Prime-Number-Law-and-Accurate-m-Computation/blob/main/Prime%20Number%20Law.pdf
## 📧 Contact

Author: **Khong Nguyen**  
📧 Email: khongnguy3n@gmail.com  
📞 Phone: +49 1624597204  

