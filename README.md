AI-Based Prime Number Generator and Checker

Overview

This project implements an AI-based approach to generate and check prime numbers using Python. It combines the traditional Sieve of Eratosthenes for efficient prime generation with a Logistic Regression model to predict whether a number is prime.

Features

Efficient Prime Number Generation using the Sieve of Eratosthenes.

Machine Learning Model (Logistic Regression) for prime number classification.

AI-Based Prime Checking for rapid number classification.

Installation

To run this project, install the required dependencies:

pip install numpy scikit-learn

Usage

Run the script to generate prime numbers and check primality using AI:

python ai_prime_checker.py

Code Explanation

Prime Generation: Uses the Sieve of Eratosthenes to generate a list of prime numbers.

Training Data Preparation: Creates labeled data where prime numbers are marked as 1 and non-prime numbers as 0.

Training AI Model: A Logistic Regression model is trained on this dataset.

AI-Based Prime Checking: The trained model predicts if a given number is prime.

Example Output

Generated prime numbers up to 100: [2, 3, 5, 7, 11, 13, ...]
AI-based Prime Check for 29: True

Future Enhancements

Implement Neural Networks for improved classification accuracy.

Extend the dataset range for better AI performance.

Combine AI with deterministic methods for hybrid checking.

Author

Developed by [Prashant Kumar]
