#JavaScript Tutorial 2
#Author: Allie Miranda

1) Let's talk about variables!
   Variables are data types given certain names.
   Think about people: one particular person, has a name.
   Data Type: Person; Variable name: Person's name.
   There are different types of variables and different data types.

First, I will walk you through the "basic" data types:

2) Integers: these are whole numbers
   1 is an integer, 2.3 is not.
   1000000 is an integer, 2082487.0 is not.
   Yes, regardless of what comes after the decimal point, if it has one its not an integer.

3) Doubles/Floats: numbers with a decimal point in it.
   1.5 is a double, so is .6, 8.0999
   Pretty simple, if its got a decimal point, its a double/float
   ***Important*** Keep not of the differences between doubles and floats when doing arithmetic.
   For example: if you multiply a float and an integer the result will be a float.
   The same goes for division, addition, etc.
   If you divide and integer by another, it will result in a float in JS.
   ***Note:***  Doubles and floats ARE different in terms of how they are stored.
   This is a distinction that is not important right now.

4) Characters:

5) Booleans: this is a truth value
   Can either be True or False.
   This can be written in many ways.
   One way to write a bool (which is what they are normally called) is to just write true or false
   Another way is to write truth statements.  For example: 3<4 is true, but 3>4 is false.
   *Truth Statements* are statements with a truth value.  "Is it raining?" is not a truth statement.
   However, "It is raining" is a truth statement, it is either true or false.

Those are your basic data types. Integers, doubles and booleans are all *primitive* data types.
Primitive data types are the most basic form of data types.
There are many more of these, but for now, these are the ones that beginners need.

Now, we will talk about an important abstract data type:

6) Strings: characters within "" or ''
   "Hello World!" is a string, Hello World! is not.
   "3" is a string and 3 is an integer.
   There are many fun things you can do with strings.
   For instance, type the following into your .js file:
   document.write("Hello World!".length);
   What do you think this will do? Run it and see!
   This data type is internally stored differently than the others.

The difference between "abstract" and "primitive":
Primitive data types are the base for most abstract data types.
Primitive data types typically make up abstract data types.
For example: internally, strings are stored as a "list" of chars.

Here is a small project:
Let's work with the data types we have talked about.

Think about the following code snippets -
What do you think they will do?  Why?
Run them, see if you were right.
a) document.write(Number.isInteger(5));

b) document.write(Number.isInteger("5"));

c) document.write(3 === 4)

d) document.write(3 <= 4)

Think about what you can do with just these pieces.
You can print your essay to a console, you can do math!
It may not seem like much, but its these pieces of computer science that create entire programs and games!

**Note: Make sure to check out tut2.html**
