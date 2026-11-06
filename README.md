# PF Lab 07 – Functions

This repository contains my solutions for **Lab#07** of the course **CL-1002 Programming Fundamentals** (FAST-NUCES, Fall 2026), taught by Sir Muhammad Aais Rabbani.

All programs are written in **C**. Every user-defined function has a prototype above `main` and its definition below `main`, with a comment stating its category (no arguments/no return, arguments/no return, no arguments/returns a value, arguments/returns a value).

## Programs Included
1. **Pattern Printer** – prints a welcome banner and a square of any character using `welcome()` and `printSquare()`.
2. **Right-Angled Triangle Calculator** – finds the hypotenuse, rounded values, and area using `math.h` functions (`sqrt`, `pow`, `ceil`, `floor`).
3. **Electricity Bill** – calculates a slab-based bill with 5% tax above Rs 3000, using `readUnits()` and `calculateBill()`.
4. **Temperature Converter** – converts between Celsius and Fahrenheit and prints a conversion table using `toFahrenheit()`, `toCelsius()`, and `printTable()`.
5. **Number Analyzer** – reports whether a number is prime, perfect, a palindrome, its reverse, digit sum, and all primes up to it.
6. **Mini Math Toolkit** – menu-driven program for power, factorial, GCD, and LCM using functions of all four categories.

## How to Run
```bash
gcc filename.c -o output -lm
./output
```
(`-lm` is needed only for Question#2, which uses `math.h`)

## Author
Muhammad Saif – Software Engineering, FAST-NUCES Peshawar
