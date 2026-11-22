# Experiment 14: Timers and Intervals

## Aim

To run code after a delay with setTimeout, to cancel a timer, and to repeat code with setInterval.

## Software / Tools Required

Web browser (Google Chrome / Microsoft Edge / Firefox) with the developer console (F12); Node.js; a code editor such as VS Code.

## Theory

setTimeout() runs a function once after a delay given in milliseconds, and clearTimeout() cancels it using the id that setTimeout() returns. setInterval() runs a function again and again after every interval, and clearInterval() stops it. JavaScript finishes the current code first and runs timer callbacks afterwards, even when the delay is 0.

## Tasks

| Task | One-line description | Files | How to run |
|---:|---|---|---|
| 1 | Compare synchronous output with a zero-delay setTimeout callback. | task1.html, task1.js, screenshot_task1.png | Open task1.html and press F12 |
| 2 | Cancel a setTimeout callback before it prints. | task2.html, task2.js, screenshot_task2.png | Open task2.html and press F12 |
| 3 | Use setInterval to print three ticks, then clear the interval. | task3.html, task3.js, screenshot_task3.png | Open task3.html and press F12 |

## Result

JavaScript programs were written to run code after a delay with setTimeout, to cancel a timer with clearTimeout and to repeat code with setInterval and stop it with clearInterval.

## Viva-Voce Questions

1. What is the use of setTimeout()?
2. How do you cancel a timer?
3. What is the difference between setTimeout() and setInterval()?
4. Why does a timer with delay 0 run after the other lines of code?
5. How is setInterval() stopped?

## Folder Tree

~~~text
Experiment 14/
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
