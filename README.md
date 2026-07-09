# Missing Number Finder (Optimal Algorithmic Solution)

## 📐 Algorithm Overview
This repository contains a highly optimized C++ solution for finding a single missing number in a sequence from $1$ to $n$. Instead of using memory-heavy arrays or sorting algorithms, this approach leverages the **Triangular Number Equation** (Gauss's summation formula) to compute the result with optimal efficiency.

## 🧮 Mathematical Logic
The total sum of numbers from $1$ to $n$ is calculated using the formula:
$$\text{Total Sum} = \frac{n \times (n + 1)}{2}$$

By subtracting the sum of the given $n-1$ elements from the theoretical total sum, the missing number is uncovered instantly in:
* **Time Complexity:** $O(n)$ to read the input elements.
* **Space Complexity:** $O(1)$ auxiliary space, as it only stores variables without using arrays.

## 🛠️ How to Compile and Run
To run this program locally on your machine, use any standard G++ compiler:
```bash
g++ -O3 main.cpp -o missing_finder
./missing_finder
