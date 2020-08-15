# 201 d66
# Read06.md
Reading notes and Repo updates from an aspiring WebDev.
![Type-copy](https://wtf.tw/ref/duckett.pdf)

### Reading06
### From the Duckett Js book:
###Chapter 3: “Object Literals” (pp.100-105)
Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object,
variables and functions take on new names. IN AN OBJECT: VARIABLES BECOME KNOWN AS PROPERTIES
If a variable is part of an object, it is called a property. Properties tell us about the object, such as
the name of a hotel or the number of rooms it has. Each individual hotel might have a different name and a different number of rooms.
#### FUNCTIONS, METHODS & OBJECTS IN AN OBJECT: FUNCTIONS BECOME KNOWN AS METHODS
If a function is part of an object, it is called a method.
Methods represent tasks that are associated with the object. For example, you can check how many rooms are available by subtracting the number of
booked rooms from the total number of rooms. Like variables and named functions, properties and methods have a name and a value. In an object,
that name is called a key. An object cannot have two keys with the same name. This is because keys are used to access their corresponding values.
The value of a property can be a string, number, Boolean, array, or even another object. The value of a method is always a function.
var hotel = { 
name : 1 Quay 1, 
romms: 40,
booked: 25,
gym: true,
roomTypes: ['twin, 'double', 'suite'],
checkAvailability: function() {
return this.rooms - this.booked;
}

###Chapter 5: “Document Object Model” (pp.183-242)
//note html:
var i = l ;
var msg = ' ' ;
II Set counter to 1
II Message
II Store 5 times tabl e in a variable
while (i < 10) {
msg += i + ' x 5 = ' + (i * 5) + '<br I>';
i++;
document .getEl ementByid( ' answer') . innerHTML = msg; 
//result: 
l x 5 = 5     
2 x s = 10
3 x 5 = 15 .
4 x 5 = 20
s x s = 25
6 x s = 30
7 x 5 = 35
8 x s = 40
9 x 5 = 45 

//note Js:
var i = l;
var msg : '';
do {
msg += i + ' x 5 = ' + (i * 5) + '<br I>' ;s
i++;
} 
while (i < 1);
document .getEl ementByld(' answer').innerHTML = msg; 
//result: 
1 x 5 = 5
Conditional statements allow your code to make decisions about what to do next.
Comparison operators (===, ! ==, ==, ! =, <, >, <=, =>) are used to compare two operands.
Logical operators allow you to combine more than one set of comparison operators.
if ... else statements allow you to run one set of code if a condition is true, and another if it is false.
switch statements allow you to compare a value against possible outcomes (and also provides a default option if none match).
Data types can be coerced from one type to another. 
All values evaluate to either truthy or falsy. 
There are three types of loop: for, while, and do ... while. Each repeats a set of statements. 





### Article: “6 Reasons for Pair Programming”
1. so you have extra eyes.
2. so you have extra hands.
3. so you have extra brains.
4. so theres a higher statistical chance you'll have some "sense" between the two assumed huemans. 
5. see reason 6.
6. see reason 1. (this is a loop and call back.HOLLAH!)

