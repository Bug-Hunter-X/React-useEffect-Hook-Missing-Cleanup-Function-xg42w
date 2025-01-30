# React useEffect Hook Missing Cleanup Function

This repository demonstrates a common error in React applications: forgetting to include a cleanup function in the `useEffect` hook. This can lead to memory leaks and unexpected behavior when the component unmounts.

## Bug

The `bug.js` file shows an example of an `useEffect` hook that is missing a cleanup function. This hook updates the document title whenever the `count` state variable changes. However, when the component unmounts, the effect is not properly cleaned up, leading to potential issues.

## Solution

The `bugSolution.js` file demonstrates the corrected version of the `useEffect` hook, which includes a cleanup function. This function ensures that any side effects are properly cleaned up when the component unmounts, preventing memory leaks and ensuring proper behavior.

## How to run

1. Clone this repository.
2. Navigate to the directory in your terminal.
3. Run `npm install` to install the required packages.
4. Run `npm start` to start the development server.