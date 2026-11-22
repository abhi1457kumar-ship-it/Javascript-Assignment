# Experiment 11: Scope and Closures

## Aim

To explain block scope and global scope, and to use a function that returns a function that keeps a value between calls.

## Software / Tools Required

Web browser (Google Chrome / Microsoft Edge / Firefox) with the developer console (F12); Node.js; a code editor such as VS Code.

## Theory

Scope decides where a variable can be used. A variable declared with let inside a block { } exists only in that block, and a variable declared outside all functions is global and can be used inside functions. A closure is an inner function that remembers the variables of the outer function even after the outer function has finished, so it can keep a value (such as a counter) between calls.

## Tasks

| Task | One-line description | Files | How to run |
|---:|---|---|---|
| 1 | Demonstrate how a block-scoped variable differs from an outer variable. | task1.html, task1.js, screenshot_task1.png | Open task1.html and press F12 |
| 2 | Create a closure-based counter and print its value after two calls. | task2.html, task2.js, screenshot_task2.png | Open task2.html and press F12 |
| 3 | Use a global variable inside a function to print a welcome message. | task3.html, task3.js, screenshot_task3.png | Open task3.html and press F12 |

## Result

JavaScript programs were written to show block scope and global scope, and to keep a value between calls using a closure.

## Viva-Voce Questions

1. What is scope in JavaScript?
2. What is the difference between block scope and global scope?
3. What is a closure?
4. Why does the counter keep its value between calls?
5. Can a function use a global variable? Give an example.

## Folder Tree

~~~text
Experiment 11/
├── README.md
├── Task 1/
│   ├── README.md
│   ├── task1.html
│   ├── task1.js
│   └── screenshot_task1.png
├── Task 2/
│   ├── README.md
│   ├── task2.html
│   ├── task2.js
│   └── screenshot_task2.png
└── Task 3/
    ├── README.md
    ├── task3.html
    ├── task3.js
    └── screenshot_task3.png
~~~
