*Question: What is the value of `foo.x`?*
```javascript
var foo = {n: 1};
var bar = foo;
foo.x = foo = {n: 2};
```

foo.x is {n:2} because even though we set the var foo equal to {n:1} at first and in the final line the value of foo.x is set to foo we are also changing the value of foo to {n:2} in that line.