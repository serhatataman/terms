# Java terms


1) code that always executes based on the main method, moving from top to bottom- this is called "procedural programming".
2) to define new entities in Java that can interact with one another, this is called "object oriented programming".
3) Primitives are stored directly in memory, so when you copy a primitive variable the value is copied, leaving the original variable unaffected. This is called value semantics.
4) Since objects are more complicated Java doesn't store their data directly in memory with the variable name, instead it creates a special space in memory for the data and then stores the address of that location in the variable. This means that any variable holding an object (like an array) actually stores a reference to the object. Therefore, when you make a copy of an object variable, you copy the reference, which still points at the original data. This is called reference semantics

5) An object is combination of "state" and "behaviour". (for example; state=variables, behaviour=methods)
6) Client class is where the main() method is; Object class is every class without main() method

*Primitives vs Objects
In Java there are two general types of data: primitives and Objects

*Primitives
Aspects of primitive data:

when working with primitive data types Java stores them directly in memory
when you copy a primitive variable, only the data is copied, creating a separate variable that holds the same value
when working with primitives you can use mathematical operators to perform direct calculations like +, -, / and *
you can use shortcuts to update the value of a primitive value like ++, -- or +=

*Objects
Aspects of Object data:

an object is a method of storing multiple pieces of data and the methods who act on this data under a single data type
this means within a single object you could have multiple pieces of data including both primitives and other objects
because objects have the potential to store large amounts of data Java stores them in memory differently from primitives, storing the location for the data in the actual variable as a "reference"
when you are working with Objects you can't use the mathematical operators or shortcuts, instead you need to rely upon the methods provided by the object like "string".equals("string") or scanner.nextInt()

*Null
Each primitive has its own associated "zero value". This is a value that java uses as a stand in when creating a place in memory for a primitive before you actually give it a value to store.

All object types share a single "zero value"- null
Null means literally "no object", which is different from an empty object. For example, if you try to use the String's lengh method on a null string you get an error. However, calling length on an empty string is perfectly valid.
