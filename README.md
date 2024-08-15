# JavaScript Concepts

## Table of Contents

1. [Introduction](#introduction)
2. [Variables and Data Types](#variables-and-data-types)
3. [Operators](#operators)
4. [Control Structures](#control-structures)
5. [Functions](#functions)
6. [Objects](#objects)
7. [Arrays](#arrays)
8. [Scope and Hoisting](#scope-and-hoisting)
9. [Closures](#closures)
10. [Promises and Asynchronous JavaScript](#promises-and-asynchronous-javascript)
11. [ES6+ Features](#es6-features)
12. [Classes (ES6)](#classes-es6)
13. [Modules (ES6)](#modules-es6)
14. [Error Handling](#error-handling)
15. [The DOM (Document Object Model)](#the-dom-document-object-model)
16. [JSON (JavaScript Object Notation)](#json-javascript-object-notation)
17. [Fetch API](#fetch-api)
18. [Web Storage](#web-storage)
19. [Regular Expressions](#regular-expressions)

## Introduction

JavaScript is a versatile programming language that is essential for creating dynamic and interactive web content. This README covers essential concepts of JavaScript, helping developers understand and utilize the language effectively.

## Variables and Data Types

### Variables
- **var**: Function-scoped or globally scoped.
- **let**: Block-scoped variable.
- **const**: Block-scoped constant, cannot be reassigned.

### Data Types
- **Primitive Types**:
  - **String**
  - **Number**
  - **Boolean**
  - **Null**
  - **Undefined**
  - **Symbol** (ES6)
  - **BigInt** (ES11)
- **Reference Types**:
  - **Object**
  - **Array**
  - **Function**

## Operators

### Arithmetic Operators
- `+`, `-`, `*`, `/`, `%`, `++`, `--`

### Comparison Operators
- `==`, `===`, `!=`, `!==`, `>`, `<`, `>=`, `<=`

### Logical Operators
- `&&`, `||`, `!`

### Assignment Operators
- `=`, `+=`, `-=`, `*=`, `/=`, `%=`

### Ternary Operator
- `condition ? expression1 : expression2`

## Control Structures

### Conditional Statements
- **if...else**
- **switch**

### Loops
- **for**: Loops through a block of code a number of times.
- **for...in**: Loops through the properties of an object.
- **for...of**: Loops through the values of an iterable object.
- **while**: Loops through a block of code while a specified condition is true.
- **do...while**: Also loops through a block of code while a specified condition is true, but always executes the block at least once.

## Functions

### Function Declaration
```javascript
function functionName(parameters) {
  // code to be executed
}
