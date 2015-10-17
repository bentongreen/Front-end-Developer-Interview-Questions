*Question: What does the following code print?*
```javascript
console.log('one');
setTimeout(function() {
  console.log('two');
}, 0);
console.log('three');
```

The code prints out 
"one
three
undefined
two"
this is because it goes through and logs the first string but then runs a timeout on a function that contains the log of the string two and even though that timeout is set to 0 it still has to "stop and wait for 0 miliseconds" which means the log of "three" runs and the the nonexisent timeout finishes so the function (that does not have a return value) runs thereby returning undefined and logging out the string "two"