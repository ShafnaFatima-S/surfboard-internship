# Markdown
## Uses:
- Platform Independent
- Markdown is portable
- markdown can be used for creating websites, documents, notes, presentation and many others
- At times where other applications stops working, we can still use **markdown language**
## Symbols:
- " # " largest heading (h1 tag in html)
- " ## " second largest heading (h2 tag in html)
- " ### " Third largest heading (h3 tag in html)
- " ** bold ** " or " _ _ bold _ _ " To change to bold
- " * italic * " or " _ italics _" To change to italic
- " > " For quoted words
- " <ins>demo</ins> " For underlining
- " ~~Demo~~ " For striking through text
- Box around a text
  <table> <tr> <td>  text </tr> </td> </table> 
- hey " <sup>superscript</sup> " For superscript
- hello " <sub>subscript</sub> " For subscript
- For markdown table:

  For left-alignment use " :-- "
  
  For right-alignment use  " --: "
  
  For center-alignment use " :--: "

  | Column 1 | Column 2 | Column 3 |
  |:---------|:--------:|---------:|
  | Data 1   | Data 2   | Data 3   |
  | Data 4   | Data 5   | Data 6   |
### Images:
- For inline images use exclamatory mark (!) along with square brackets [ ] for the alternate text and paratheses() for image link

            " ! [alt text] (link) "
- Inline GIF:
 
    " ! [alt text] (link) "

# Array in JS

Array is a variable that can hold collection of values

## Array Methods:

- array.length() :
    
    returns the array length.
    
    example:
    ```
    let a=["hello","hi","hey"]
    let size=a.length;
    console.log(size)
    ```
    output:
    
    3
    
- array.toString():
    
    converts any array into strings of array value.
    
    example:
    ```
    let a=["hey","hello"]
    let b=a.toString()
    console.log(b)
    ```
    output:
    
    hey,hello
    
- array.splice():
    
    used to add new values in an array.
    
    example:
    ```
    let a=['apple','banana']
    let b=a.splice(1,0,'cherry','strawberry')
    console.log(a)
    ```
    output:
    
    [ 'apple', 'cherry', 'strawberry', 'banana' ]
    
- array.slice():
    
    It slices out a part of array into a new array. It doesn’t affect the original array.  
    
    example:
    ```
    let a=['apple','banana','cherry','strawberry']
    let b=a.slice(1)
    console.log(a)
    console.log(b)
    ```
    output:
    
    [ 'apple', 'banana', 'cherry', 'strawberry' ]

    [ 'banana', 'cherry', 'strawberry' ]
    
- array.join():
    
    It joins all array element into string and we can also add separators.
    
    example:
    ```
    let a=['apple','banana','cherry','strawberry']
    let b=a.join("-")
    console.log(b)
    ```
    output:
    
    apple-banana-cherry-strawberry
    
- array.push():
    
    used to add new element at the end of an array
    
    example:
    ```
    let a=['apple','banana','cherry','strawberry']
    a.push('kiwi')
    console.log(a)
    ```
    output:
    
    [ 'apple', 'banana', 'cherry', 'strawberry', 'kiwi' ]
    
- array.pop():
    
    used to remove an element from an array
    
    example:
    ```
    let a=['apple','banana','cherry','strawberry']
    a.pop()
    console.log(a)
    ```
    output:
    
    [ 'apple', 'banana', 'cherry' ]
    
- array.shift():
    
    used to remove an element from the beginning of an array
    
    example:
    ```
    let a=['apple','banana','cherry','strawberry']
    a.shift()
    console.log(a)
    ```
    output:
    
    [ 'banana', 'cherry', 'strawberry' ]
    
- array.flat():
    
    It creates an array using the sub-array elements
    
    example:
    ```
    let a=[[1,2],[3,4]]
    let b=a.flat()
    console.log(b)
    ```
    output:
    
    [ 1, 2, 3, 4 ]
    
- array.concat():
    
    creates new array by merging existing array
    
    example:
    ```
    let a=['shafna','fatima']
    let b=['hey','hello']
    let c=a.concat(b)
    console.log(c)
    ```
    output:
    
    [ 'shafna', 'fatima', 'hey', 'hello' ]
    

Difference between var, const, let

var - allows re-declaration as well as re-assigning

let- allows re-assigning but not re-declaration

const- doesn’t allow re-declaration as well as re-assigning

### Function:

A block of code to perform a particular task and executes when it is called

example:
```
function demo(a,b)
{
let c=a+b
console.log(c)
}
demo(2,3)
```
output:

5

### Class:
Class is the template for creating a object. Class is a collection of variables and methods. Use the class keyword to create a class.

Example:
```
class Person {
    constructor(name, age) {
        this.newname = name;
        this.newage = age;
    }
    func() {
        console.log('Hello, my name is '+this.newname+' and I am '+ this.newage, 'years old.');
    }
}
let p1 = new Person("shafna", 21);
p1.func();
```

Output:
Hello, my name is shafna and I am 21 years old.

In the above example constructor is a special method to create and initialize object instance of a class

#### array.map():

map() method is used to create  new array of values by calling a function for every array element. It returns a new array

Example:
```
let a=[1,2,3,4]
let b=console.log(a.map(fun))
function fun(n)
{
    return n+1
}

```
Output:
[ 2, 3, 4, 5 ]

#### array.forEach():

forEach() method is used to call a function for each element of an array. It doesn't create a new array.

Example:
```
let sum=0
let a_var=[11,22,33]
a_var.forEach(funct)
function funct(n){
    console.log(sum += n) 
}
```
Example:
11
33
66

#### array.find():

find() method returns the value of the first element that passes the test.

Example:
```
const age=[8,18,20,25]
function check(a){
    return a>18
}
console.log(age.find(check))
```
Output:
20

#### array.filter():

filter() method returns all the value that passes the test.
 
Example:
```
const age=[8,18,20,25]
function check(a){
    return a>18
}
console.log(age.filter(check))
```
Output:
[ 20, 25 ]

