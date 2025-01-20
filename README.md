# React useEffect Dependency Array Issue

This repository demonstrates a common error in React's `useEffect` hook related to the dependency array.  The example shows how an incorrect dependency array can lead to unexpected behavior and how to fix it.

## Bug Description
The provided code uses `useEffect` to log a message when the `count` is greater than 0. However, due to an issue with the dependency array, the conditional logic within `useEffect` never executes. This happens because the `count` value is not updated appropriately in the component due to the incomplete logic.

## Solution
The solution is fixing the incorrect conditional logic and updating the dependency array correctly. 
