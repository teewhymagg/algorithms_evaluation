# Algorithms_evaluation
Experimental comparison of popular pattern-matching algorithms (Brute force, KMP, Boyer Moore)

# Pattern Matching Algorithms Comparison

## Introduction and Problem Description

Pattern matching is a fundamental operation in computer science used in various applications like text processing, data mining, and bioinformatics. This project aims to experimentally compare the performance of three popular pattern-matching algorithms: Brute Force, Knuth-Morris-Pratt (KMP), and Boyer-Moore. The focus is on evaluating their relative speeds when applied to large text documents with varying-length patterns.

## Algorithms Overview

### Brute Force Algorithm

The Brute Force algorithm compares each character of the pattern sequentially against the text, starting from the beginning. It has a time complexity of O(mn), where m is the pattern length and n is the text length.

### Knuth-Morris-Pratt (KMP) Algorithm

KMP improves upon Brute Force by utilizing a precomputed prefix table. This table helps in skipping unnecessary comparisons based on previous matching information. It has a time complexity of O(m + n) for pattern matching.

### Boyer-Moore Algorithm

Boyer-Moore uses heuristic rules like the bad character and good suffix rules to efficiently skip sections of the text during search. It has a worst-case time complexity of O(mn) but can perform significantly better in practice.

## Description of Text Documents Used for Testing

### Random Character Sequence

A randomly generated text file consisting of a large number of random characters.

### Passwords

A downloaded text file containing possible passwords used by internet users, commonly used for security testing.

## Implementation and Testing

The project includes implementations of Brute Force, KMP, and Boyer-Moore algorithms to search for predefined patterns in both random character sequences and password text files. Each algorithm's execution time is recorded and compared using Python.

## Usage

1. **Clone the Repository**
   ```bash
   git clone https://github.com/teewhymagg/algorithms_evaluation.git
   ```
