# CSS Calc() Inconsistency

This repository demonstrates a subtle bug related to the `calc()` function in CSS when combining percentage and pixel units.  Some browsers may interpret the expression differently, leading to inconsistent layouts.

The `bug.css` file contains the problematic CSS.  The solution is provided in `bugSolution.css`.

## Reproducing the bug

1. Clone this repository.
2. Open `index.html` in different browsers (Chrome, Firefox, Safari, etc.).
3. Observe the differences in the width of the `.element`.

## Solution

The solution avoids directly using percentages and pixels together within a single `calc()` expression.