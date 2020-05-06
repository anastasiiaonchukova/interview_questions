Javascript questions

Scopes

1. Temporary Dead Zone 
2. Can we redeclare var/let/const. e.g. 
```
let baz = 'baz';
let baz = 'qux'; 
```
3. Cand we call function before it declaration, e.g
```
 foo();
 function foo(){};
 var foo=function(){};
```
4.
```
function saySomething() {
    var greeting = "Hello";
    {
        greeting = "Howdy";   
        let greeting = "Hi";
        console.log(greeting);
    }
}

saySomething();
```

Performance

1. Why it is bad to have undeclared variables
2. 
