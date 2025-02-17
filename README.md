# CSS calc() Space Issue

This repository demonstrates an uncommon issue with the CSS `calc()` function.  Unexpected spaces around the operators within the `calc()` function can prevent it from working correctly.

**bug.css** shows the code with the incorrect spacing. **bugSolution.css** shows the corrected code.

This is a subtle error that can be hard to track down. Always ensure there are no spaces around the `+`, `-`, `*`, or `/` operators within a `calc()` expression.