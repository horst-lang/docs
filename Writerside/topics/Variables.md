# Variables

In Horst, Variables are defined using the let keyword. Defining a Variable looks like this:
```Javascript
let identifier = "value";
```
As Horst is dynamically typed, type annotations are not necessary. Variables can at any time be reassigned, with the type of the new value not really mattering too.
```Javascript
let x = "Hello, world!";

print x;

x = 50;

print x;

/*
Output:
> "Hello, world!"
> 50
*/
```
