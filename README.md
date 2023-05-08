# Reveiw Functions And Objects


## Objectives

- Review javaScript object literals
- Review javaScript functions
- Solve code problems using functions and objects

## Preparation

1. Fork and clone this repository.
 [FAQ](https://git.generalassemb.ly/ga-wdi-boston/meta/wiki/ForkAndClone)
1. Create a new branch, `review`, for your work.
1. Checkout to the `review` branch.
1. Install dependencies with `npm install`.

## Review Functions

In the last few days, we covered some important concepts about functions:

* A function is a reusable block of code that groups together a sequence of statements to perform a specific task.

* A function declaration :

![Diagram showing the syntax of a function declaration](https://content.codecademy.com/courses/learn-javascript-functions/Diagram/declaration.svg)

* A parameter is a named variable inside a function’s block which will be assigned the value of the argument passed in when the function is invoked:

![JavaScript syntax for declaring a function with parameters](https://content.codecademy.com/courses/learn-javascript-functions/Diagram/function_parameters.svg)

* To *call* a function in your code:

![Diagram showing the syntax of invoking a function](https://content.codecademy.com/courses/learn-javascript-functions/Diagram/name.svg)

* ES6 introduces new ways of handling arbitrary parameters through default parameters which allow us to assign a default value to a parameter in case no argument is passed into the function.

* To return a value from a function, we use a return statement.

* To define a function using function expressions:

```js

```

* To define a function using arrow function notation:

```js

```


* Function definition can be made concise using concise arrow notation:

```js
const sumNumbers = number =>{
const sum = number + number;
return sum
}

//convert to a concise function


```

It’s good to be aware of the differences between function expressions, arrow functions, and function declarations. As you program more in JavaScript, you’ll see a wide variety of how these function types are used.
