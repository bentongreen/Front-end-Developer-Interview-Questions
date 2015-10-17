* What is the difference between `==` and `===`?

== is loose equality mean that the two compared items only need to be the same after being converted to a type. === is strict equality meaning that the two items need to be equal AND of the same time. 

3 == '3' //true
3 == 3 //true

3 === '3' //false
3 === 3 //true