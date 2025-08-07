# incubyte-tdd-assessment

# incubyte-tdd-assessment

# Incubyte TDD Assessment - String Calculator

This repository contains the solution for the Incubyte TDD assessment for the Software Craftsperson - Python role.

## Overview
The task is to create a String Calculator using Test-Driven Development (TDD) principles. The calculator should be able to handle a string of comma-separated numbers, new lines between numbers, custom delimiters, and throw an exception for negative numbers.

## Implementation
* Language: Python
* Testing framework: `unittest`

## Features
* Handles empty string input: returns 0
* Handles one or more numbers (comma-separated or with new lines)
* Supports custom delimiters
* Throws exception for negative numbers with message showing all negatives

## Files
* `string_calculator.py`: Implementation of the String Calculator
* `test_string_calculator.py`: Unit tests for the String Calculator

## Running Tests
Run tests using:
```bash
python test_string_calculator.py
