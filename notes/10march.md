## reduce()
The array.reduce() method is used to iterate over an array. It applies function to each element of an array resulting in a single output value. It takes an initial value processing elements from left to right, reducing the array to a single value output. 

Example:
```
const a=[10,20,30]
let sum=a.reduce((e,i)=> e*i,1)
console.log(sum)
```
Output:
```
6000
```
In the above example variable 'e' denotes the total value, 'i' denotes the element in the array, '1' denotes the initial value.
## reverse()
The array.reverse() method is used to reverse the order of an array.

Example:
```
const a=[10,20,30]
const rev=a.reverse()
console.log(rev)
```
Output:
```
[ 30, 20, 10 ]
```
