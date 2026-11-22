# JavaScript Programming Lab (BCS354) — Practical Record

**Course:** B.Tech CSE, 3rd Semester, Invertis University, Bareilly  
**Course code:** BCS354  
**Submitted to:** Mr. Aman Singh  
**Submitted by:** Abhinav Kumar, Roll No. 2510303017, ID BCS2025479, Section C

This practical record contains 15 experiments covering JavaScript from basic scripts and const/let through functions, arrays, JSON, classes and inheritance, the DOM, closures, higher-order functions, timers, and promises with async/await. It includes the original task code, output screenshots, procedures, expected results, and viva-voce questions.

## Experiments

| Experiment | Title | Tasks | Date |
|---:|---|---:|---|
| 1 | Your First JavaScript Script | 3 | 26/10/2026 |
| 2 | Operators, Type Conversion and a Calculator | 3 | 26/10/2026 |
| 3 | Conditions and Loops | 3 | 26/10/2026 |
| 4 | Writing Functions | 3 | 28/10/2026 |
| 5 | Arrays, Array Methods and Nested Arrays | 4 | 28/10/2026 |
| 6 | JSON Text | 3 | 28/10/2026 |
| 7 | Constructor Functions and Classes | 3 | 30/10/2026 |
| 8 | Inheritance, Methods and Composition | 3 | 30/10/2026 |
| 9 | DOM, Validation, Storage and Quiz | 4 | 01/11/2026 |
| 10 | Objects and Destructuring | 3 | 01/11/2026 |
| 11 | Scope and Closures | 3 | 01/11/2026 |
| 12 | Callbacks and Higher-Order Functions | 3 | 02/11/2026 |
| 13 | Reduce, Some, Every and Map | 3 | 02/11/2026 |
| 14 | Timers and Intervals | 3 | 04/11/2026 |
| 15 | Promises and async/await with Local Data | 4 | 04/11/2026 |

## How to Run

Open taskN.html in Chrome, Edge, or Firefox, then press F12 and check the Console. For standalone JavaScript tasks, run node taskN.js from the task folder in a terminal. Use the browser method for tasks that access the DOM or localStorage.

## Folder Structure

~~~text
JavaScript_Assignment_Abhinav_Kumar/
├── README.md
├── Experiment 1/
│   ├── README.md
│   ├── Task 1/
│   │   ├── README.md
│   │   ├── task1.html
│   │   ├── task1.js
│   │   └── screenshot_task1.png
│   ├── Task 2/
│   │   ├── README.md
│   │   ├── task2.html
│   │   ├── task2.js
│   │   └── screenshot_task2.png
│   └── Task 3/
│       ├── README.md
│       ├── task3.html
│       ├── task3.js
│       └── screenshot_task3.png
├── Experiment 2/
│   ├── README.md
│   ├── Task 1/
│   │   ├── README.md
│   │   ├── task1.html
│   │   ├── task1.js
│   │   └── screenshot_task1.png
│   ├── Task 2/
│   │   ├── README.md
│   │   ├── task2.html
│   │   ├── task2.js
│   │   └── screenshot_task2.png
│   └── Task 3/
│       ├── README.md
│       ├── task3.html
│       ├── task3.js
│       └── screenshot_task3.png
├── Experiment 3/
│   ├── README.md
│   ├── Task 1/
│   │   ├── README.md
│   │   ├── task1.html
│   │   ├── task1.js
│   │   └── screenshot_task1.png
│   ├── Task 2/
│   │   ├── README.md
│   │   ├── task2.html
│   │   ├── task2.js
│   │   └── screenshot_task2.png
│   └── Task 3/
│       ├── README.md
│       ├── task3.html
│       ├── task3.js
│       └── screenshot_task3.png
├── Experiment 4/
│   ├── README.md
│   ├── Task 1/
│   │   ├── README.md
│   │   ├── task1.html
│   │   ├── task1.js
│   │   └── screenshot_task1.png
│   ├── Task 2/
│   │   ├── README.md
│   │   ├── task2.html
│   │   ├── task2.js
│   │   └── screenshot_task2.png
│   └── Task 3/
│       ├── README.md
│       ├── task3.html
│       ├── task3.js
│       └── screenshot_task3.png
├── Experiment 5/
│   ├── README.md
│   ├── Task 1/
│   │   ├── README.md
│   │   ├── task1.html
│   │   ├── task1.js
│   │   └── screenshot_task1.png
│   ├── Task 2/
│   │   ├── README.md
│   │   ├── task2.html
│   │   ├── task2.js
│   │   └── screenshot_task2.png
│   ├── Task 3/
│   │   ├── README.md
│   │   ├── task3.html
│   │   ├── task3.js
│   │   └── screenshot_task3.png
│   └── Task 4/
│       ├── README.md
│       ├── task4.html
│       ├── task4.js
│       └── screenshot_task4.png
├── Experiment 6/
│   ├── README.md
│   ├── Task 1/
│   │   ├── README.md
│   │   ├── task1.html
│   │   ├── task1.js
│   │   └── screenshot_task1.png
│   ├── Task 2/
│   │   ├── README.md
│   │   ├── task2.html
│   │   ├── task2.js
│   │   └── screenshot_task2.png
│   └── Task 3/
│       ├── README.md
│       ├── task3.html
│       ├── task3.js
│       └── screenshot_task3.png
├── Experiment 7/
│   ├── README.md
│   ├── Task 1/
│   │   ├── README.md
│   │   ├── task1.html
│   │   ├── task1.js
│   │   └── screenshot_task1.png
│   ├── Task 2/
│   │   ├── README.md
│   │   ├── task2.html
│   │   ├── task2.js
│   │   └── screenshot_task2.png
│   └── Task 3/
│       ├── README.md
│       ├── task3.html
│       ├── task3.js
│       └── screenshot_task3.png
├── Experiment 8/
│   ├── README.md
│   ├── Task 1/
│   │   ├── README.md
│   │   ├── task1.html
│   │   ├── task1.js
│   │   └── screenshot_task1.png
│   ├── Task 2/
│   │   ├── README.md
│   │   ├── task2.html
│   │   ├── task2.js
│   │   └── screenshot_task2.png
│   └── Task 3/
│       ├── README.md
│       ├── task3.html
│       ├── task3.js
│       └── screenshot_task3.png
├── Experiment 9/
│   ├── README.md
│   ├── Task 1/
│   │   ├── README.md
│   │   ├── task1.html
│   │   ├── task1.js
│   │   └── screenshot_task1.png
│   ├── Task 2/
│   │   ├── README.md
│   │   ├── task2.html
│   │   ├── task2.js
│   │   └── screenshot_task2.png
│   ├── Task 3/
│   │   ├── README.md
│   │   ├── task3.html
│   │   ├── task3.js
│   │   └── screenshot_task3.png
│   └── Task 4/
│       ├── README.md
│       ├── task4.html
│       ├── task4.js
│       └── screenshot_task4.png
├── Experiment 10/
│   ├── README.md
│   ├── Task 1/
│   │   ├── README.md
│   │   ├── task1.html
│   │   ├── task1.js
│   │   └── screenshot_task1.png
│   ├── Task 2/
│   │   ├── README.md
│   │   ├── task2.html
│   │   ├── task2.js
│   │   └── screenshot_task2.png
│   └── Task 3/
│       ├── README.md
│       ├── task3.html
│       ├── task3.js
│       └── screenshot_task3.png
├── Experiment 11/
│   ├── README.md
│   ├── Task 1/
│   │   ├── README.md
│   │   ├── task1.html
│   │   ├── task1.js
│   │   └── screenshot_task1.png
│   ├── Task 2/
│   │   ├── README.md
│   │   ├── task2.html
│   │   ├── task2.js
│   │   └── screenshot_task2.png
│   └── Task 3/
│       ├── README.md
│       ├── task3.html
│       ├── task3.js
│       └── screenshot_task3.png
├── Experiment 12/
│   ├── README.md
│   ├── Task 1/
│   │   ├── README.md
│   │   ├── task1.html
│   │   ├── task1.js
│   │   └── screenshot_task1.png
│   ├── Task 2/
│   │   ├── README.md
│   │   ├── task2.html
│   │   ├── task2.js
│   │   └── screenshot_task2.png
│   └── Task 3/
│       ├── README.md
│       ├── task3.html
│       ├── task3.js
│       └── screenshot_task3.png
├── Experiment 13/
│   ├── README.md
│   ├── Task 1/
│   │   ├── README.md
│   │   ├── task1.html
│   │   ├── task1.js
│   │   └── screenshot_task1.png
│   ├── Task 2/
│   │   ├── README.md
│   │   ├── task2.html
│   │   ├── task2.js
│   │   └── screenshot_task2.png
│   └── Task 3/
│       ├── README.md
│       ├── task3.html
│       ├── task3.js
│       └── screenshot_task3.png
├── Experiment 14/
│   ├── README.md
│   ├── Task 1/
│   │   ├── README.md
│   │   ├── task1.html
│   │   ├── task1.js
│   │   └── screenshot_task1.png
│   ├── Task 2/
│   │   ├── README.md
│   │   ├── task2.html
│   │   ├── task2.js
│   │   └── screenshot_task2.png
│   └── Task 3/
│       ├── README.md
│       ├── task3.html
│       ├── task3.js
│       └── screenshot_task3.png
└── Experiment 15/
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

Every experiment folder and every task folder has its own README.md with the experiment or task details.
