# JavaScript Interview Questions

A curated list of JavaScript interview questions organized from core concepts to practical machine coding challenges.

## 1. Core JavaScript Concepts
*Foundational knowledge regarding the language syntax, execution context, and object models.*

1.  What are the different data types in JavaScript?
2.  Explain the difference between `var`, `let`, and `const`.
3.  What is the difference between `==` and `===`?
4.  What is the difference between `null` and `undefined`?
5.  How does type coercion work in JavaScript? Give examples.
6.  What is the difference between `undefined` and `not defined`?
7.  How does the `typeof` operator work? What is the `typeof null`?
8.  What is the difference between `isNaN()` and `Number.isNaN()`?
9.  What is **Hoisting** in JavaScript? How does it apply to variables and functions?
10. What is the difference between Function Declaration and Function Expression?
11. Explain **Closures** with a practical example.
12. What is an IIFE (Immediately Invoked Function Expression)?
13. What are Higher-Order Functions?
14. What is the difference between a Regular function and an Arrow function?
15. Explain the concept of **Currying**.
16. What is the Temporal Dead Zone (TDZ)?
17. What is the difference between parameter and argument?
18. What are "Pure Functions"?
19. What is the `this` keyword? How does its value change in different contexts?
20. Explain `call()`, `apply()`, and `bind()` methods.
21. What is the difference between **Deep Copy** and **Shallow Copy**?
22. How does Prototypal Inheritance work?
23. What is the Prototype Chain?
24. What is the difference between `Object.create()` and object literal `{}`?
25. How can you prevent an object from being modified (Freeze vs Seal)?
26. What are Getters and Setters in JavaScript objects?
27. What is the difference between `Map` and `WeakMap`?
28. What is the difference between `Set` and `WeakSet`?

## 2. Asynchronous JavaScript
*Questions regarding the event loop, promises, and handling async operations.*

29. What is the **Event Loop**? Explain the Call Stack, Callback Queue, and Microtask Queue.
30. What is the difference between **Synchronous** and **Asynchronous** code?
31. What are **Promises**? What are the possible states of a Promise?
32. Explain `async` and `await`. How is it different from `.then()` chains?
33. What is the difference between `Promise.all()`, `Promise.allSettled()`, `Promise.race()`, and `Promise.any()`?
34. What happens if you call `setTimeout` with a delay of 0ms?
35. What is the difference between `setTimeout` and `setInterval`?
36. What is "Callback Hell" and how do you avoid it?
37. How to handle errors in Async/Await?
38. Explain the concept of "Promisification" (converting callbacks to promises).

## 3. JavaScript Coding Challenges
*Logic-based problems involving strings, arrays, and algorithms.*

### String Manipulation
39. Write a program to reverse a string (with and without built-in methods).
40. Check if a string is a Palindrome.
41. Find the longest palindromic substring in a string.
42. Check if two strings are Anagrams.
43. Find the first non-repeating character in a string.
44. Find the most frequent character in a string.
45. Count the occurrences of each character in a string.
46. Remove all duplicates from a string.
47. Find the longest substring without repeating characters.
48. Reverse words in a sentence without using the built-in `reverse()` method.
49. Convert a string to an Integer (Implementation of `atoi`).
50. Implement Run-Length Encoding (Compress a string, e.g., "aaabb" → "a3b2").
51. Check if a string is a rotation of another string.
52. Check if a string is a valid shuffle of two other strings.
53. Find the longest common prefix among an array of strings.
54. Convert a sentence into an acronym (e.g., "Portable Network Graphics" → "PNG").
55. Replace spaces in a string with `%20` (URL Encoding).

### Array & Object Logic
56. Write a program to remove duplicates from an array.
57. Write a function that returns the even numbers from an array.
58. Find the maximum and minimum numbers in an array.
59. Find the maximum count of consecutive 1’s in an array.
60. Merge two sorted arrays into a single sorted array.
61. Find the largest element in a nested array (e.g., `[[3, 4], [7, 8, [10, 11]]]`).
62. Flatten a nested array into a single-dimensional array (Deep Flatten).
63. Given an array of objects, write a function to return unique objects based on a property (e.g., `id` or `name`).
64. Create a function that compares two arrays and returns `true` if every value in the first array has its corresponding square in the second array (frequency must be the same).
65. Write a function that converts a string path into an object (e.g., `"a.b.c", "value"` → `{a: {b: {c: "value"}}}`).
66. Write a function to generate the Fibonacci sequence up to `n` terms.
67. Write a function to check if a given number is prime.
68. Find the factorial of a given number.

## 4. Advanced & Modern JavaScript (ES6+)
*Questions regarding DOM manipulation, web APIs, memory, and ES6+ features.*

69. What is the DOM (Document Object Model)?
70. What is the difference between `window` and `document`?
71. What is **Event Bubbling** vs. **Event Capturing**?
72. What is **Event Delegation**?
73. What is the difference between `e.preventDefault()` and `e.stopPropagation()`?
74. How does `localStorage` differ from `sessionStorage` and `cookies`?
75. What is the Fetch API?
76. What is the Intersection Observer API?
77. Explain the concept of **Debouncing** and **Throttling**.
78. What are **Generators** and **Iterators**?
79. What is Memoization?
80. What are JavaScript Modules (ESM)? How do `import` and `export` work?
81. What is the **Spread** operator vs **Rest** parameter?
82. What is Destructuring assignment?
83. What is the Nullish Coalescing operator (`??`)?
84. What is Optional Chaining (`?.`)?
85. What are Memory Leaks in JavaScript? How do you detect and prevent them?
86. What is Garbage Collection in JavaScript?
87. What is a Service Worker?

## 5. Practical Implementation (Machine Coding)
*Tasks involving writing polyfills and custom utility functions.*

88.  Implement your own version of `Array.prototype.map`.
89.  Implement your own version of `Array.prototype.filter`.
90.  Implement your own version of `Array.prototype.reduce`.
91.  Implement a generic `debounce` function.
92.  Implement a generic `throttle` function.
93.  Write a function to perform a Deep Clone of an object.
94.  Implement a custom `bind` method.
95.  Implement a `Promise.all` polyfill.
96.  Create a simple **Event Emitter** class (subscribe, emit, unsubscribe).
97.  Implement a function that executes N async tasks in series.
98.  Implement a function that executes N async tasks in parallel.
99.  Write a function to flatten a deeply nested object.
100. Implement an infinite currying function (e.g., `add(1)(2)(3)...()`).
