# CSS `calc()` Error: Missing Number Before Percentage

This repository demonstrates a subtle but easily overlooked error in using the CSS `calc()` function.  The issue arises when a percentage value is used within the `calc()` expression without a preceding number.  This typically results in unexpected behavior or parsing errors.

The `bug.css` file contains the erroneous code, while `bugSolution.css` provides the corrected version.

## How to reproduce
1. Open `bug.html` in a web browser.
2. Observe the unexpected width of the element.
3. Replace `bug.css` with `bugSolution.css` and see the corrected behavior.

## Conclusion
This example highlights the importance of carefully constructing `calc()` expressions to avoid errors. Always ensure that percentage values within `calc()` have a preceding number.