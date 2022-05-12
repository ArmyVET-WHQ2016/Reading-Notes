# **Control flow**

The *control flow* **is the order in which the computer executes statements in a script**.

Code is run in order from the first line in the file to the last line, unless the computer runs across the extremely frequent structures that change the control flow, such as conditionals and loops.

Key Notes: *The script submits validated data, but if the user, say, leaves a required field empty, the script prompts them to fill it in. To do this, the script uses a conditional structure or if...else, so that different code executes depending on whether the form is complete or not*:**Control flow means that when you read a script, you must not only read from start to finish but also look at program structure and how it affects order of execution**

## **JavaScript Functions**

- A JavaScript function is a block of code designed to perform a particular task.

- A JavaScript function is executed when "something" invokes it calls it.

JavaScript Function Syntax

- A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses.

- Function parameters are listed inside the parentheses () in the function definition.

- Function arguments are the values received by the function when it is invoked.

Note: **A Function is much the same as a Procedure or a Subroutine, in other programming languages**.

### Function Invocation

The code inside the function will execute when "something" **invokes** calls the function:

- When an event occurs when a user clicks a button
- When it is invoked called from JavaScript code
- Automatically self invoked

#### **Function Return**

When JavaScript reaches a *return* statement, the function will stop executing.Functions often compute a return value. The **return value** is "returned" back to the "caller"

Example: let x = myFunction 4, 3;   // Function is called, return value will end up in x

function myFunction a, b {
  return a * b;             // Function returns the product of a and b
}

##### **Why Functions?**

- You can reuse code: Define the code once, and use it many times.

- You can use the same code many times with different arguments, to produce different results.

Example
Convert Fahrenheit to Celsius:

function toCelsiusfahrenheit {
  return 5/9 * fahrenheit-32;
}
document.getElementById"demo".innerHTML = toCelsius77

- The () Operator Invokes the Function

1. Accessing a function without () will return the function object instead of the function result.

2. Functions can be used the same way as you use variables, in all types of formulas, assignments, and calculations.

3. Variables declared within a JavaScript function, become LOCAL to the function. Local variables can only be accessed from within the function.

Example
// code here can NOT use carName

function myFunction() {
  let carName = "Volvo";
  // code here CAN use carName
}

// code here can NOT use carName

- JavaScript Operators

1. The assignment operator = assigns a value to a variable.

Assignment
let x = 10;

2.The addition operator + adds numbers:

Adding
let x = 5;
let y = 2;
let z = x + y;

3.The multiplication operator * multiplies numbers.

Multiplying
let x = 5;
let y = 2;
let z = x * y;

- JavaScript Assignment Operators

1.The addition assignment operator += adds a value to a variable.

-JavaScript String Operators

Note: **The + operator can also be used to add concatenate strings.*When used on strings, the + operator is called the concatenation operator**

- Adding Strings and Numbers

Adding two numbers, will return the sum, but adding a number and a string will return a string:

Note:**If you add a number and a string, the result will be a string!**
