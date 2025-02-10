# JavaScript Loose Equality with Null and Undefined

This example demonstrates a common JavaScript error related to loose equality (==) when dealing with null and undefined values.  The use of == can lead to unexpected results due to JavaScript's type coercion.

## Bug
The original code uses loose equality (==) to check for null or undefined inputs.  This is problematic because loose equality performs type coercion, leading to unexpected true/false evaluations in edge cases.

## Solution
The solution uses strict equality (===) to explicitly check for null and undefined values without type coercion, resulting in more predictable and reliable behavior.

## How to Run
1. Save the provided `bug.js` and `bugSolution.js` files.
2. Open your browser's developer console or use Node.js to run the files.
3. Observe the difference in output between the original and corrected code.