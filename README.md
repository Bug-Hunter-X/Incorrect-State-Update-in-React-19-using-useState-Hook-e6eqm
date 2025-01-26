# Incorrect State Update in React 19 using useState Hook

This repository demonstrates a common error in React 19 related to the `useState` hook.  Incorrectly using functional updates with the `useState` hook can lead to unpredictable behavior and bugs.

## The Bug
The `bug.js` file contains a component that attempts to increment a state variable using a functional update. However, the functional update does not correctly utilize the previous state, resulting in an always-1 count instead of incrementing as expected.

## The Solution
The `bugSolution.js` file provides the corrected code. It shows the correct way to use functional updates to ensure that the state variable is incremented properly.