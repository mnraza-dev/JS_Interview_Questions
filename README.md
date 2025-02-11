
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

Sure! Here's the content for each link so you can check if the links are working properly. I'll use placeholder text for the explanations, but you can replace them with detailed explanations or code snippets as needed:

---

### Coding Problems

## Palindrome Number
```js
function factorialNum(x){
    let fact = 1
    for(let i=2; i<=x; i++){
            fact = fact* i
    }
    return fact;
}

console.log(factorialNum(4))
```
## Fibbonacci Number
```js
const fibboNums =[0,1]
function getFibbonacci(x){
    for(let i=2; i< x; i++){
       fibboNums[i] =  fibboNums[i-1] + fibboNums[i-2]  
    }
    return fibboNums;
}
```

console.log(getFibbonacci(7))

#### [What are the steps to check if a number is a palindrome?](#what-are-the-steps-to-check-if-a-number-is-a-palindrome)
To check if a number is a palindrome:
1. Convert the number to a string.
2. Reverse the string.
3. Compare the original string with the reversed string. If they are the same, it's a palindrome.

---

#### [What are the steps to remove duplicates from an array?](#what-are-the-steps-to-remove-duplicates-from-an-array)
To remove duplicates from an array:
1. Convert the array to a `Set` to eliminate duplicates.
2. Convert the `Set` back to an array if needed.
   Example:
   ```js
   let arr = [1, 2, 2, 3, 4];
   arr = [...new Set(arr)];
   ```

---

#### [How to find the longest word in a string?](#how-to-find-the-longest-word-in-a-string)
To find the longest word in a string:
1. Split the string into an array of words.
2. Loop through the array and compare word lengths.
3. Keep track of the longest word.
   Example:
   ```js
   let str = "Find the longest word here";
   let words = str.split(" ");
   let longestWord = words.reduce((a, b) => a.length > b.length ? a : b);
   ```

---

#### [How to check if two strings are anagrams of each other?](#how-to-check-if-two-strings-are-anagrams-of-each-other)
To check if two strings are anagrams:
1. Sort both strings.
2. Compare the sorted strings. If they are the same, the strings are anagrams.
   Example:
   ```js
   let str1 = "listen";
   let str2 = "silent";
   let areAnagrams = str1.split("").sort().join("") === str2.split("").sort().join("");
   ```

---

#### [How to reverse a string without using built-in methods?](#how-to-reverse-a-string-without-using-built-in-methods)
To reverse a string without using built-in methods:
1. Loop through the string from the last character to the first.
2. Concatenate each character to a new string.
   Example:
   ```js
   let str = "hello";
   let reversed = "";
   for (let i = str.length - 1; i >= 0; i--) {
     reversed += str[i];
   }
   ```

---

#### [How to find the factorial of a number using recursion?](#how-to-find-the-factorial-of-a-number-using-recursion)
To find the factorial of a number using recursion:
1. Define a recursive function that multiplies the current number with the factorial of the previous number.
2. Base case: return 1 when the number is 0.
   Example:
   ```js
   function factorial(n) {
     if (n === 0) return 1;
     return n * factorial(n - 1);
   }
   ```

---

#### [How to find the first non-repeated character in a string?](#how-to-find-the-first-non-repeated-character-in-a-string)
To find the first non-repeated character:
1. Loop through the string and count the occurrences of each character.
2. Return the first character that occurs only once.
   Example:
   ```js
   let str = "swiss";
   let charCount = {};
   for (let char of str) {
     charCount[char] = (charCount[char] || 0) + 1;
   }
   let firstNonRepeated = Object.keys(charCount).find(char => charCount[char] === 1);
   ```

---

#### [What are the steps to check if a number is prime?](#what-are-the-steps-to-check-if-a-number-is-prime)
To check if a number is prime:
1. Loop from 2 to the square root of the number.
2. If the number is divisible by any number in this range, it's not prime.
3. If no divisor is found, the number is prime.
   Example:
   ```js
   function isPrime(num) {
     for (let i = 2; i <= Math.sqrt(num); i++) {
       if (num % i === 0) return false;
     }
     return num > 1;
   }
   ```

---

#### [How to implement a basic stack data structure in JavaScript?](#how-to-implement-a-basic-stack-data-structure-in-javascript)
To implement a basic stack:
1. Create a class `Stack` with methods like `push`, `pop`, and `peek`.
2. Use an array to store stack elements.
   Example:
   ```js
   class Stack {
     constructor() {
       this.stack = [];
     }
     push(element) {
       this.stack.push(element);
     }
     pop() {
       return this.stack.pop();
     }
     peek() {
       return this.stack[this.stack.length - 1];
     }
   }
   ```

---

#### [How to find the maximum product of two integers in an array?](#how-to-find-the-maximum-product-of-two-integers-in-an-array)
To find the maximum product of two integers:
1. Sort the array.
2. The maximum product will be either the product of the two largest or two smallest numbers.
   Example:
   ```js
   let arr = [-10, -10, 5, 2];
   arr.sort((a, b) => a - b);
   let maxProduct = Math.max(arr[0] * arr[1], arr[arr.length - 1] * arr[arr.length - 2]);
   ```

---


#### [What is the difference between `var`, `let`, and `const` in JavaScript?](#what-is-the-difference-between-var-let-and-const-in-javascript)
- `var` is function-scoped and can be re-assigned.
- `let` is block-scoped and can be re-assigned.
- `const` is block-scoped and cannot be re-assigned after initialization.

---

#### [What is the difference between `==` and `===` in JavaScript?](#what-is-the-difference-between-and-in-javascript)
- `==` performs type coercion, meaning it converts operands to a common type before comparison.
- `===` checks both the value and the type without type coercion.

---

#### [How does JavaScript interact with the DOM?](#how-does-javascript-interact-with-the-dom)
JavaScript interacts with the DOM by using methods like `getElementById`, `querySelector`, and `addEventListener` to manipulate HTML elements, styles, and handle events.

---

#### [What is hoisting in JavaScript, and how does it work?](#what-is-hoisting-in-javascript-and-how-does-it-work)
Hoisting is the behavior in JavaScript where variable and function declarations are moved to the top of their scope before code execution. However, only the declarations are hoisted, not the initializations.

---

#### [What is `MutationObserver`, and what are its use cases?](#what-is-mutationobserver-and-what-are-its-use-cases)
`MutationObserver` is an API used to detect changes in the DOM. It’s useful for reacting to changes such as element creation, deletion, or attribute modifications.

---

#### [What is JavaScript prototypes, and how do they function?](#what-are-javascript-prototypes-and-how-do-they-function)
In JavaScript, every object has a prototype. The prototype is used for inheritance, and objects can access properties and methods defined on their prototype.

---

#### [What are higher-order functions, and how do they work?](#what-are-higher-order-functions-and-how-do-they-work)
Higher-order functions are functions that can take other functions as arguments or return them. They are a key feature of functional programming.

---

#### [What is functional programming, and how is it applied in JavaScript?](#what-is-functional-programming-and-how-is-it-applied-in-javascript)
Functional programming in JavaScript emphasizes immutability, pure functions, and higher-order functions. It avoids side effects and promotes a declarative coding style.

---

#### [How can you optimize DOM manipulations for better performance?](#how-can-you-optimize-dom-manipulations-for-better-performance)
To optimize DOM manipulations:
1. Minimize reflows and repaints by batch-processing DOM changes.
2. Use `DocumentFragment` for off-DOM tree manipulations.
3. Avoid excessive use of `innerHTML`.

---

#### [What are closures in JavaScript, and how are they used?](#what-are-closures-in-javascript-and-how-are-they-used)
Closures are functions that have access to their lexical scope, even when they are executed outside of that scope. They are commonly used for data encapsulation and function factories.

---

#### [How does JavaScript handle asynchronous operations?](#how-does-javascript-handle-asynchronous-operations)
JavaScript handles asynchronous operations using callbacks, promises, and async/await. These mechanisms allow non-blocking code execution while waiting for external resources or operations.

---
