# React Memory Leak Bug

This repository demonstrates a common bug in React applications: memory leaks caused by improper use of the `setInterval` function within the `useEffect` hook.  The bug example shows a component that continuously increments a counter using `setInterval` without a proper cleanup function. This results in the interval continuing to run even after the component is unmounted from the DOM, leading to a memory leak.

The solution demonstrates the correct way to use `setInterval` within `useEffect` to prevent this issue.