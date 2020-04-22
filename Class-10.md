# Class 10 Notes
## Michelle Salazar

## JS Debuging

## EXECUTION CONTEXT
Every statement in a script lives in one of three
execution contexts: 
### GLOBAL CONTEXT
Code that is in the script, but not in a function. There is only one global context in any page.
### FUNCTION CONTEXT
Code that is being run within a function. Each function has its own function context.
### EVAL CONTEXT (NOT SHOWN)
Text is executed like code in an internal function called eval {) (which is not covered in this book).

## VARIABLE SCOPE
The first two execution contexts correspond with the
notion of scope (which you met on p98):
### GLOBAL SCOPE
If a variable is declared outside a function, it can be used anywhere because it has global scope. If you do not use the var keyword when creating a variable, it is placed in global scope.
###  FUNCTION-LEVEL SCOPE
When a variable is declared within a function, it can only be used within that function. This is because it has function-level scope.


***the  Stack*** when a statement needs data from another function it stacks or piles the new function on top of the current task.

Each time a script  enters a new execution contect, there are two phase of activity:
    1 Prepare
    2 Execute

this is called hoisting

each execution context also creates its own variables object. This object contains details of all the vairables, functions, and parameters for tat execution of content.

## Error Objects
When an Error object is created, it will contain the following properties:
|PROPERTY |DESCRIPTION |
---|---
name | Type of error
message | Description 
fileNumber | Name of the JavaScript file 
lineNumber | Line number of error



|OBJECT | DESCRIPTION |
---|---
Error | Generic error - the other errors are all based upon this error
SyntaxError | Syntax has not been followed
ReferenceError | Tried to reference a variable that is not declared/within scope
TypeError | An unexpected data type that cannot be coerced
RangeError | Numbers not in acceptable range
URIError  | encodeURI ().decodeURI(),and similar methods used incorrectly
EvalError | eval () function used incorrectly


 
### Debugging
### * Try- specify the code  you think might throw an exception.
### * Catch - if there is an exception, run this code
### * Finally - this always gets excuted

to create your own error, you use the folliwng line:

throw new Error('message');


### Debuging tips
## ANOTHER BROWSER  
Some problems are browser- specific. Try the code in another browser to see which ones are causing a problem.
## ADD NUMBERS
Write numbers to the console
so you can see which the items get logged. It shows how far your code runs before errors stop it.
## STRIP IT BACK
Remove parts of code, and strip it down to the minimum you need. You can do this either by removing the code altogether, or by just commenting it out using multi-line comments:
/* Anything between these characters is a cofllllent */
## EXPLAINING THE CODE
Programmers often report finding a solution to a problem while explaining the code to someone else.
## SEARCH
Stack Overflow is a Q+A site for programmers.
Or use a traditional search engine such as Google, Bing, or DuckDuckGo.
## CODE PLAYGROUNDS
If you want to ask about problematic code on a forum, in addition to pasting the code into a post, you could add it to a code playground site (such as JSBin.com, JSFiddle.com, or Dabblet.com)and then post a link to it from the forum.
(Other popular playgrounds include CSSDeck.com and CodePen.com - but these sites place more emphasis on show and tell.)

##VALIDATION TOOLS 
There are a number of online validation tools that can help you try to find errors in your code:

 GO BACK TO BASICS | MISSED/ EXTRA CHARACTERS | DATA TYPE ISSUES 
 ---|---|---
|JavaScript is case sensitive so check your capitalization.| Every statement should end in a semicolon. | Using= rather than == will assign a value to a variable, not check that the values match.
|If you did not use var to declare the variable, it will be a global variable, and its value could be overwritten elsewhere (either in your script or by another script that is included in the page). | Check that there are no missing closing braces \} or parentheses \) |If you are checking whether values match, try to use strict comparison to check datatypes at the same time. (Use === rather than ==.)
|If you cannot access a variable's value, check if it is out of scope, e.g., declared within a function that you are not within.| Check that there are no commas inside a , } or ,) by accident.| Inside a switch statement. the values are not loosely typed (so their type will not be coerced).
|Do not use reserved words or dashes in variable names. | Always use parentheses to-surround a condition that you are testing. | Once there is a match in a switch statement, all expressions will be executed until the next br eak or return statement is executed.
|Check that your single I double quotes match properly. | Check the script is not missing a parameter when calling a function. | The replace() method only replaces the first match. If you want to replace all occurrences, use the global flag.
|Check that you have escaped quotes in variable values. | undefined is not the same as nu11 : nu11 is for objects, undefi ned is for properties, methods, or variables. | If you are using the parseInt() method, you might need to pass a radix (the number of unique digits including zero used to represent the number).
|Check in the HTML that values of your id attributes are unique. | Check that your script has loaded (especially CDN files).|
| | Look for conflicts between different script files. 









# [Home](https://misalz.github.io/Reading-Notes)