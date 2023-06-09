### Day 4 - 9th June 2023

# Types, Values and Variables

Today is about strings and other data types in JavaScript.

## Strings

Strings represents text in JavaScript with an ordered sequence of immutable 16-bit values, it's length is a number of 16-bit values it contains. They're zero based index just like arrays though they must be enclosed in double `" "` or single `' '` quotes ot backticks **` `**

## Working with Strings

+ Using the Addition (+) operator joins two strings by appending the second to the first e.g: `"My name is" + "De Malong"` will be concatenate to form `"My name is De Malong`.
+ To find the length of a string i.e to find how many characters are in a string, the `length` property is used eg `let msg = "Programming is awesome"` will give `22` when the length property is called on the msg `msg.length`.
+ Strings have a number of built-in methods that can be used to manipulate them examples are **charAt()**, **charAt(**), **substring()** and **slice()** to mention but a few. strings are immutable and methods like `replace()` and `toUpperCase()` return new strings but do not modify the string on which they are invoked.

## Booleans Values

There are only two possible values of this type, the reserved words `true` and `false` evaluate to these two values. which represents truth or falsehood, on or off, yes or no. The two values are predominently used in comparisions i.e comparing one variable to another eg `a == b, 3 < 4` and so on.

## Null and Undefined
Null in Javascript usaully indicates the absent of a value, Undefined also indicates an absent of a value but it usually occurs when a variable is uninitialized and the value you get when you query the value of an object property or array element that does not exist. 

 ## [On to Day 5](/day5/day5.md)