[Operators and Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)

JS Has both binary and unary operators, and a ternary operator which is known as the conditional operator. A binary operator requires 2 operands, one before the operator and one after the operator. 

A Unary operator requires a single operatnd, either before or after the operator. 

Assignment Operators

Assigns a value to its left operand based on the value of its right operand. The simple assignment operator is the equal sign, which assigns the value of its right operand to its left operand. ie, x=y assigns the vaule of y to x. 

Like most expressions, assignments like x=y have a return value. for example, if you did: 
const z=x=y, 
console.log(z); returns value of the assignment x=7
and 
console.log(x = y); returns the value directly. 

?Destructuring: Makes it possible to extract data froim arrays or objects using a syntax that mirros the construction of array and object literals. 

Comparison Opperators: compares its operands and returns a logical value based on whether the comparison is true. 

Arithmetic opoerators: takes numberical values as their operands and returns a single numerical value. 

Logical operatorsL typical used with boolean values, but may also return the value of one of the specified operands if && or || operators are used. 

String Operators: Concatenation operator is +, and concatenates two string values together, reutrning another string thatis the union of the two operand strings. 

Conditional Operator: Only JS operator that takes 3 operands. Operator can have one of two values based on a condition. 

Comma operator: Evaluates both of its operands and returns the value of the last operand; typically used inside a for loop. 

typeof operatorL returns a string indicating the type of the unevaluated operand. 

Void: specifies an expression to be evaluated without returning a value. 

Relational: compares its operands and returns a boolean value based on whether the comparison is true. 

In: returns true if the specified property is in the specified object. 

Instanceof: returns true if the specified object is the specified object type. 

Presedence of operators determines the order they are appliesd when evaluating an expression, can be overridden via parenthesis. 

An expression is any valid unit of code that resolves to a value. 

This: refers to the current object. 

[Loops and Iteration](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)

Loops offer a quick way to do something repeatedly. 
Example
for (let step = 0; step < 5; step++) {
  // Runs 5 times, with values of step 0 through 4.
  console.log('Walking east one step');
}

For StatementL a for loop repeats until a specified condition evaulates to false. 

do...while statement: repeats until a specified codition evaluates to false. 

While statement: Executes its statements as long as a specified condition evaluates to true. 

Labeled Statement: Provides statement with an identifier that lets you refer to it elsewhere in your program. 

Break statement terminates a loop. 

Continue statement can be used to restart a while, do whhile, for, or label statement. 

For in statement iterates a specified variable over all the enumerable properties of an object. 

For...of statement creates a loop iterating over iterable objects, invoking a custome iteration hook with statements to be executed for the value of each distince proiperty. 