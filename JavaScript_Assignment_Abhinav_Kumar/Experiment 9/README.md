# Experiment 9: DOM, Validation, Storage and Quiz

## Aim

To change a page with a click, to check form values in code, to save text in local storage, and to build a small quiz.

## Software / Tools Required

Web browser (Google Chrome / Microsoft Edge / Firefox) with the developer console (F12); Node.js; a code editor such as VS Code.

## Theory

The DOM (Document Object Model) represents an HTML page as objects that JavaScript can read and change. document.getElementById() finds an element, textContent changes its text, and addEventListener() runs a function when an event such as a click happens. Validation checks that a value is acceptable before it is used. localStorage saves text in the browser using setItem() and reads it back with getItem(), and the text stays after the page is closed.

## Tasks

| Task | One-line description | Files | How to run |
|---:|---|---|---|
| 1 | Change a page heading when the user clicks a button. | task1.html, task1.js, screenshot_task1.png | Open task1.html and press F12 |
| 2 | Validate a name and report an error when it is blank. | task2.html, task2.js, screenshot_task2.png | Open task2.html and press F12 |
| 3 | Load and save a note with localStorage. | task3.html, task3.js, screenshot_task3.png | Open task3.html and press F12 |
| 4 | Check a multiple-choice answer and show feedback on the page. | task4.html, task4.js, screenshot_task4.png | Open task4.html and press F12 |

## Result

JavaScript programs and pages were written to change text on a click, to validate a form value, to save and show text using localStorage and to check a quiz answer.

## Viva-Voce Questions

1. What is the DOM?
2. What is the use of addEventListener()?
3. What is the difference between setItem() and getItem() in localStorage?
4. Why is form validation needed?
5. How does querySelector find the selected radio button?

## Folder Tree

~~~text
Experiment 9/
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
