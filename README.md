# Unexpected Calculation with calc() Using Percentages and Viewport Units

This repository demonstrates a CSS bug related to unexpected calculations when using the `calc()` function with percentages and viewport units (like `vw` or `vh`).  The expected result doesn't match the actual rendered output.

## Bug Description

The issue arises when attempting to calculate a value based on both a percentage and viewport units within a single `calc()` expression.  The calculated value is inconsistent across browsers, and frequently incorrect.

## Reproduction Steps

1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Observe the rendered element's width or height and compare it to the expected value based on the `calc()` expression in `bug.css`.

## Solution

The solution might involve alternative methods for achieving the desired layout, such as using JavaScript for dynamic calculations or restructuring the CSS to avoid the problematic combination of units within `calc()`. See `bugSolution.css` for one possible approach. 