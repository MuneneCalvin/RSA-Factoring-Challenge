# RSA Factoring Challenge :cat:
This repo is just an attempt to read in and factorize a file of numbers.

# RSA-Factoring-Challenge

### Problem Statement

Factorize as many numbers as possible into a product of two smaller numbers.

### Implementation

Implementing the Pollard Rho algorithm as seen here:
http://mathforum.org/library/drmath/view/65801.html

### Constraints

* No dependencies
* 5s max to complete calculations
* Required output: n=(p)(q)

### Real World Application?

Prime Factorization (or integer factorization) is a commonly used mathematical problem often used to secure public-key encryption systems. A common practice is to use very large semi-primes (that is, the result of the multiplication of two prime numbers) as the number securing the encryption. In order to break it, they would have to find the prime factorization of the large semi-prime number – that is, two or more **prime numbers** that multiplied together result in the original number.


## Description of what each file shows:
* factors - the program to factorize (Usage: time ./factors tests/test00)
* tests/test00 - the file with the numbers

### Environment
* Language: Bash script
* OS: Ubuntu 14.04 LTS

## Author :Calvin:

 [GitHub](https://github.com/MuneneCalvin)

