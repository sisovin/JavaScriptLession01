# Lesson 01: Get Started

## How to start-up JavaScript

This script is a step-by-step guide for beginners on how to use the Chrome browser's console to experiment with JavaScript. It covers:

1. **Opening the Chrome Developer Tools**: Instructions on how to open a blank page in Chrome and access the developer tools using keyboard shortcuts or the context menu.
2. **Using the Console**: Demonstrates how to enter JavaScript code in the console, including comments, and explains the output for each command.
3. **Exploring Data Types**: Introduces basic JavaScript data types (string, number, boolean, undefined) by typing values into the console and using the `typeof` operator to check their types.
4. **Variables and Assignment**: Shows how to declare variables with `let`, assign values to them, and change their values. It also demonstrates that variables in JavaScript are dynamically typed, meaning their type can change based on the value assigned to them.
5. **Basic Arithmetic Operations**: Provides examples of performing arithmetic operations (addition, subtraction, multiplication, division) directly in the console and storing results in variables.
6. **String Concatenation**: Illustrates how to concatenate strings and numbers, and how adding a number to a string converts the number into a string, resulting in a concatenated string.
7. **Boolean Logic and Comparisons**: Introduces boolean values, comparison operators (`===`, `!==`, `>=`, `<=`), and shows how to compare variables and store the result of a comparison in a boolean variable.

Each step is designed to familiarize the user with interacting with JavaScript through the Chrome console, providing a hands-on way to learn basic programming concepts.

1. Go to Chrome Browser, then type: about:blank (Ctrl + Shift + I) or at the address bar, type: https://supersimple.dev/js-basics/
2. Right click, choose Inspect, the Chrome layout popup with the different pallette like Web page, Console, Element, source with style, Computed, EventListener etc.
3. From the Console, type like: >// this is a comment press Enter the output is undefined
4. > // data types, press Enter the output is undefined
5. > type my name: 'Sisovin' or "Sisovin" press Enter the output is Sisovin
6. > typeof "Sisovin" press Enter, the output is 'string'
7. > typeof 52 press Enter, the output is 'number
8. > typeof true press Enter the output is 'boolean'
9. > type Ctrl + L, or click on Clear console to clear the screen
10. > let myVariable; press Enter, the output is undefined
11. > typeof myVariable; press Enter, the output is 'undefined'
12. > myVariable = "Sisovin"; press Enter the output is "Sisovin"
13. > myVariable = 52; press Enter the output is 52
14. > typeof myVariable; press Enter the output is 'number'
15. This time we go with math in the console >52 + 2; press Enter the output is 54
16. > typeof 52 + 2; press Enter the output is 'number2'
17. > 52 - 2; press Enter the output is 50
18. > let myNumber = 52; press Enter the output is undefined
19. > myNumber + 2; press Enter the output is 54
20. > myNumber - 2; press Enter the output is 50
21. > myNumber \* 2; press Enter the output is 104
22. > myNumber / 2; press Enter the output is 26
23. > myVariable = 52 \* 2; press Enter the output is 104
24. > let myEquation = 52 / 2; press Enter the output is undefined
25. > myEquation \* 2; press Enter the output is 52
26. > myVariable; press Enter the output is 104
27. > myVariable = "Chieng Sisovin"; press Enter the output is 'Chieng Sisovin'
28. > myEquation + myVariable; press Enter the output is '26Chieng Sisovin'
29. > myNumber + myVariable; press Enter the output is '52Chieng Sisovin'
30. > let myBlankSpace = " "; press Enter the output is undefined
31. > myNumber + myBlankSpace + myVariable; press Enter the output is '52 Chieng Sisovin'
32. > let myCombo = myNumber + myVariable; press Enter the output is undefined
33. > typeof myCombo; press Enter the output is 'string'
34. > typeof Boolean; press Enter the output is 'function
35. > myVariable === myNumber; press Enter the output is 'false'
36. > myNumber; press Enter the output is 52
37. > myNumber === 52; press Enter the output is true
38. > let myBool = myNumber === 52; press Enter the output is undefined
39. > myBool; press Enter the output is true
40. > myNumber !== 52; press Enter the output is false
41. > myNumber >= 52; press Enter the output is true
42. > > myNumber <= 52; press Enter the output is true

## Review

Please generate the practical review as below:

### [] How to open Chrome Dev Tools

### [] How to put Chrome Dev Tools into dark mode

### [] How to use the Console tab in Chrome Dev Tools to enter JavaScript statements

### [] Four data types: 1) String 2) Number 3) Boolean 4) Undefined

### [] How to check data types with the keyword typeof

### [] How to create variable with keyword let

### [] How to name variable with camelCase

### [] How to use basic mathematical operators to perform mathematic operations, to concatenate string data, and to compare data types

### [] When we compared data, we received Boolean data in return. The example in this lesson have used JavaScript syntax

## Popup the screen with JavaScript Function

43. > alert("Hello World!"); press Enter the output is popped up 'This page says Hello World!'

### Practical Review

#### How to open Chrome Dev Tools

- **Action**: Press `Ctrl + Shift + I` or `F12` on Windows/Linux, `Cmd + Option + I` on macOS.
- **Observation**: Chrome Developer Tools window opens either docked or in a separate window, depending on your settings.

#### How to put Chrome Dev Tools into dark mode

- **Action**: Go to Dev Tools settings (click on the three dots in the top right corner, then select "Settings"), under the "Appearance" section, choose the "Theme" dropdown, and select "Dark".
- **Observation**: The Developer Tools interface switches to dark mode, reducing eye strain in low-light conditions.

#### How to use the Console tab in Chrome Dev Tools to enter JavaScript statements

- **Action**: Click on the "Console" tab within Dev Tools and type a JavaScript statement, such as `console.log('Hello, world!');`, then press Enter.
- **Observation**: The output of the JavaScript statement is displayed in the console.

#### Four data types: 1) String 2) Number 3) Boolean 4) Undefined

- **Action**: Type examples of each data type into the console, like `"Hello"` (String), `42` (Number), `true` (Boolean), and `undefined` (Undefined).
- **Observation**: Each data type represents different kinds of values you can work with in JavaScript.

#### How to check data types with the keyword typeof

- **Action**: Use the [`typeof`]
- **Observation**: The console returns the data type of the given value, helping you understand what kind of data you're dealing with.

#### How to create variable with keyword let

- **Action**: In the console, declare a variable using [`let`] e.g., `let myVar = 10;`.
- **Observation**: The variable `myVar` is created and can be used to store or manipulate data.

#### How to name variable with camelCase

- **Action**: When naming a variable, start with a lowercase letter and capitalize subsequent words, e.g., `let myVariableName;`.
- **Observation**: The variable is easily readable and follows JavaScript naming conventions.

#### How to use basic mathematical operators to perform mathematic operations, to concatenate string data, and to compare data types

- **Action**: Perform operations like `5 + 3`, concatenate strings like `"Hello " + "world!"`, and compare values with `5 === 5`.
- **Observation**: JavaScript performs the specified operations, returning results or boolean values indicating the outcome of comparisons.

#### When we compared data, we received Boolean data in return. The example in this lesson have used JavaScript syntax

- **Action**: Compare two values using comparison operators, e.g., `10 > 5`.
- **Observation**: The comparison returns a Boolean value (`true` or `false`), indicating the result of the comparison.

### Popup the screen with JavaScript Function

- **Action**: Use the `alert()` function to display a message, e.g., `alert('Hello, world!');`.
- **Observation**: A popup appears on the screen displaying the message "Hello, world!".

## To debug JavaScript code using breakpoints in Chrome Dev Tools, follow these steps:

1. **Open Chrome Dev Tools**: Press `Ctrl + Shift + I` (Windows/Linux) or `Cmd + Option + I` (macOS).
2. **Navigate to the Sources Tab**: Click on the "Sources" tab to view the files loaded by the current webpage.
3. **Find Your JavaScript File**: In the file explorer pane on the left, navigate through the folders to find the JavaScript file you want to debug. Click to open it in the editor pane.
4. **Set a Breakpoint**: Scroll through the code in the editor pane to find the line where you want to pause execution. Click on the line number to the left of the code to set a breakpoint. A blue or red icon will appear to indicate that the breakpoint is set.
5. **Trigger the Code**: Perform the actions in the browser that would normally trigger the execution of the code where you set the breakpoint. The execution will pause at the breakpoint.
6. **Inspect Variables and Scope**: While paused, you can hover over variables in the code to see their current values. The right-hand pane also shows the "Scope" section where you can inspect local, closure, and global variables.
7. **Control Execution**: Use the control buttons (Continue, Step Over, Step Into, Step Out, and Deactivate Breakpoints) in the top right of the "Sources" tab to control execution. For example, "Step Over" executes the next line of code, while "Step Into" dives into the functions called by the current line.
8. **Resume Execution**: Click the "Continue" button (or press F8) to resume execution until the next breakpoint is hit or the program completes.

Using breakpoints is a powerful way to understand how your JavaScript code executes, allowing you to inspect variables and control execution flow to diagnose and fix issues.

## To inspect and modify the DOM of a webpage using Chrome Dev Tools, follow these steps:

1. **Open Chrome Dev Tools**: Press `Ctrl + Shift + I` (Windows/Linux) or `Cmd + Option + I` (macOS).
2. **Navigate to the Elements Tab**: Click on the "Elements" tab. This tab shows the DOM tree of the webpage, allowing you to see the structure and content of the HTML document.
3. **Inspect an Element**:
   - **Action**: Move your mouse over the elements in the DOM tree to highlight them on the webpage. Alternatively, you can right-click on an element on the webpage and select "Inspect" to jump directly to its representation in the DOM tree.
   - **Observation**: The selected element is highlighted in the Dev Tools, and its corresponding area is highlighted on the webpage.
4. **Modify an Element**:
   - **Action**: Double-click on any part of the element in the Dev Tools (e.g., a tag name, attribute, or text content) to edit it. You can change the tag, add or modify attributes, and edit or add text content.
   - **Observation**: The changes you make are immediately reflected on the webpage. This is useful for testing and debugging layout issues, experimenting with different content, or understanding how changes to the HTML affect the page.
5. **Add a New Element**:
   - **Action**: Right-click on an element in the DOM tree and select "Edit as HTML" or use the context menu to insert new elements before or after the selected element. You can also use the "Add node" button (a `+` icon) in the toolbar at the bottom of the Elements panel to add a new element.
   - **Observation**: The new element appears in the DOM tree and is rendered on the webpage.
6. **Style Inspection and Modification**:
   - **Action**: With an element selected in the "Elements" tab, look at the "Styles" pane on the right side. Here, you can see the CSS styles applied to the selected element. You can toggle styles on and off, edit existing styles, or add new ones.
   - **Observation**: Changes to styles are immediately applied to the selected element on the webpage, allowing you to experiment with different styles and immediately see the results.

Using the "Elements" tab in Chrome Dev Tools provides a powerful interface for inspecting, understanding, and experimenting with the DOM and styles of a webpage in real-time.

44. > alert('Hello'); press Enter the output is popped up 'The supersimple.dev says Hello'
45. > alert("Good Job!"); press Enter the output is popped up 'The supersimple.dev says Good Job!'
46. About sample >2 + 2; press Enter the output is 4
47. > 10 - 3 press Enter the output is 7
48. > document.body.innerHTML = 'Hello'; press Enter the console output is 'Hello' then the Browser show Hello
49. Talking about the syntax error >alert'hello'); press Enter the output is Uncaught SyntaxError: Unexpected string
