
### JavaScript Coding Problems

| #  | Question | Difficulty | What You Learn | JavaScript Topics |
|----|----------|------------|----------------|-------------------|
| 1  | [What are the steps to check if a number is a palindrome?](#what-are-the-steps-to-check-if-a-number-is-a-palindrome) | Easy | Learn string reversal and symmetry logic. | String Manipulation, Algorithms |
| 2  | [What are the steps to remove duplicates from an array?](#what-are-the-steps-to-remove-duplicates-from-an-array) | Medium | Learn array cleaning techniques and data processing. | Array Methods, Set Operations |
| 3  | [How to find the longest word in a string?](#how-to-find-the-longest-word-in-a-string) | Medium | Learn to parse and analyze text data. | String Manipulation, Array Methods |
| 4  | [How to check if two strings are anagrams of each other?](#how-to-check-if-two-strings-are-anagrams-of-each-other) | Medium | Learn text comparison and string sorting techniques. | String Manipulation, Sorting |
| 5  | [How to reverse a string without using built-in methods?](#how-to-reverse-a-string-without-using-built-in-methods) | Medium | Learn string manipulation without relying on built-in methods. | String Manipulation, Loops |
| 6  | [How to find the factorial of a number using recursion?](#how-to-find-the-factorial-of-a-number-using-recursion) | Medium | Learn recursion and how to solve problems with it. | Recursion, Functions |
| 7  | [How to find the first non-repeated character in a string?](#how-to-find-the-first-non-repeated-character-in-a-string) | Medium | Learn efficient string analysis and data cleaning. | String Manipulation, Hashing |
| 8  | [What are the steps to check if a number is prime?](#what-are-the-steps-to-check-if-a-number-is-prime) | Medium | Learn number theory concepts and optimization. | Number Theory, Algorithms |
| 9  | [How to implement a basic stack data structure in JavaScript?](#how-to-implement-a-basic-stack-data-structure-in-javascript) | Hard | Learn the implementation of a stack data structure. | Data Structures (Stack), Algorithms |
| 10 | [How to find the maximum product of two integers in an array?](#how-to-find-the-maximum-product-of-two-integers-in-an-array) | Hard | Learn optimization algorithms for numerical analysis. | Array Methods, Sorting, Optimization |

---

### Theory Based Questions

| #  | Question | Difficulty | What You Learn | JavaScript Topics |
|----|----------|------------|----------------|-------------------|
| 1  | [What is the difference between `var`, `let`, and `const` in JavaScript?](#what-is-the-difference-between-var-let-and-const-in-javascript) | Easy | Learn about variable scoping and best practices in JS. | Variable Scoping, ES6 Features |
| 2  | [What is the difference between `==` and `===` in JavaScript?](#what-is-the-difference-between-and-in-javascript) | Easy | Learn how JavaScript handles comparison and type coercion. | Equality Operators, Type Coercion |
| 3  | [How does JavaScript interact with the DOM?](#how-does-javascript-interact-with-the-dom) | Easy | Learn how JavaScript can manipulate HTML and CSS through the DOM. | DOM Manipulation, Events |
| 4  | [What is hoisting in JavaScript, and how does it work?](#what-is-hoisting-in-javascript-and-how-does-it-work) | Medium | Learn about the JavaScript execution context and variable declarations. | Hoisting, Scope |
| 5  | [What is `MutationObserver`, and what are its use cases?](#what-is-mutationobserver-and-what-are-its-use-cases) | Medium | Learn how to monitor DOM changes efficiently with `MutationObserver`. | MutationObserver, DOM Manipulation |
| 6  | [What is JavaScript prototypes, and how do they function?](#what-are-javascript-prototypes-and-how-do-they-function) | Medium | Learn about prototypes and inheritance in JavaScript. | Prototypes, Inheritance |
| 7  | [What are higher-order functions, and how do they work?](#what-are-higher-order-functions-and-how-do-they-work) | Hard | Learn how to work with functions that accept other functions as arguments. | Higher-order Functions, Functional Programming |
| 8  | [What is functional programming, and how is it applied in JavaScript?](#what-is-functional-programming-and-how-is-it-applied-in-javascript) | Medium | Learn how to write clean, maintainable, and bug-free code using functional programming. | Functional Programming, High-order Functions |
| 9  | [How can you optimize DOM manipulations for better performance?](#how-can-you-optimize-dom-manipulations-for-better-performance) | Hard | Learn techniques to improve front-end performance. | DOM Optimization, Performance |
| 10 | [What are closures in JavaScript, and how are they used?](#what-are-closures-in-javascript-and-how-are-they-used) | Hard | Learn about closures, scope chains, and data encapsulation in JavaScript. | Closures, Scope Chain |
| 11 | [How does JavaScript handle asynchronous operations?](#how-does-javascript-handle-asynchronous-operations) | Hard | Learn about asynchronous programming with callbacks, promises, and async/await. | Asynchronous JavaScript, Promises, Callbacks |

---

### Detailed Explanations

#### [What are the steps to check if a number is a palindrome?](#what-are-the-steps-to-check-if-a-number-is-a-palindrome)
- Reverse the number and check if it's the same as the original number.

#### [What are the steps to remove duplicates from an array?](#what-are-the-steps-to-remove-duplicates-from-an-array)
- Use `Set` to eliminate duplicates or filter through the array.

#### [How to find the longest word in a string?](#how-to-find-the-longest-word-in-a-string)
- Split the string into words and find the word with the maximum length.

#### [How to check if two strings are anagrams of each other?](#how-to-check-if-two-strings-are-anagrams-of-each-other)
- Sort both strings and compare if they are the same.

#### [How to reverse a string without using built-in methods?](#how-to-reverse-a-string-without-using-built-in-methods)
- Loop through the string from end to start and create a new reversed string.

#### [How to find the factorial of a number using recursion?](#how-to-find-the-factorial-of-a-number-using-recursion)
- Use a recursive function where the base case is 1.

#### [How to find the first non-repeated character in a string?](#how-to-find-the-first-non-repeated-character-in-a-string)
- Use an object or `Map` to track character frequencies.

#### [What are the steps to check if a number is prime?](#what-are-the-steps-to-check-if-a-number-is-prime)
- Check if the number is divisible by any number from 2 to its square root.

#### [How to implement a basic stack data structure in JavaScript?](#how-to-implement-a-basic-stack-data-structure-in-javascript)
- Create a `Stack` class with `push`, `pop`, and `peek` methods.

#### [How to find the maximum product of two integers in an array?](#how-to-find-the-maximum-product-of-two-integers-in-an-array)
- Sort the array and return the product of the two largest or two smallest numbers.

---

#### [What is the difference between `var`, `let`, and `const` in JavaScript?](#what-is-the-difference-between-var-let-and-const-in-javascript)
- `var`: Function-scoped, can be re-assigned.
- `let`: Block-scoped, can be re-assigned.
- `const`: Block-scoped, cannot be re-assigned.

#### [What is the difference between `==` and `===` in JavaScript?](#what-is-the-difference-between-and-in-javascript)
- `==` performs type coercion, while `===` checks both value and type without coercion.

#### [How does JavaScript interact with the DOM?](#how-does-javascript-interact-with-the-dom)
- JavaScript can manipulate HTML elements, change styles, and handle events through the DOM.

#### [What is hoisting in JavaScript, and how does it work?](#what-is-hoisting-in-javascript-and-how-does-it-work)
- Hoisting is the process of moving declarations to the top of their scope before execution.

#### [What is `MutationObserver`, and what are its use cases?](#what-is-mutationobserver-and-what-are-its-use-cases)
- `MutationObserver` allows you to watch for changes in the DOM and act accordingly.

#### [What is JavaScript prototypes, and how do they function?](#what-are-javascript-prototypes-and-how-do-they-function)
- Prototypes allow objects to inherit properties and methods from other objects.

#### [What are higher-order functions, and how do they work?](#what-are-higher-order-functions-and-how-do-they-work)
- Higher-order functions are functions that take other functions as arguments or return functions.

#### [What is functional programming, and how is it applied in JavaScript?](#what-is-functional-programming-and-how-is-it-applied-in-javascript)
- It focuses on writing functions that avoid side effects and use pure functions.

#### [How can you optimize DOM manipulations for better performance?](#how-can-you-optimize-dom-manipulations-for-better-performance)
- Minimize reflows and repaints by batch-processing DOM changes or using `DocumentFragment`.

#### [What are closures in JavaScript, and how are they used?](#what-are-closures-in-javascript-and-how-are-they-used)
- Closures allow functions to remember their lexical scope even when executed outside that scope.

#### [How does JavaScript handle asynchronous operations?](#how-does-javascript-handle-asynchronous-operations)
- JavaScript uses callbacks, promises, and async/await to manage async operations.

---
