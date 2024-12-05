# CSS calc() Errors
This repository demonstrates two uncommon errors related to the CSS `calc()` function:

1. **Negative Values:**  `calc()` can produce unexpected results if the calculation yields a negative value for properties like `width` or `height`.
2. **Missing Spaces:**  Spaces around operators (+, -, 
*, /) within `calc()` are mandatory.  Missing spaces can lead to parsing errors.

The `bug.css` file contains code exhibiting these errors, while `bugSolution.css` provides the corrected version.