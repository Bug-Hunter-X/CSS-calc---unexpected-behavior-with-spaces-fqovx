# CSS calc() Unexpected Behavior with Spaces

This repository demonstrates an uncommon error in CSS involving the `calc()` function. The error occurs when extra spaces are present around the operators within the `calc()` expression, leading to unexpected results.  The issue is easily resolved by removing the unnecessary spaces.

## Bug Report

The original CSS code exhibits unexpected behavior when spaces are included around the plus operator in a `calc()` expression.  This results in the calculation not being performed correctly. 

## Solution

The solution simply involves removing the spaces around the operator within the `calc()` function, allowing the correct calculation to be made.

## How to reproduce

1. Clone the repository.
2. Open `bug.css` to see the incorrect usage of `calc()`. 
3. Open `bugSolution.css` to see the corrected usage.
4. Observe the difference in rendered output in a browser.