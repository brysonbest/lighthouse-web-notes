## Arrow Functions!

New syntax for function declaration in ES6. 

Benefits:
* convenient for anonymous functions
* less code
* more efficient


However:
* arrow functions don't get assigned a value for ```this``` in the regular way a function might. 
* arrow functions will inherit the ```this``` value from the object they are internally referenced to.


### Example:

``` JavaScript
[1,2,3].forEach(num => console.log('num: ', num)); 
//prints 'num: 1 num: 2 num: 3'
```