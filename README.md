- 👋 Hi, I’m @oubaid666
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

## Developing Functions in JavaScript
JavaScript functions are reusable blocks of code that you can define and invoke to perform tasks when developing applications. Below are common ways to create and use them.

### 1) Function declaration
```js
function greet(name) {
  return `Hello, ${name}!`;
}

greet("Sam"); // "Hello, Sam!"
```

### 2) Function expression
```js
const add = function (a, b) {
  return a + b;
};

add(2, 3); // 5
```

### 3) Arrow function
```js
const multiply = (a, b) => a * b;

multiply(4, 5); // 20
```

### 4) Default parameters
```js
function increment(value, step = 1) {
  return value + step;
}

increment(10); // 11
```

### 5) Rest parameters
```js
function sum(...numbers) {
  return numbers.reduce((total, n) => total + n, 0);
}

sum(1, 2, 3); // 6
```

### 6) Higher-order functions
```js
const applyTwice = (fn, value) => fn(fn(value));
const double = (x) => x * 2;

applyTwice(double, 3); // 12
```

### 7) Immediately-invoked function expression (IIFE)
```js
(function () {
  const secret = "hidden";
  console.log(secret);
})();
```

<!---
oubaid666/oubaid666 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
