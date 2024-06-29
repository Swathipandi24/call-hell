#### Callback Hell Countdown

This project demonstrates a countdown timer from 10 to 1 followed by displaying "Happy Independence Day" using callback functions in JavaScript.

### Files Included

- **index.html**: Contains the basic HTML structure to display the countdown.
- **script.js**: JavaScript file where the countdown logic is implemented using callback functions.
- **css**: CSS file style to display the countdown

### Explanation

- **HTML Structure**: 
  - Provides a basic structure with a `<div>` element (`#countdown`) where the countdown numbers and final message will be displayed.

- ### CSS:

 - Styles the body to use flexbox for centered alignment (display: flex; justify-content: center; align-items: center;).
.container centers its contents (text-align: center;).
.countdown styles the countdown numbers (font-size, margin-bottom).


- **JavaScript (`script.js`)**:
  - Waits for the DOM to be fully loaded using `document.addEventListener("DOMContentLoaded", ...)`.
  - Defines a `displayNumber` function that takes a number and a callback function. It updates the inner HTML of `#countdown` with the given number and schedules the callback to execute after 1 second using `setTimeout`.
  - Implements the countdown using nested callback functions (`callback hell`) to sequentially display numbers from 10 to 1.
  - After displaying "1", uses another `setTimeout` to display "Happy Independence Day" after a delay.

### Constraints

- The implementation strictly adheres to the following constraints:
  - No named functions.
  - No `setInterval` function.
  - No recursion.
  - No IIFEs (Immediately Invoked Function Expressions).
  - No loops.

### Usage

- Open `index.html` in a web browser to see the countdown from 10 to 1 followed by the message "Happy Independence Day".

### Notes

- Callback hell is used to demonstrate the sequential execution of asynchronous operations without using traditional control structures like loops or recursion.

