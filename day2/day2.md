### Day 2 - 7th June 2023
Today I leverage [JavaScript: The Definitive Guide](https://www.amazon.com/JavaScript-Definitive-Guide-Activate-Guides/dp/0596805527) book by David Flanagan and [Javascript.info](https://javascript.info/) website to get a hang of what javascript is. Basically JavaScript is a scripting language that initially created as a browser-only language but as it evolue, JavaScript can now execute on the server as well or on any device with a JavaScript engine.

JavaScript engine is a software component that executes JavaScript code. They include:-
- V8 – in Chrome, Opera and Edge.
- SpiderMonkey – in Firefox.
- Chakra - in IE

## Purpose of JavaScript in Browsers

JavaScript manipulate webpages, interact with users and webservers. It is able to:-
- Add new HTML to the page or change the existing content
- modify the CSS stylings of the page.
- React to user actions like mouse clicks. To mention but a few

JavaScript is unique because of it's full integration with HTML and CSS and it's supported by all the major web browsers.

## The Lexical Structure of JavaScript

The Lexical Structure of JavaScript are sets of elementary rules that specifies how you write programs in that JavaScript, in other words the building blocks of JavaScript. They include:-
- Unicode character set  - JS uses the unicode character set which is a superset of the ASCII character encoding format. meaning you can write identifiers names in any language on the plate.
- Case Sensitivity - JS is case-sensity meaning the keywords, variable names, functions names and other identifiers must be typed with consistency for example the following variable names are different.
`let firstName` and `let firstname` or `let FirstName`
- Whitespace and Line Breaks - JavaScript ignores whitespace and line breaks but for the readability of the code, it's neccessary to format your code. However using **Prettier** code formatter extention in the VSCODE can do the trick.
- Comments - comments are used to add information about code so that other programmers can understand. JavaScript use two styles of comment // and /* */
- Literals - Is a data value that appears directly in the program. for example
`12`, `true`, `false` `"hello world"`
- Identifiers - is simply a name that is given to a variable, function etc. JavaScript Identifiers have the following rules
    - must begin with either underscore(_) or a dollar sign($) and a string
    - must not begin with a digit so that JavaScript can easily distinguish identifiers from numbers.
- Reserved Keywords - This are identifiers that are used in the language itself and they cannot be used as variable names, functions names etc. for example
`let`, `for`, `while`, `break` to mention but a few.
- Optional Semicolons - semicolons in JavaScript are optional but it's a good practice to always add a semicolon at the end of a statement to avoid bugs in the code.

## [On to Day 3](/day3/day3.md)
