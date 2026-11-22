# Experiment 15 — Task 3

## What it does

Use async/await and try/catch for valid and invalid marks.

## Steps

1. Define checkMarks(marks) in the same way.
2. Define the async function run() with a try block that prints await checkMarks(65) and then awaits checkMarks(-5).
3. In the catch block, print "Caught:" with error.message.
4. Call run().

## Files

- README.md
- task3.html
- task3.js
- screenshot_task3.png

## How to run

Open task3.html in Chrome, Edge, or Firefox and press F12 to check the Console.

## Expected output

The console prints 65, then Caught: Marks out of range.
