# Programming with JavaScript
## Control flow
When code is run, the computer reads the code line by line. How the code is read is called control flow. The computer will normally read it from top to bottom unless it comes across a **conditional** or **loop**. These structures can make the computer go back to previous code and excecute it again. This will be discussed in more detail in the next article.
## Operators
To assign values to variables, JavaScript uses the assignment operator **=**. In the example below, the variable x is being declared or assigned to a value of the number 1.

    let x = 1;

 

Operators can also perform math! Below is an example of a statement that assigns the difference of the x and y variables to the z variable using the **-** operator.

    let z = x - y

There are more operators for many more uses.
## Functions
A benefit of using a function is that it can be **invoked** or called upon to be used thoughout the code multiple times. In the example below, two variables are assigned and a function called sum is created. 

    let a = 2;
    let b = 10;
    function sum(){
        return a + b;
    }    

This function excecutes a **return** statement to send back the sum of the variables to where the function was invoked. In the example below, we use the document.write( ) function to invoke the sum function and display the value on the website.

    document.write(sum())

**Note:** The document.write() is no longer in use due to security risks. It is used in the example for demonstration purposes only.

We can then use the following HTML element to apply the JavaScript code.

    <script src="filename.js"></script>

[Main Page](programming.md)








