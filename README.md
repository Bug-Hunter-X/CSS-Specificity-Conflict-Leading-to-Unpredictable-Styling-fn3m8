# CSS Specificity Conflict

This repository demonstrates a common CSS bug involving specificity conflicts that lead to unpredictable styles.  The bug is challenging to track down as the unexpected styling is not immediately obvious.

## Bug Description

The `bug.css` file contains two CSS rules that target the same element but have equal specificity. This leads to inconsistent and unpredictable rendering, depending on the order of CSS rules or other factors that are hard to trace.

## Solution

The `solution.css` file provides a solution.  The solution relies on understanding CSS Specificity and using more specific selectors or the `!important` flag(though this is generally discouraged for maintainability).  The best solution is to avoid the conflict altogether through careful analysis of the CSS specificity rules.

## How to Reproduce

1. Clone this repository.
2. Open `index.html` in your browser.
3. Observe the inconsistent styling caused by the specificity conflict.