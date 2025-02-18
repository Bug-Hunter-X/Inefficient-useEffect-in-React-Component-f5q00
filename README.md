# Inefficient useEffect in React Component

This repository demonstrates a common performance issue in React applications involving the `useEffect` hook. The initial implementation causes the effect to run on every render, leading to unnecessary re-renders and potential performance problems, especially with complex components.

The solution provided demonstrates how to fix the issue and improve performance by correctly utilizing the dependency array within `useEffect`.