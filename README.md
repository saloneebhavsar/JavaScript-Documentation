 <a align="center" href="https://github.com/saloneebhavsar/JavaScript-Documentation">
    <img src="logo.png" alt="Logo" width="80" height="80" >
 </a>
<h1 align="center">JavaScript-Documentation</h1>
<p align="center">
  JavaScript is used to program the behavior of web pages.
</p>


## Where to add the script tag?

You can place the <script> tags, containing your JavaScript, anywhere within your web page, but it is normally recommended that you should keep it within the <head> tags.
The best practice to is to keep the scripts in the external files as shown below:
  
### External JavaScript
```
<script src="myScript.js"></script>

```
## Code structure
### Statements
Statements are syntax constructs and commands that perform actions.
```
alert('Hello');
alert('World');
```
### Semicolons
Although Semicolons are optional in javascript but is is best practice to always put it between statements even if they are separated by newlines.

### Comments
Comments are used to explain the code or prevent the execution of certain code while testing. Also they are used to make the code more readable.
-- One-line comments 
```
// This comment occupies a line of its own
```
-- Multiline comments
```
/* An example with two messages.
This is a multiline comment.
*/
```
## Variables

Variables are containers for storing data values.
In order to create a variable in JavaScript one can use the following three keywords:
### let
Let is used to store a variable and is scope specific unlike var.
```
let message = 'Hello!';
```
### const
const – is like let, but the value of the variable can’t be changed.
```
const myId = '17BIT002';
```
### var
The var variables belong to the global scope when you define them outside a function.
```
var _firstName = "Salonee";
```
There are two limitations on variable names in JavaScript:
- The name must contain only letters, digits, or the symbols $ and _.
- The first character must not be a digit.

## Datatypes

### Number
Numbers can be written with or without decimals:
```
var x2 = 34;
```

### String
A string (or a text string) is a series of characters like "Salonee Bhavsar". Strings are written with quotes. You can use single or double quotes:
```
var carName1 = "Volvo XC60";
```
### Boolean
Booleans can only have two values: true or false.
```
let nameFieldChecked = true; // yes, name field is checked
let ageFieldChecked = false;
```
### Null
```
var myVar = null;
```
### Undefined
```
var car;    // Value is undefined, type is undefined
```
### Arrays
Arrays are written with square brackets.In it items are separated by commas.
```
var colors = ["White", "Black", "Pink"];
```

### Object
Objects are written with curly braces {}.Their properties are written as name:value pairs, separated by commas.
```
var person = {firstName:"John", lastName:"Doe", age:50, eyeColor:"blue"};
```
## Popup Boxes
### Alert Box
Alert box is useful for alerting your users to something important. When a JavaScript alert box is triggered, a small box will pop up with the text that you wasnt to display. When an alert box pops up, the user will have to click "OK" to proceed.
```
window.alert("sometext");
```
### Confirm Box
A confirm box is often used if you want the user to verify or accept something.When a confirm box pops up with a specified message, the user will have to click either "OK" or "Cancel" to proceed.If the user clicks "OK", the box returns true. If the user clicks "Cancel", the box returns false.
```
window.confirm("sometext");
```
### Prompt Box
A prompt box is often used if you want the user to input a value before entering a page. When a prompt box pops up, the user will have to click either "OK" or "Cancel" to proceed after entering an input value.If the user clicks "OK" the box returns the input value. If the user clicks "Cancel" the box returns null.

```
window.prompt("sometext","defaultText");
```
## Basic operators, maths
### Addition +
The addition operator (+) adds numbers:
```
var z = 2 + 3;
```
### Subtraction -
The subtaction operator (-) subtracts one number from another:
```
var z = 7 - 3;
```
### Multiplication *
The multiplication operator (*) multiplies numbers:
```
var z = 2 * 3;
```
### Division /
The division operator (+) divides numbers:
```
var z = 100 / 3;
```
### Remainder %
The remainder operator (%) gives remainder of the integer division:
```
var z = 100 % 3;
```
### Exponentiation **
The exponentiation operator (**) results of raising the first operand to the power of the second operand.:
```
var z = 2 ** 3;
```





















