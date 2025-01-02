# React Native Uninitialized State Bug

This repository demonstrates a common bug in React Native applications: accessing state variables before they've been initialized.  The `UninitializedStateBug.js` file shows the problematic code, while `UninitializedStateBugSolution.js` provides a corrected version.

## Problem

Attempting to access state values within the `render` method before `useState` has set the initial state can lead to unexpected behavior, often resulting in `undefined` values or crashes.