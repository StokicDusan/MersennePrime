[![Contributors][contributors-shield]][contributors-url]
[![Commit-activity][commit-activity-shield]][commit-activity-url]
[![Issues][issues-shield]][issues-url]
[![Repo-size][repo-size-shield]][repo-size-url]
[![License][license-shield]][license-url]  
[![Forks][forks-shield]][forks-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

# Welcome to MersennePrime

A Mersenne prime is a prime number that is one less than a power of two. It is a prime number of the form $M_{n} = 2^{n}-1$ for some integer $n$.

## What does the script do?
The script prints Mersenne prime numbers on the command line.

## `mersennePrimes.py` :
This script is ready to use script which uses one arguments to run. The argument is the integer passed for the number of primes to be printed.

### mersenne_primes:
Function prints numbers divided by a space character.  
Invoking the script runs this function.

### mersenne_primes_format:
Function prints every number in a new line formatted to display in the $2^{n}-1$ form as well.

## Installing the dependencies

### Used packages
This script require the math, doctest and sys package.

## How to use it
#### 1. Clone this repository:
```bash
$ git clone https://github.com/StokicDusan/MersennePrime
$ cd MersennePrime/
```
#### 2. Launch:
In the command line simply invoke the script with one argument:
```bash
$ python mersennePrimes.py argv1
```
* argv1:  
Any positive integer  

:warning: *Note:* Other input will result in an error

Invoking the script with no arguments will run testmod().

## Examples

The following code block shows examples of calling the mersennePrimes script from terminal.

```bash
$ python3 mersennePrimes.py -20

$ python3 mersennePrimes.py 0

$ python3 mersennePrimes.py 1
3

$ python3 mersennePrimes.py 9
3 7 31 127 8191 131071 524287 2147483647 2305843009213693951
```
## Provide Feedback 👍

If you encounter any bugs or have suggestions, please file an issue in the [Issues][issues-url] section of the project.

[contributors-shield]: https://img.shields.io/github/contributors/StokicDusan/MersennePrime
[contributors-url]: https://github.com/StokicDusan/MersennePrime/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/StokicDusan/MersennePrime?style=social
[forks-url]: https://github.com/StokicDusan/MersennePrime/network/members
[issues-shield]: https://img.shields.io/github/issues/StokicDusan/MersennePrime
[issues-url]: https://github.com/StokicDusan/MersennePrime/issues
[commit-activity-shield]: https://img.shields.io/github/last-commit/StokicDusan/MersennePrime
[commit-activity-url]: https://github.com/StokicDusan/MersennePrime/graphs/commit-activity
[license-url]: https://github.com/StokicDusan/MersennePrime/blob/main/LICENSE
[license-shield]: https://img.shields.io/github/license/StokicDusan/MersennePrime
[repo-size-shield]: https://img.shields.io/github/repo-size/StokicDusan/MersennePrime
[repo-size-url]: https://img.shields.io/github/repo-size/StokicDusan/MersennePrime
[linkedin-shield]: https://img.shields.io/badge/LinkedIn-0077B5?style=plastice&logo=linkedin&logoColor=white
[linkedin-url]: https://linkedin.com/in/stokicdusan
