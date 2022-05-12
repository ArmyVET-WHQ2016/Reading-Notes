# *JavaScript*

Definition:

*JavaScript* is a lightweight, interpreted, or just-in-time compiled programming language with first-class functions. While it is most well-known as the scripting language for Web pages, many non-browser environments also use it, such as Node.js, Apache CouchDB and Adobe Acrobat. JavaScript is a prototype-based, multi-paradigm, single-threaded, dynamic language, supporting object-oriented, imperative, and declarative e.g. functional programming styles

The standards for JavaScript are the *ECMA Script Language Specification ECMA-262* and the *ECMAScript Internationalization API specification*

Note: **Do not confuse JavaScript with the Java programming language. Both "Java" and "JavaScript" are trademarks or registered trademarks of Oracle in the U.S. and other countries. However, the two programming languages have very different syntax, semantics, and use.**

## *Key Features*

1. Variables  
2. Strings
3. Numbers
4. Arrays  

Asynchronous JavaScript can be used to effectively handle potential blocking operations such as fetching resources from a server.

### **Understanding client-side JavaScript frameworks**  

*JavaScript* frameworks are an essential part of modern front-end web development, providing developers with proven tools for building scalable, interactive web applications

JavaScript provides three different value-comparison operations:

- strict equality using ===
- loose quality using ==
- Object.is method

A *closure* is the line combination of a function and the lexical environment within that function was declare

Strict Mode defines that you can not use any variable before initializing it. It is restricted variant of ECMAScriot 5, for faster performance and easier debugging.

JavaScript typed arrays provide a mechanism for accessing raw binary data.JavaScript has a concurrency model based on an "event loop

#### **Input Output in plain JavaScript**

In the JavaScript code we have a function called say_hi. It used the getElementById we have already seen to locate the DOM element representing the input element with the id first_name. The object returned has a method value that will return the text the user has typed in that field.

- We use this technique to retrieve the content of both input fields and assign their content to two variables: fname and lname.

- Then, using these variable we create an HTML snippet and assign it to a new variable called html.

- Then we set the inner HTML attribute as earlier to show the HTML we generated. The result might look like this:

4 Ways to Declare a JavaScript Variable:

- Using *var*
- Using *let*
- Using *const*
- Using nothing

Varable are containers for storing data " storing data values.

##### When to Use JavaScript var?

1. Always declare JavaScript variables with *var*,*let*, or *const*.

2. The *var* keyword is used in all JavaScript code from 1995 to 2015.

3. The *let* and *const* keywords were added to JavaScript in 2015.

4. If you want your code to run in older browser, you must use *var*.

###### **When to Use JavaScript const?**

1. If you want a general ruloe: always declare variables with *const*.

2. If you think the value of the variable can change, use *let*.

3. The two variable *price1* and *price2* are declared with the *const* keyword.

4. The variable *total* is declared with the *let* keyword.

Note 1: *Variables are used in expression "just like in algebra. Variables are containers for storing values*. All JavaScript variables must be identified with unique names. These unique names are called *identifiers*. Indentifiers can be short names or more descriptive names.

Note 2: **JavaScript identifiers are case sensitive**

- The Assignment Operator

In JavaScript, the equal sign = is an "assignment" operator, not an "equal to" operator.

x = x + 5

Note:**The "equal to" operator is written like == in JavaScript

- JavaScript Data Types

JavaScript variables can hold numbers like 100 and text values like "John Doe".

- In programming, text values are called text strings.

JavaScript can handle many types of data, but for now, just think of numbers and *strings*. Strings are written inside double or single quotes. Numbers are written without quotes. If you put a number in quotes, it will be treated as a text string.

const pi = 3.14;
let person = "John Doe";
let answer = 'Yes I am!';

- Declaring a JavaScript Variable

Creating a variable in JavaScript is called "declaring" a variable.

You declare a JavaScript variable with the var or the let keyword:

Example: *var* carName; or *let* carName;

Note: **It's a good programming practice to declare all variables at the beginning of a script.**

- One Statement, Many Variables

You can declare many variables in one statement.

Start the statement with let and separate the variables by comma:

 Example *let* person = "John Doe", carName = "Volvo", price = 200;

- A declaration can span multiple lines:

Example: *let* person = "John Doe",
carName = "Volvo",
price = 200;

- Value = undefined

In computer programs, variables are often declared without a value. The value can be something that has to be calculated, or something that will be provided later, like user input. A variable declared without a value will have the value undefined. The variable carName will have the value undefined after the execution of this statement:

Example: let carName;

- Re-Declaring JavaScript Variables

If you re-declare a JavaScript variable declared with var, it will not lose its value. The variable *carName* will still have the value "Volvo" after the execution of these statements:

Example: *var* carName = "Volvo";
*var* carName;

Note: **You cannot re-declare a variable declared with let or const**.

This will not work:

let carName = "Volvo";
let carName.**

- JavaScript Arithmetic

As with algebra, you can do arithmetic with JavaScript variables, using operators like = and +:

Example: let x = 5 + 2 + 3;

Note: **If you put a number in quotes, the rest of the numbers will be treated as strings, and concatenated**.

- JavaScript Dollar Sign $

Since JavaScript treats a dollar sign as a letter, identifiers containing $ are valid variable names:

JavaScript Underscore _

Since JavaScript treats underscore as a letter, identifiers containing _ are valid variable names: *Using the underscore is not very common in JavaScript, but a convention among professional programmers is to use it as an alias for "private hidden" variables*.
