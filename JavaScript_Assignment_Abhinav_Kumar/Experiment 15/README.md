# Experiment 15: Promises and async/await with Local Data

## Aim

To create a Promise that resolves or rejects, to use async/await with try and catch, and to load local data as a Promise.

## Software / Tools Required

Web browser (Google Chrome / Microsoft Edge / Firefox) with the developer console (F12); Node.js; a code editor such as VS Code.

## Theory

A Promise represents a value that will be available later. It is resolved when the work succeeds and rejected when it fails. then() handles the resolved value and catch() handles the error. An async function always returns a Promise, and the await keyword waits for a Promise to finish inside it; Errors from an awaited Promise are handled with try and catch.

## Tasks

| Task | One-line description | Files | How to run |
|---:|---|---|---|
| 1 | Resolve a Promise for valid marks and print the resolved value. | task1.html, task1.js, screenshot_task1.png | Open task1.html and press F12 |
| 2 | Reject a Promise for an out-of-range mark and print the error message. | task2.html, task2.js, screenshot_task2.png | Open task2.html and press F12 |
| 3 | Use async/await and try/catch for valid and invalid marks. | task3.html, task3.js, screenshot_task3.png | Open task3.html and press F12 |
| 4 | Load a local user array asynchronously and print each user's name. | task4.html, task4.js, screenshot_task4.png | Open task4.html and press F12 |

## Result

JavaScript programs were written to create Promises that resolve or reject, to use async/await with try and catch, and to load local data as a Promise.

## Viva-Voce Questions

1. What is a Promise?
2. What is the difference between resolve and reject?
3. What does the await keyword do?
4. What is the use of try and catch with async/await?
5. What does an async function return?

## Folder Tree

~~~text
Experiment 15/
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
├── Task 3/
│   ├── README.md
│   ├── task3.html
│   ├── task3.js
│   └── screenshot_task3.png
└── Task 4/
    ├── README.md
    ├── task4.html
    ├── task4.js
    └── screenshot_task4.png
~~~
