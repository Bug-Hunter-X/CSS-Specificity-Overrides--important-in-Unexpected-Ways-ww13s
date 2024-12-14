# CSS Specificity and !important Surprise

This repository demonstrates a subtle yet important interaction between CSS specificity and the `!important` declaration.  It's easy to assume that `!important` always wins, but as this example shows, specificity plays a crucial role. 

The `bug.css` file contains the problematic code. The `bugSolution.css` demonstrates a solution.  The issue centers around unexpected color inheritance when a more specific selector is applied to a nested element.