# Read07
***JavaScript Functions***

JavaScript provides functions similar to most of the scripting and programming languages.

A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().


***Why Functions?***

*You can reuse code: Define the code once, and use it many times.
You can use the same code many times with different arguments, to produce different results.*

***Function declarations:***

A function definition (also called a function declaration, or function statement) consists of the function keyword, followed by:

The name of the function.
A list of parameters to the function, enclosed in parentheses and separated by commas.
The JavaScript statements that define the function, enclosed in curly brackets, {...}.

***Function expressions:***

While the function declaration above is syntactically a statement, functions can also be created by a function expression.

Such a function can be anonymous; it does not have to have a name. 

***Calling functions:***
Defining a function does not execute it. Defining it names the function and specifies what to do when the function is called.

Calling the function actually performs the specified actions with the indicated parameters.

**JavaScriptCode for Example**

**function toCelsius(fahrenheit) {
  return (5/9) * (fahrenheit-32);
}
document.getElementById("demo").innerHTML = toCelsius;**

