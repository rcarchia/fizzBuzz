FizzBuzz Game - README

Overview

This simple HTML and JavaScript project implements the classic programming challenge "FizzBuzz." It's designed to print numbers in sequence, replacing multiples of 3 with "fizz," multiples of 5 with "buzz," and multiples of both 3 and 5 with "fizzBuzz."

How It Works

User Interaction

Upon loading the HTML page, a browser prompt will request the user to input a number.

This input determines how far the FizzBuzz sequence will go.

Core Logic

The main logic is defined in JavaScript:

loop(answer) iterates through each number from 1 to the user's chosen number.

isFizzBuzz(count) evaluates each number:

Returns "fizzBuzz" if divisible by both 3 and 5.

Returns "fizz" if divisible by 3.

Returns "buzz" if divisible by 5.

Otherwise, returns the number itself.

Output

Results are printed in the browser's console, clearly indicating the selection and each step of the FizzBuzz sequence.

Setup

Simply save the code as an .html file and open it in any modern browser.

Example

Technologies Used

HTML5

JavaScript

Customization

Feel free to extend the project by:

Adding styling with CSS.

Displaying results directly on the webpage instead of the console.

Implementing additional game rules or visual feedback.
