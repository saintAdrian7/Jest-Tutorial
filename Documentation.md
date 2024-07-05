

## Setup Process
1. Initialized a new project using `npm init -y`.
2. Installed Jest using `npm install jest --save-dev`.
3. Created `calculator.js` and `calculator.test.js` files.

## Functions
- **add(a, b):** Returns the sum of `a` and `b`.
- **subtract(a, b):** Returns the difference between `a` and `b`.

## Tests
- **add(1, 2):** Expects the result to be `3`.
- **subtract(5, 2):** Expects the result to be `3`.

## Test Results
PS C:\Users\Admin\Jest Tutorial> npx jest
 PASS  ./calculator.test.js
  √ adds 1 + 2 to equal 3 (7 ms)
  √ subtracts 5 - 2 to equal 3 (1 ms)

Test Suites: 1 passed, 1 total
Tests:       2 passed, 2 total
Snapshots:   0 total
Time:        1.347 s
Ran all test suites.
