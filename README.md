# CSS Specificity Bug

This repository demonstrates a subtle bug related to CSS selector specificity.  The bug arises from the unexpected behavior of more specific selectors overriding less specific ones, even if the less specific selector seems like it should take precedence based on the order in the stylesheet.

The `bug.css` file contains the erroneous code. The `bugSolution.css` demonstrates one method to address the unexpected behavior.

The issue is explained in more detail in the `bug.css` file.