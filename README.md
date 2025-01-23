# CSS `calc()` Function Inconsistency

This repository demonstrates an uncommon issue with the CSS `calc()` function when combining percentages and fixed lengths in a single expression. The problem lies in the order of operations and how different browsers interpret the calculation.

The `bug.css` file contains the problematic code. The `bugSolution.css` provides a workaround to ensure consistent behavior across different browsers.

## Problem
The expected result is that the element's width should be 20% of its container's width plus 10 pixels. However, due to variations in browser interpretations, this may not always be the case.

## Solution
The solution involves separating the percentage-based calculations from the fixed-length additions. This ensures that the calculations are performed correctly regardless of the browser.

## Setup
No special setup is required to run this example. Simply open the HTML file (or a file containing the provided CSS rules) in your browser to observe the behavior.