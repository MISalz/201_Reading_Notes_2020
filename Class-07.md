# Class 07 Notes
## Michelle Salazar

# HTML chp 6 pp126-145
Basic table structure
\<table> table 

\<tr> table row

\<td> table data

\<th> table header

for long tables you can use 
\<thead> headings
\<tbody> body of table
\<tfoot> footer of table

# JS chp 3 106-144
**constructor** notation
the "new" keyword and the object constructor create a blank object then you can add properties and methods to the object.

var hotel = **new** object();
### updating an object 
to update the value of peroperties, use dot notation or square brackets
### hotel.name = 'park';

to delete a property use the delete keyword
### delete hotel.name;

## many objects constructor notation
object constructers can use a function as a template for creating objects. 

tha name of a constructor being with a captail letter not like other functions

## this. \(its a keyword)
the keyword this is commonly used inside a function and objects. Where the function is declared alters what this means. it always refers to one object usually the object in which the function operates.

### arrays are objects
arrays are actually a special type of object
they hold a related key/value pair but the key for each value is its index number

## three groups of built in objects
* browser object model
* document object model
* global JS objects

global string objects
|PROPERTY | DESCRIPTION |
--- |---
length | Returns number of characters in the string in most cases (see note bottom-left)

| METHOD | DESCRIPTION
--- | ---
toUpperCase () | Changes string to uppercase characters 
tolowerCase ()  | Changes string to lowercase characters
charAt () | Takes an index number as a parameter, and returns the character found at that position
indexOf() | Returns index number of the first time a character or set of characters is found within the string
lastlndexOf() | Returns index number of the last time a character or set of characters is found within the string
substring() |  Returns characters found between two index numbers where the character for the first index number is included and the character for the last index number is not included
split()| When a character is specified, it splits the string each time it is found, then stores each individual part ih an array
trim() | Removes whitespace from start and end of string
replace() | Like find and replace, it takes one value that should be found, and another to replace it (by default, it only replaces the first match it finds)







# [Home](https://misalz.github.io/Reading-Notes)