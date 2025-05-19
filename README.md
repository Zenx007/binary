# Decimal to Binary Converter

![Project Status](https://img.shields.io/badge/Status-Complete-green) 
![Language](https://img.shields.io/badge/Language-C%2B%2B-blue) 
![Academic Project](https://img.shields.io/badge/Academic-Project-orange)

## Description

This is a simple C++ program that converts non-negative decimal numbers to their binary (base-2) equivalents. The program uses a stack data structure to reverse the remainders obtained during the conversion process, ensuring the correct binary representation.

This project was developed as part of a college assignment for a Data Structures or Programming Fundamentals course.

## Features

- Converts decimal numbers to binary
- Handles multiple inputs in a single run
- Validates input to ensure only non-negative numbers are processed
- Uses stack to properly reverse the binary digits

## How It Works

1. The program asks how many numbers you want to convert
2. For each number:
   - Validates that the input is non-negative
   - Pushes valid numbers onto a stack
3. For each number in the stack:
   - Converts the number to binary by:
     1. Repeatedly dividing by 2 and pushing remainders onto a stack
     2. Popping the remainders to construct the binary string
   - Prints both the original decimal and converted binary numbers

## Requirements

- C++ compiler (g++, clang++, or MSVC)
- Standard Library support
