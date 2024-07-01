# Statements, Conditionals, and Functions

## Truthy vs Falsy - everything can be converted to a boolean

- Truthy Values
  - true
  - non-empty strings
  - ALL numbers except for zero

- Falsy
  - false
  - "", '', ``
  - 0
  - null
  - undefined
  - NaN - not a number

## Equals Symbols

- = -> assigning a variable to a value
- == -> loosely equals (DO NOT USE)
- === -> strictly equals
- != -> loosely inequal (DO NOT USE)
- !== -> strictly inequal

## Control Flow - how to tell the computer to make decisions

- if statements
  - if(condition) { do something }
- else statements
  - have to go with an if statement
  - else { do something else }
- else if
  - else if (condition) { do something }

## Converting Data Types

- use the name of the data type you want to convert to with a capital letter and then pass in the value you want to convert in parenthesis

## Prompt - one way to get user input

- allows the user to input a value
- ALWAYS comes back as a string

## Functions - block of code that will execute a given task

- just a set of directions
- can be re-used throughout your code and can be called when something triggers it (like a button click)
- two ways to write a function
  - function functionName() { code } (ES5)
  - const functionName = () => { code } (ES6)
- how to invoke (run) a function -> functionName()

## Parameters vs Arguments

- parameters are in the function definition and act as a placeholder for values
- arguments are the real values that are passed into the function call

## The return keyword

- only used in functions
- what the function sends back to whatever called it
- once you return, the function stops

## Getting a random number in JS

- Math.random() -> outputs a random number between 0 and 1
- Math.floor() -> rounds a number down
