# CSS Nested Element Hover Issue

This repository demonstrates a common, yet subtle, CSS bug related to the `:hover` pseudo-class and nested elements.  The issue arises when the hover effect on a nested element is unintentionally overridden by the parent element's hover state.  The solution provides a strategy to resolve this conflict.

## Bug Description
The provided `bug.css` file contains CSS that causes the inner `.inner` element's hover effect to not apply properly due to the parent `.outer` element's `:hover` selector. This demonstrates the unexpected behavior.

## Solution
The `bugSolution.css` file provides a solution that uses more specific selectors to correctly apply the hover effect to the `.inner` element without being overridden.

## How to Reproduce
1. Clone this repository.
2. Open `index.html` (you'll need to create a simple HTML file with the corresponding class structure) in a web browser.
3. Observe the behavior of the nested element when hovering over it and the parent element.  The `bug.css` will show the unexpected behavior, while `bugSolution.css` demonstrates the fix.