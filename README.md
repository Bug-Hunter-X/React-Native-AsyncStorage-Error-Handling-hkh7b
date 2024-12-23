# React Native AsyncStorage Error Handling

This example demonstrates a common error in React Native when using AsyncStorage and provides a solution for proper error handling.

## Bug

Forgetting to handle potential exceptions during AsyncStorage operations can lead to app crashes.  The `bug.js` file shows this mistake.

## Solution

The solution involves wrapping AsyncStorage calls in `try...catch` blocks to gracefully handle potential errors. The `bugSolution.js` file demonstrates this correct approach.

## How to reproduce the bug

1. Run the `bug.js` example.
2. Observe the error message in the console (if your device/emulator isn't throwing a generic error, you may have to set breakpoints).

## How to run the solution

1. Run `bugSolution.js`
2. Observe the console for messages indicating that any errors are handled successfully.