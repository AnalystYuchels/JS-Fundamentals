# JavaScript Programming


**1. Why JavaScript programming is outstanding:**

It adds interactivity to websites, runs in the browser, supports backend (Node.js), and has a vast community.


**2. How to run a JavaScript script:**

Use `node filename.js` in the terminal (with Node.js installed).


**3. How to create variables and constants:**

* `let x = 5;` (variable)
* `const y = 10;` (constant)


**4. Differences between `var`, `const`, and `let`:**

* `var`: function-scoped, hoisted
* `let`: block-scoped, not hoisted
* `const`: block-scoped, must be initialized, cannot be reassigned


**5. All data types in JavaScript:**

* Primitive: `string`, `number`, `boolean`, `undefined`, `null`, `bigint`, `symbol`
* Object types: `Object`, `Array`, `Function`, etc.


**6. How to use `if`, `if...else` statements:**

```js
if (x > 0) { ... }  
else { ... }
```


**7. How to use comments:**

* Single-line: `// comment`
* Multi-line: `/* comment */`


**8. How to assign values to variables:**

```js
let name = "John";  
const age = 25;
```


**9. How to use `while` and `for` loops:**

```js
while (i < 5) { i++; }  
for (let i = 0; i < 5; i++) { ... }
```


**10. How to use `break` and `continue`:**

```js
if (i === 3) break;  
if (i === 2) continue;
```


**11. What is a function and how to use it?**

They are reusable blocks of code;

```js
function greet() { console.log("Hi"); }  
greet();
```


**12. What does a function that does not use any return statement return?**

`undefined`


**13. Scope of variables:**

* `var`: function-scoped
* `let`/`const`: block-scoped


**14. Arithmetic operators and how to use them:**

`+`, `-`, `*`, `/`, `%`, `**` (exponentiation)

```js
let sum = a + b;
```


**15. How to manipulate a dictionary (object):**

```js
let obj = { name: "Sam" };  
obj.age = 30;  
console.log(obj["name"]);
```


**16. How to import a file:**

(in Node.js with ES6 modules)

```js
import { func } from './file.js';
```

Or with CommonJS:

```js
const func = require('./file');
```
