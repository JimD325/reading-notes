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

**lecture Notes:** 

Loops: We are going to focus on while, do while, and for loops. 

While Loop: much like an if statement or a function, starts with the word
while(condition){}
//as loong as conidtion is met, code block will run
ex: 

letn number =1;
while(number <5){
    console.log(number);
};  
This would create an infinite loop

so we do: 

letn number =1;
while(number <5){
    number = number +1;
    console.log(number);
};

could also do number ++ instead of number = number +1, that is an incremental of one. 

Return vs Consol log

Return actually returns the value back to someone, the console log just displays the answer. 

While loops are basically if statements, just with multiple iterations. 

Do while: 

Rarely used in every day development because there are other ways to do it, but there is utility in games or user interactions. 
Do while loops guaruntees you at least one iteration.

let answer = ""
d{
let answer = prompt("how many cats does amanda have?");
}while(answer != "2") 

For Loops: 

**One of the most fundamental tools you have as a developer**

You need to know these, not an uncommon interview question to write down a for loop on a white board. Useful if you know you only want to give a few attempts to get the right answer, or how many items are in a list. 

there are three parameters (all separated by a semi colon ;)

**p 1 is declaring the variable and setting its value**

**p 2 is the condition that must be met for the loop to run**

**p 3 declare what happens to the variable after each iteration.** 

must have exactly 3 parameters for the for loop to be run

for(let bananna = 0; bananna < 5; bananna++){
    console.log(bananna);
}

typically they use i instead of a actual variable name. thats because with the variable being declared inside of the for loop, it doesnt exist outside of the for loop. 