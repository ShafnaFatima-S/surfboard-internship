## Callback function:
Callback function is a function that is passed as an argument to another function. Callback function works after another function is finished.

Example:
```
const val1=10
const val2=10
function demo(a,b,callback){
    const sum=a+b
    console.log("sum="+sum)
    callback(val1,val2)
    
}
function mul(c,d){
    const mul=c*d
    console.log("mul="+mul)
    
}
demo(val1,val2,mul)
```
Output:
```
sum=20
mul=100
```
## Using setTimeout():
The setTimeout() takes the callback function as argument and executes it after the specified time.
Example:
```
const val1=10
const val2=10
function demo(a,b,callback){
    const sum=a+b
    console.log("sum="+sum)
    setTimeout(callback,2000,val1,val2)
    
}
function mul(c,d){
    const mul=c*d
    console.log("mul="+mul)
    
}
demo(val1,val2,mul)
```
Output:
```
sum=20
mul=100
```
- Here the mul function executes after 2 seconds.
#### Json.parse()
It converts a string into json.
Example:
```
const details='{"name":"shafna","age":21}'
console.log(JSON.parse(details))
```
Output:
```
{ name: 'shafna', age: 21 }
```
#### JSON.stringify()
It converts JS object to a json string.
Example:
```
const details={name:"shafna",age:21}
console.log(JSON.stringify(details))
```
Output:
```
{"name":"shafna","age":21}
```
#### parseFloat()
It converts string to a floating point number.
Example:
```
const a="10.7"
console.log(parseFloat(a))
```
Output:
```
10.7
```
#### parseInt()
It converts a string to a number.
Example:
```
const a="10.7"
console.log(parseInt(a))
```
Output:
```
10
```
#### Math.floor()
It returns the value rounded down to the nearest integer.
Example:
```
const a=10.7
console.log(Math.floor(a))
const b=10.1
console.log(Math.floor(b))
```
Output:
```
10
10

```
#### Math.random()
It returns a random number between 0 and 1.
Example:
```
console.log(Math.random())
console.log(Math.random()*10) 
```
Output:
```
0.9444314163765459
5.380025104122293
```
#### Math.round()
It rounds to the nearest integer.
Example:
```
const a=10.7
console.log(Math.round(a))
const b=10.1
console.log(Math.round(b))
```
Output:
```
11
10

```
#### Math.ceil()
It rounds a number up to the nearest number.
Example:
```
const a=10.7
console.log(Math.ceil(a))
const b=10.1
console.log(Math.ceil(b))
```
Output:
```
11
11
```
#### promise
An object that acts as a placeholder for the result. A promise is created using the new promise constructor, which takes two parameters: resolve and reject. JS promise make handling asynchronous operations like API calls, file loading, or time delays easier.
##### promise.all()
Resolves when all promise resolve, rejects if any fails.
##### promise.allSettled()
Returns result of all promises whether resolved or rejected.
#### Async
Async ensures that the execution is not blocked. Async functions always return a promise.
#### Await
The await keyword is used to wait for a promise to resolve. It can only be used within an async . Await makes the code wait until the promise returns a result.
#### then()
The then() method in JavaScript is used with promises to handle asynchronous operations. It accepts two callback functions: one for handling a promise’s resolved value and one for handling its rejection.
#### catch()
The catch() method is called whenever a promise is rejected.This method is used for error handling. This method is used after .then
