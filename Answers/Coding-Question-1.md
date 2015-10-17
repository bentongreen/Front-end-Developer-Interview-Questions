*Question: What is the value of `foo`?*
```javascript
var foo = 10 + '20';
```
The value of var foo after running the line var foo = 10 + '20'; is the string 1020 (also written as '1020' or "1020"), this happens because Javascript assumes that you are asking it to concatenate the number 10 with the string 20 and so if changes the type of 10 to a string from a number and then concatenates the two strings.