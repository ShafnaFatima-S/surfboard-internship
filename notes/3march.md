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

<!-- .fle to save -->