# Markdown

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
Output:
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

