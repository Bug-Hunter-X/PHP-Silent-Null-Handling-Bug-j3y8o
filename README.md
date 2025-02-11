# PHP Silent Null Handling Bug

This repository demonstrates a common issue in PHP where null values are not explicitly handled, leading to unexpected behavior.  The `bug.php` file shows the problematic code, while `bugSolution.php` provides a corrected version.

**Problem:**
The original code silently fails when null values are passed into the function.  This can lead to errors that are difficult to debug.

**Solution:**
The solution explicitly checks for null values and returns an appropriate result, preventing unexpected behavior.