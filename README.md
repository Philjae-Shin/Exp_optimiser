# Implementation of Exponential Functions in Haskell

## Overview

This project involves implementing the mathematical exponential function, commonly denoted as `n^k`, where `n` and `k` are integers. The function computes the power of `n` raised to `k`, and this implementation will focus on cases where `k` is non-negative.

## Setup Instructions

1. Clone the repository containing the initial codebase.
2. Extract the contents into your desired directory.

## Compilation and Testing

To ensure functionality, follow these steps:

1. Open the project in VSCode. If you are on Windows, consider using WSL mode.
2. Launch the integrated terminal within VSCode:
    - Use the menu option `Terminal -> New Terminal`
    - Or the shortcut `Ctrl + Shift + ‘`
3. Update the Haskell package list:
    ```bash
    cabal update
    ```
4. Compile the project along with the tests:
    ```bash
    cabal build
    ```
5. Run the tests to validate the implementation:
    ```bash
    cabal test
    ```

Initially, all tests will fail since the base functions are unimplemented. Implementations should be written in `Power.hs`. Avoid renaming any predefined function or modifying additional files.

## Development Tasks

### Task 1
Analyze and document the computational steps required for the power function.

### Task 2
Implement the power function using Haskell's `product` function to compute the result from a list of repeated elements.

### Task 3
Explore an optimized method for the power function, utilizing properties of even and odd numbers to reduce computational steps.

### Task 4
Verify the correctness of the implementations by comparing the outputs of different methods.

### Task 5
Complete a function that generates a list of test results for various combinations of base numbers and exponents.

Each implementation should ensure that the basic function and its optimized versions yield the same outputs for any given inputs.

## Contribution

Feel free to fork this repository, submit changes, or suggest improvements via pull requests.


## Cabal commands

- Update package list: `cabal update`
- Compile and tests: `cabal build`
- Run tests: `cabal test`
- Open in GHCi: `cabal repl`
