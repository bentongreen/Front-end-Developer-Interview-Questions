*Question: What is the value of `window.foo`?*
```javascript
( window.foo || ( window.foo = "bar" ) );
```
The value of window.foo is "bar" because when you run the line of code it can either be window.foo which will return undefined, or it can be defined as "bar" so in the case of this || statment javascript with "choose" to run the option that doesn't return undefined.