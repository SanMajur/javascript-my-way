### Day 3 - 8th June 2023

# Types, Values and Variables
JavaScript Programs works by manipulating **Values** `123`, `"hello world"` and this values have **Types** which are than stored in **Variables** for future use. A variable defines a symbolic name for value which allows the said value to be referred to by name.

JavaScript has two types which are:-
- Primitive type - this includes **Numbers**, **Strings**, **Boolean**, **Null** and **Undefined**. Primitive type are immutable meaning their values can not be change.
- Object type - is a collection of properties where each property has a name and a value. The values can be of either primitive type or object type. Mostly an Objects in JS are unordered collection of named values. 
    - Arrays - are a special type of object that represents an ordered collection of numbered values.
    - Functions - are another special type of object that has executable code associated with it, they may be invoked to run that executable code and return a computed value.
Object and arrays are mutable meaning their values can be changed.
## Numbers
JavaScript does not make a distinction between integer values and floating-point values. Meaning all numbers are represented as floating-point values, and are represented by using the 64-bit floating-point format. When a number appears directly in a JavaScript program, it's called a **Numeric Literal**.

## Arithmetic in JavaScript
JavaScript programs work with numbers using arithmetic operators like
- Addition (+)
- Substraction (-)
- Multiplication (*)
- Division (/) and
- Modulo (%) - remainder after division

In addition to the above basic arithmetics operators, JavaScript provides a build-in **Math** object that provides functions to support complex arithmetic operations for example **Math.pow(2,53)**. There are some special global variables that are predefined by JS:
    - NaN - stands for not-a-number and it arises when you divide zero by zero or use an arithmetic operation  other than addition (+) with a non-number value like a string eg `"cat" / "dog"`.
    - Infinite - This occurs when the result of a numeric operation is larger than the largest representable number and it's counter part is **-Infinite** which occurs when a negative value becomes larger than the largest repre- sentable negative number.

    ## [On to Day 4](/day4/day4.md)