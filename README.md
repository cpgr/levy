# README

`levy` is a python code to generate a random number drawn from the
Levy stable distribution L. It is based on the algorithm presented in
Mantegna, Fast, accurate algorithm for numerical simulation of Levy stable
stochastic processes, Phys Rev E, 49 (1994).

## Usage

Import the levy method using
```
from levy import levy
```
and use it as
```
levy(alpha, gamma, n)
```
where alpha is the Levy index, gamma is the shape, and n is the number of
averages to use (default is one). For example, to sample for a Levy distribution
L(1.5, 1), where alpha = 1.5 and gamma = 1, simply call
```
levy(1.5, 1)
```
