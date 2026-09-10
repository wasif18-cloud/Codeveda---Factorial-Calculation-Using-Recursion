# Factorial Calculation Using Recursion

A simple Java console application that calculates the factorial of a number using a recursive function.

## 📌 Project Overview

This project demonstrates the use of **recursion in Java** to calculate the factorial of a given number.

The program takes a number from the user and calculates its factorial by repeatedly calling the same function until the base condition is reached.

## 🎯 Objective

The main objectives of this project are:

- To understand recursion in Java.
- To create and use a recursive function.
- To take input from the user using `Scanner`.
- To use conditional statements.
- To calculate the factorial of a number.
- To handle negative numbers.

## 🧮 What is Factorial?

The factorial of a non-negative number `n` is the multiplication of all positive integers from `n` to `1`.

For example:

```text
5! = 5 × 4 × 3 × 2 × 1
   = 120
```

## 🔄 What is Recursion?

Recursion is a programming technique where a function calls itself.

### Example

For `5`:

```text
factorial(5)
     ↓
5 × factorial(4)
     ↓
5 × 4 × factorial(3)
     ↓
5 × 4 × 3 × factorial(2)
     ↓
5 × 4 × 3 × 2 × factorial(1)
     ↓
5 × 4 × 3 × 2 × 1
     ↓
120
```

## 🛠️ Technologies Used

- Java
- Java Scanner
- Recursion
- Console Application

## 📋 Program Logic

The program works in the following steps:

1. Start the program.
2. Take a number from the user.
3. Check if the number is negative.
4. If the number is negative, display an error message.
5. If the number is valid, call the `factorial()` function.
6. Check the base case.
7. If `n` is `0`, return `1`.
8. Otherwise, multiply `n` by `factorial(n - 1)`.
9. Continue until the base case is reached.
10. Display the factorial result.
11. Close the Scanner and end the program.


