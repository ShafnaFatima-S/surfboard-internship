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
- **bold**
- *italic*
- > quoted
- <ins>demo msg 
- ~~Demo~~
- <table><tr><td>Text</tr></td></table>
- hey <sup>superscript</sup>
- hello <sub>subscript</sub>


# Array in JS

Array is a variable that can hold collection of values

## Array Methods:

- array.length() :
    
    returns the array length.
    
    example:
    
    var a=["hello","hi","hey"]
    var size=a.length;
    console.log(size)
    
    output:
    
    3
    
- array.toString():
    
    converts any array into strings of array value.
    
    example:
    
    var a=["hey","hello"]
    var b=a.toString()
    console.log(b)
    
    output:
    
    hey,hello
    
- array.splice():
    
    used to add new values in an array.
    
    example:
    
    var a=['apple','banana']
    var b=a.splice(1,0,'cherry','strawberry')
    console.log(a)
    
    output:
    
    [ 'apple', 'cherry', 'strawberry', 'banana' ]
    
- array.slice():
    
    It slices out a part of array into a new array. It doesn’t affect the original array.  
    
    example:
    
    var a=['apple','banana','cherry','strawberry']
    var b=a.slice(1)
    console.log(a)
    console.log(b)
    
    output:
    
    [ 'apple', 'banana', 'cherry', 'strawberry' ]
    [ 'banana', 'cherry', 'strawberry' ]
    
- array.join():
    
    It joins all array element into string and we can also add separators.
    
    example:
    
    var a=['apple','banana','cherry','strawberry']
    var b=a.join("-")
    console.log(b)
    
    output:
    
    apple-banana-cherry-strawberry
    
- array.push():
    
    used to add new element at the end of an array
    
    example:
    
    var a=['apple','banana','cherry','strawberry']
    a.push('kiwi')
    console.log(a)
    
    output:
    
    [ 'apple', 'banana', 'cherry', 'strawberry', 'kiwi' ]
    
- array.pop():
    
    used to remove an element from an array
    
    example:
    
    var a=['apple','banana','cherry','strawberry']
    a.pop()
    console.log(a)
    
    output:
    
    [ 'apple', 'banana', 'cherry' ]
    
- array.shift():
    
    used to remove an element from the beginning of an array
    
    example:
    
    var a=['apple','banana','cherry','strawberry']
    a.shift()
    console.log(a)
    
    output:
    
    [ 'banana', 'cherry', 'strawberry' ]
    
- array.flat():
    
    It creates an array using the sub-array elements
    
    example:
    
    var a=[[1,2],[3,4]]
    var b=a.flat()
    console.log(b)
    
    output:
    
    [ 1, 2, 3, 4 ]
    
- array.concat():
    
    creates new array by merging existing array
    
    example:
    
    var a=['shafna','fatima']
    var b=['hey','hello']
    var c=a.concat(b)
    console.log(c)
    
    output:
    
    [ 'shafna', 'fatima', 'hey', 'hello' ]
    

Difference between var, const, let

var - allows re-declaration as well as re-assigning

let- allows re-assigning but not re-declaration

const- doesn’t allow re-declaration as well as re-assigning

Function:

A block of code to perform a particular task and executes when it is called

example:

function demo(a,b)
{
var c=a+b
console.log(c)
}
demo(2,3)

output:

5