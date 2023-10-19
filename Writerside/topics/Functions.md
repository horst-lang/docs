# Functions

Functions are typically declared usign the fn keyword, followed by an identifier, the function arguments seperated by commas, wrapped in parentheses. The declaration of a function looks something like this:
```Javascript
fn identifier(argument1, argument2, ...) {
    // Code
}
```
Functions can then be called by simply writing the identifier, followed by the arguments.

```Javascript
fn f(x, y) {
    print x;
    print y;
}

f("foo", "bar");

/*
Output:
> "foo"
> "bar"
*/
```

Variables declared in a function can only be accessed inside the same block as they were declared in
```
fn f() {
    let x = 5;
    print x; // > 5
}

print x; // > Error: Variable doesn't exist here
```