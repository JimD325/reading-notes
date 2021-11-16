**Day 7 Reading Notes**

[Control Flow](https://developer.mozilla.org/en-US/docs/Glossary/Control_flow)

Control Flow is the order in which the computer executes statements in a script. Code is always run from the first line to the last line, unless there is a structure which changes the control flow, such as a conditional or a loop. 

A conditional could be of the form of an IF ELSE statement. 

A conditional is a set of rules thatcan interrupt normal code execution or change it, depending on whether the condition is completed or not. An instruction or a set of instruction is executed if a specific condition is fulfilled, otherwise another instruction is executed. ie IF condition is true then do X, ELSE do Y. 

Loop: A sequence of instructions which are repeated continually untel a certain condition is met. 

FOR loop: A series of statements which are executed in sequence, with statement one being executed once code is run, statement 2 defining the condition to execute the code block, and statement 3 executing every time the code block is run. 
WHILE loop: The code block will continue to loop as long as the condition is true. 

[Functions](https://www.w3schools.com/js/js_functions.asp)

A function is a block of code designed to do a particular task. A function is executed when something invokes it. 

function name(insert variables/parameters here) {code to be executed goes here}

Function Return: When JS reaches a return statement, the function will stop executing. 

Steps: 
1. define variable --> let x =function (n_0,n_1,...n_z)
2. Function function(a, b) {
    return a*b
}
With functions, you can define the code just once, and use it many times, and can use it with different arguements to produce different results. 

() is an operator, and invokes the function. So, the function name refers to the function object, the function name () refers to the function result. 

Functions may be used the same way you use variables in all types of formuals, assignments, and caluclations. 

Local Variables: 
A local variable is declared within a JS function, and can only be accessed from within the function. 
// code here can NOT use carName

function myFunction() {
  let carName = "Volvo";
  // code here CAN use carName
}

[Operators](https://www.w3schools.com/js/js_operators.asp)


= is the assignment operator

+ means add, - means subtract etc...

** means exponentiation
% means modulus
++ means increment
--decrement 

Strings/#s can be concatenated using +

so Can +=

Addint two numbers returns the sum adding a number and a string returns a string. 

?	ternary operator

==	equal to

===	equal value and equal type

!=	not equal

!==	not equal value or not equal type

&&	logical and

||	logical or

!	logical not

typeof	Returns the type of a variable

instanceof	Returns true if an 
object is an instance of an object type

[Expressions and Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)

[More Indepth Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)