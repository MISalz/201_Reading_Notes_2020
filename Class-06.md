# Class 06 Notes
## Michelle Salazar

## Function  

* store  steps needed to achieve a task
***If your going to perform  the function later you need to name the function.  This is called “calling” a function.***

When you write a function and you expect it to provide. You an answer the response is known as return value.

## Declaring a function
Function functionname(){this is code lock between curly brackets}

## Declaring function
Function functtionname(parameter1, parameter2){
Return para1*para2;
}

## Single value from function
Function functtionname(parameter1, parameter2){
Return para1*para2;
}
Var calcul = functionname(parameter1,parameter2);

## Named function 
Function functionname (){}
Anonymous function
Function(){}

## Object has variables called properties (literal notation)
Var hotel ={Name:’hilton’, rooms:40, booked:’25’;
}
**Property =key =value**

### Accessing an object and dot notation
Var hotelname = hotel.name;


## Create a object(constructor notation) pg 106
Th new keyword and the object constructor create a blank object

# DOM tree pg 187

### DOM manipulation (adding) 222
CreateElement()
CreateTextNode()
Appendchild()

### (removing) 224
Remove
Container =remove parent
Container=removechild

**Examine the DOM in chrome pg 236**

Chp 3 100-105
## Object
Objects grouop together a set of variables  and functions to create a model

If a variable is part of an object it is known as a **property**
	* Properties tell us about the object
If a function is part of an object its called a **method**
	* Methods represent tasks that are associate with the object
Variables with a name an a value inside an object are called a **Key**
An object cannot have two keys with same name. 
The value  of a property can be any value type
## Literal Notation
 is the easiest way to creat objects
All keys have actual values
## Dot Notation
You can access the properties or methods of an object using dot notation
You access a property or method of an object by using the name of the object followed by a period then the name of the property. The period is known as the **member operator**.
	Var hotelName =hotel.name;
	Car roomsFree = hotel.checkAvailability();
You can also access properties using square brackets
	Var hotelName = hotel['name']

Chp 5 183-242
## DOM Document object Model
Some people call the DOM application programming interface **(API)**


Each node is an object with methods and properties.
Scripts access and update this DOM tree 

* Document Node
* Element Nodes
* Attribute Nodes
* Text Nodes


# [Home](https://misalz.github.io/Reading-Notes)