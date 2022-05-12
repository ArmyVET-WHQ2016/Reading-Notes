
# Expressions and operators

-Operators

- *JavaScript* has the following types of operators. This section describes the operators and contains information about operator precedence

1. Assignment
2. Comparison
3. Arithmetic
4. Bitwise
5. Logical
6. String
7. Conditional- ternary
8. Comma
9. Unary
10. Relational

Note: *JavaScript has both binary and unary operators, and one special ternary operator, the conditional operator. A binary operator requires two operands, one before the operator and one after the operator:*

Example of binary operator:
**operand1 operator
operand2** 3+4 or x * y

Example of unary operator: **operator operand** or operan operator x++ or ++x

- Assignment Operator

**An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal =, which assigns the value of its right operand to its left operand.** T

- **Assigning to properties**

*If a variable refers to an object, then the left-hand side of an assignment expression may make assignments to properties of that variable.*let*obj = {};*

- Destructuring

Syntax is a JavaScript expression that makes it possible to extract data from arrays or objects using a syntax that mirrors the construction of array and object literals.

- Evaluation and nesting. In general, assignments are used within a variable declaration i.e., with const, let, or var or as standalone statements.**Chaining assignments or nesting assignments in other expressions can result in surprising behavior.** *By chaining or nesting an assignment expression, its result can itself be assigned to another variable. It can be logged, it can be put inside an array literal or function call, and so on.*

Note: **for all assignment operators other than = itself, the resulting values are always based on the operands' values before the operation.**

- Comparsion Operators

**ompares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values. Strings are compared based on standard lexicographical ordering, using Unicode values. In most cases, if the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison. This behavior generally results in comparing the operands numerically**.

### Loops and iteration

Loops offer a quick and easy way to do something repeatedly-they repeat an action some number of times.

The statement for loop provided in JavaScript are

1. for statement
2. do...while statement
3. while statement
4. labeled statement
5. break statement
6. continue statement
7. for... in statement
8. for..of statement

- **for statement**

A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.

When a for loop executes, the following occurs:

1. The initializing expression initialExpression, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.

2. The condition Expression expression is evaluated. If the value of condition expression is true, the loop statements execute. Otherwise, the for loop terminates. If the condition Expression expression is omitted entirely, the condition is assumed to be true.
3. The statement executes. To execute multiple statements, use a block statement { ... } to group those statements.
4. If present, the update expression incrementExpression is executed.
5. Control returns to Step 2.

HTML example:
*the function contains a for statement that counts the number of selected options in a scrolling list a select element that allows multiple selections*.

JavaScript example:*the for statement declares the variable i and initializes it to 0. It checks that i is less than the number of options in the select element, performs the succeeding if statement, and increments i by 1 after each pass through the loop.*

- **while statement**

A while statement executes its statements as long as a specified condition evaluates to true. A while statement looks as follows:*If the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop.* **The condition test occurs before statement in the loop is executed. If the condition returns true, statement is executed and the condition is tested again. If the condition returns false, execution stops, and control is passed to the statement following while.**

Note: You can find more information on the listed statements for loops provided in JavaScript at **<https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration>**
