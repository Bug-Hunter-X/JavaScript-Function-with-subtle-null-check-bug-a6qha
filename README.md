# JavaScript Function with subtle null check bug

This repository demonstrates a common, yet subtle bug in JavaScript functions involving null checks.

## Bug Description
The provided JavaScript function `foo` checks for null values in its input parameters (a and b). While the function correctly handles null inputs, it fails to handle cases where either parameter is undefined. This leads to unexpected behavior when undefined values are passed to the function.

## Bug Reproduction
1. Clone the repository
2. Run the `bug.js` file using a JavaScript interpreter (e.g., node.js)
3. Observe the output; the results for undefined inputs may be unexpected.

## Solution
The `bugSolution.js` file provides a corrected version of the `foo` function. The solution explicitly handles both null and undefined values, ensuring robust behavior in various scenarios.

## How to run
You can run the bug and solution file with nodejs.
```bash
node bug.js
node bugSolution.js
```