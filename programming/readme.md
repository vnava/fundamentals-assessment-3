#Fundamentals Assessment 3

## emptyFunc 
* [ ] create a function "emptyFunc" that takes in no arguments, and contains an empty block of code. This function is the bare bones of all function declarations, and therefore can still be properly invoked (it just won't do anything at all).

If you invoked emptyFunc :
```Javascript
emptyFunc(); // undefined
```

-

## myProfile 
**Part 1 of 2**
* [ ] create an object called "myProfile" which has the following properties:

_Populate each value with whatever you would like, so long as it adheres to the type_
  * [ ] "name" with a `string` value
  * [ ] "age" with a `number` value
  * [ ] "knowsJavascript" with a `boolean` value
  * [ ] "pets" with an `array` value

## printProfile 
**Part 2 of 2**
* [ ] create a function called "printProfile" that logs each property and value of `myProfile` in Part 1 of this exercise.

_This assumes that `myProfile` was created correctly_

Example :
```Javascript
printProfile(myProfile);
/* Result :
name : "Beyonce"
age : 35
knowsJavascript : true
pets : ["Munchie"]
*/
```
-

## sumOf
* [ ] create a function "sumOf" that takes in an array of numbers, and logs the number of elements in the array and the total sum.

Example:
```Javascript
sumOf([1,2,3,4,5]); //"5 elements. Sum : 15"
```
-

## coinFlip
* [ ] create a function "coinFlip" that randomly returns either "heads" or "tails". Each outcome should have an equal chance of happening. 
_Hint: `Math.random()`_

-

## everyOther
* [ ] create a function "everyOther" that takes in an array, and returns an array with every other value from the previous array starting with the first.

Example : 
```Javascript
var myArray = [1,'a',2,'b',3,'c',4,'d',5,'e'];
var newArray = everyOther(myArray); //[1,2,3,4,5]
```
-
