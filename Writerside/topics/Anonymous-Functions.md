# Anonymous Functions

Apart from the way described before, there is a different way to declare functions in Horst: anonymous functions.
```Javascript
let f = fn(x) {
    print x;
}

f("foo");

/*
Output:
> "foo"
*/
```

These anonymous functions can also be used as Arguments, e.g. in other functions
```Javascript
fn f(h) {
    h();
}

f(fn() { print "hi"; });

/*
Output:
> "hi"
*/
```

Also, Horst supports closures. See this example I've stolen from the MDN web docs page about closures:
```Javascript
fn makeAdder(x) {
    return fn(y) {
        return x + y;
    };
}

let add5 = makeAdder(5);
let add10 = makeAdder(10);

print add5(2);
print add10(2);

/*
Output:
> 7
> 12
*/
```