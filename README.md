# CSS calc() Unexpected Calculation Results

This repository demonstrates a common issue encountered when using the `calc()` function in CSS: unexpected results due to operator precedence and inconsistent units.

The `bug.css` file showcases the problematic code. The `bugSolution.css` file provides the solution.

## Problem

The `calc()` function, while powerful, requires careful attention to operator precedence and units.  Mixing percentages and pixels without proper parentheses can lead to miscalculations and unexpected layout behavior.