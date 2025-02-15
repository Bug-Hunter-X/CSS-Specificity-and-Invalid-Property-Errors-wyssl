# CSS Specificity and Invalid Property Errors

This repository demonstrates and resolves common CSS errors, specifically focusing on issues related to CSS specificity and usage of unsupported properties.

## Bug Description
The primary issue lies in CSS specificity.  A more specific selector unintentionally overrides a more general selector, leading to unexpected styling outcomes.  Additionally, the code might contain invalid or unsupported CSS properties in some browsers causing rendering inconsistencies.  The use of incorrect syntax also causes parsing failure of the style sheet.

## Solution
The solution involves reviewing the CSS selectors to ensure proper specificity and checking for usage of unsupported properties. Always test your code across multiple browsers.

## How to reproduce
1. Clone this repository.
2. Open `bug.css` to see the buggy code.
3. Open `bugSolution.css` to see the solution.