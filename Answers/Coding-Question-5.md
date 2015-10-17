*Question: What is the outcome of the two alerts below?*
```javascript
var foo = "Hello";
(function() {
  var bar = " World";
  alert(foo + bar);
})();
alert(foo + bar);
```

The first alert will pop up and display the message "Hello World" however the second alert will run into a reference error and say bar is not defined because though foo is defined outside the function bar is only defined inside the function so definition of bar is out of scope for the second alert.