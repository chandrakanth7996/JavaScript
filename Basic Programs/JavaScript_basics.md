console.log("Hello, world!");

console.log prints to the console (browser console or terminal). Strings use quotes ("..." or '...' or `...`).

# Variables and how to declare them

let — for variables you expect to change.

const — for values that should not be reassigned.

var — old style; avoid for now.

# example
let age = 25;
const name = "Ram";

# Primitive data types

Number — 42, 3.14
String — "hello", 'hi', `template`
Boolean — true or false
undefined — a variable declared but not assigned
null — intentionally no value
Symbol — for unique identifiers (advanced; we'll cover later)

# typeof operator
console.log(typeof 42);      // "number"
console.log(typeof "hey");   // "string"
console.log(typeof true);    // "boolean"
console.log(typeof undefined); // "undefined"
console.log(typeof null);     // "object"

# Basic operators

Arithmetic: + - * / % (remainder)
String concatenation: "Hi, " + name
Assignment: = and compound +=, -=, etc.
Comparison (loose): ==, != (we’ll prefer strict ===/!== later)

# Small example program

const firstName = "Ram";
let score = 10;
score = score + 5;
console.log(firstName + " scored " + score + " points");
