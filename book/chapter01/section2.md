# 1.2 Algorithms as a technology

## Notes

No notes yet.

## Exercises

### 1.2-1

**Give an example of an application that requires algorithmic content at the application level, and discuss the function of the algorithms involved.**

An example of an applciation that requires algorithmic content at the application level is an API that serves a list of restaurants sorted by their user ratings. Algorithms are involved in the API since the conception, while choosing the most beneficial data structures to store restaurant informations and algorithms are also responsible for sorting the restaurants.

### 1.2-2

**Suppose that for inputs of size $n$ on a particular computer, insertion sort runs in $8 n^{2}$ steps and merge sort runs in $64 n \lg{n}$ steps. For which values of $n$ does insertion sort beat merge sort?**

We know that insertion sort performance beats merge sort for all values of $n$ in which $8 n^{2} < 64 n \lg{n}$. That is, for all value of $n$ in which $n < 8 \lg{n}$. Numerically, since $n$ can only assume natural value, that would be the interval 1 < $n$ < 44.

### 1.2-3

**What is the smallest value of $n$ such that an algorithm whose running time is $100n^{2}$ runs faster than an algorithm whose running time is $2^{n}$.**

We want the smallest value of $n$ such that $100n^{2} < 2^{n}$. The inequality solutions are $n > 14.3$ and $-0.1 < n < 0.1$. Therefore, the value we are searching for is $n=15$.