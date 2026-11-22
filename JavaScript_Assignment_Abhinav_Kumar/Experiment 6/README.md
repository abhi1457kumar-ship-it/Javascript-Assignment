# Experiment 6: JSON Text

## Aim

To convert an object to JSON text, to convert JSON text back to an object, and to catch invalid JSON.

## Software / Tools Required

Web browser (Google Chrome / Microsoft Edge / Firefox) with the developer console (F12); Node.js; a code editor such as VS Code.

## Theory

JSON (JavaScript Object Notation) is a text format used to store and exchange data. JSON.stringify() converts a JavaScript object into JSON text, and JSON.parse() converts JSON text back into an object. In valid JSON, the keys and text values must be written in double quotes. When JSON.parse() gets invalid text it throws an error, which can be handled with try and catch.

## Tasks

| Task | One-line description | Files | How to run |
|---:|---|---|---|
| 1 | Convert a student object to JSON text and print it. | task1.html, task1.js, screenshot_task1.png | Open task1.html and press F12 |
| 2 | Parse JSON text into an object and print its city. | task2.html, task2.js, screenshot_task2.png | Open task2.html and press F12 |
| 3 | Catch a JSON parsing error and print an invalid-data message. | task3.html, task3.js, screenshot_task3.png | Open task3.html and press F12 |

## Result

JavaScript programs were written to convert an object to JSON text, to convert JSON text to an object and to catch invalid JSON using try and catch.

## Viva-Voce Questions

1. What is JSON?
2. What is the difference between JSON.stringify() and JSON.parse()?
3. Why is {name: Rohan} not valid JSON?
4. What is the use of try and catch?
5. How is JSON different from a JavaScript object?

## Folder Tree

~~~text
Experiment 6/
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
