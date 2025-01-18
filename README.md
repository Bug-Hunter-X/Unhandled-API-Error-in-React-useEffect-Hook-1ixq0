# Unhandled API Error in React useEffect Hook

This repository demonstrates a common error in React applications involving the `useEffect` hook and asynchronous API calls. The provided code fetches data from an API endpoint.  If the API request fails (e.g., due to a network issue or server error), the error is logged to the console, but there's no user-friendly way to handle it. This could lead to a poor user experience or unexpected behavior.

The solution focuses on implementing robust error handling to improve the application's reliability and provide informative feedback to the user.

## Bug
The `bug.js` file contains a React component that fetches data using the `useEffect` hook. The error handling is insufficient, simply logging the error to the console. This makes it difficult for the user to understand that something went wrong. 

## Solution
The `bugSolution.js` file shows how to correctly handle errors gracefully.  It includes a more robust way to handle API request failures.  The solution shows how to: 

1. Display an error message to the user when the API request fails.
2. Provide a better user experience, avoiding unexpected behavior caused by undefined data.
3. Implement a loading state to display while the request is being processed.