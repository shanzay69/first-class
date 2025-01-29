# first-class
TypeScript Fundamentals – Template Literals & Unary Operators

This project contains basic TypeScript exercises demonstrating the use of:
1- Template Literals
2- Unary Operators (Prefix and Postfix Increment/Decrement)

Concepts Used

1. Template Literals (Backticks ``)
Template literals allow embedding variables inside strings using ${} syntax.
This makes string concatenation easier and more readable.
Example:
let firstname = "shanza khan";
let fatherName = "sardar";
console.log(`Hello, my name is ${firstname} and my father's name is ${fatherName}`);

Output:
Hello, my name is shanza khan and my father's name is sardar
. Unary Operators (++, --)
Unary operators increment (++) or decrement (--) a variable by 1.
They can be used as prefix (++index) or postfix (index++).
Prefix (++index or --index): The value is changed before using it.
Postfix (index++ or index--): The value is used first, then changed.

Example 1: Prefix Increment (++index)
let index = 10;
++index; // 10 + 1 = 11
++index; // 11 + 1 = 12
++index; // 12 + 1 = 13
++index; // 13 + 1 = 14
++index; // 14 + 1 = 15
console.log(index);
Output:
15
How to Run the Code
1- Install Node.js if not already installed.
2- Save the code in a TypeScript file (e.g., index.ts).
3- Compile the TypeScript file using:
tsc index.ts
Run the generated JavaScript file:
node index.js



















