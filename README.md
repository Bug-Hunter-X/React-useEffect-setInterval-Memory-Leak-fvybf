# React useEffect setInterval Memory Leak
This example demonstrates a common mistake in React: using `setInterval` within `useEffect` without proper cleanup.  This leads to memory leaks because the interval continues to run even after the component unmounts.

The `bug.js` file contains the buggy code. The `bugSolution.js` file provides the corrected version.