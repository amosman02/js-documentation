# JS Documentation

[View on MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)

## Table of Contents

- [Introduction](#introduction)
- [What You Should Already Know](#what-you-should-already-know)
- [JavaScript and Java](#javascript-and-java)
- [Hello World](#hello-world)
- [Variables](#variables)
- [Declaring Variables](#declaring-variables)
- [Variable Scope](#variable-scope)
- [Global Variables](#global-variables)
- [Constants](#constants)
- [Data Types](#data-types)
- [if...else Statement](#ifelse-statement)
- [while Statement](#while-statement)
- [Function Declarations](#function-declarations)
- [Reference](#reference)

## Introduction

JavaScript is a cross-platform, object-oriented scripting language. It is a small and lightweight language. Inside a host environment (for example, a web browser), JavaScript can be connected to the objects of its environment to provide programmatic control over them.

JavaScript contains a standard library of objects, such as Array, Date, and Math, and a core set of language elements such as operators, control structures, and statements. Core JavaScript can be extended for a variety of purposes by supplementing it with additional objects.

## What You Should Already Know

This guide assumes you have the following basic background:

- A general understanding of the Internet and the World Wide Web (WWW).
- Good working knowledge of HyperText Markup Language (HTML).
- Some programming experience. If you are new to programming, try one of the tutorials linked on the main page about JavaScript.

## JavaScript and Java

JavaScript and Java are similar in some ways but fundamentally different in others. JavaScript is not Java; it is a dynamic, prototype-based, and loosely-typed language.

## Hello World

To get started with writing JavaScript, open the Scratchpad and write your first "Hello world" JavaScript code:

```javascript
function greetMe(yourName) {
  alert("Hello " + yourName);
}

greetMe("World");
```

## Variables

Variables are used as symbolic names for values in your application. A JavaScript identifier must start with a letter, underscore (\_), or dollar sign ($) and can contain alphanumeric characters.

### Declaring Variables

You can declare a variable in three ways:

- With the keyword var. For example, `var x = 42`.
- By simply assigning a value. For example, `x = 42`. (Note: This always declares a global variable and is discouraged.)
- With the keyword let. For example, `let y = 13`.

### Variable Scope

JavaScript has variable scope. Variables declared outside of functions are global, while variables declared inside functions have local scope. The introduction of let in ECMAScript 2015 provides block scope for variables.

## Global Variables

Global variables are properties of the global object, which is window in web pages. You can access global variables using the `window.variable` syntax.

## Constants

You can create read-only, named constants with the `const` keyword. Constants cannot be re-declared or changed after they are initialized.

## Data Types

JavaScript has seven data types:

- Boolean
- Null
- Undefined
- Number
- String
- Symbol (ES6)
- Object

These data types allow you to perform various functions in your applications.

## if...else Statement

The `if` statement executes a block of code if a specified condition is true. The `else` clause allows executing a different block of code if the condition is false.

## while Statement

The `while` statement executes a block of code as long as a specified condition is true.

## Function Declarations

JavaScript functions are defined using the function keyword, followed by the function name, a list of arguments, and the function's code block.

## Reference

For more detailed documentation and examples, visit the MDN JavaScript Guide.
