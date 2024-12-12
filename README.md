# Uncommon HTML Errors

This repository demonstrates two uncommon errors that can occur in HTML:

1. **Accessing a Non-Existent Element:** Attempting to access an element that doesn't exist in the DOM using `document.getElementById()` will throw an error.  A safer approach is using `document.querySelector()` which handles the case of no matching elements gracefully.
2. **Using Reserved Keywords as Identifiers:** Using reserved JavaScript keywords (like `class` and `for`) as variable names can lead to unexpected behavior and syntax errors.

The `bug.html` file contains the buggy code, and `bugSolution.html` provides the corrected version.

This example highlights the importance of careful element selection and proper use of variable names.