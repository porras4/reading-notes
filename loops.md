# Loops and Operators
## What is a loop?
A loop performs a set of code several times until a certain condition is met. There are several methods in JavaScript that allow developers to make loops.

## for
The method **for** is an example of a loop statement. This method will repeat a set of code until the condition is false. This loop is useful when you want to control the number of time the loop repeats. To use this loop, it must first be initialized with **expressions**.

**Note:** The operator **++** is the same as + 1.

    for (let x = 1; x <= 5; x++){
        document.write('Hello ');
    }

The expressions are written in the parantheses of the method. The first expression "let x = 1" makes the inital assignment of the variable x. The second expression "x < 5" sets the **condition**. When this condition is false, the loop will stop. The third expression "x++" increments the variable x by 1 each time the loop is performed. Notice ";" is used to separate the expressions. This loop will display the string 'Hello' five times before ending.

## while

Another example of a loop method is **while**. This method repeats the code until the condtion written in the parantheses is true.

**Note:** The operator **||** means or.

    let x = prompt('Enter a number from 1 to 5.');

    while (x < 1 || x > 5) {
       x = prompt('Try again, enter a number from 1 to 5.');
    }

This loop will continue to prompt the user to enter a value between from 1 to 5 until the condition is met.
 ## Operators
 Operators are important in loop methods. Below are a few more examples of operators used often in loops.

|Operator   | Meaning  |
|-----------|----------|
|**&&**     |**and**   |
|**\|\|**   |**or**    |
|**!**      |**not**   |
|**==**     |**equal**|
|**>**      |**greater than**|
|**<**      |**less than**|
|**++**     |**increment**|
|**--**     |**decrement**|

[Main Page](README.md)