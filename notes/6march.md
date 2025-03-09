## String Methods
### at()
returns the value present in that index.
Example:
```
const a="hello"
console.log(a.at(1))
```
Output:
```
e
```
### charAt()
This method returns the value present in the particular index.
Example:
```
const a="hello"
console.log(a.charAt(0))
```
Output:
```
h
```
### charCodeAt()
This method returns the ascii code for the index.
Example:
```
const a="Hello"
console.log(a.charCodeAt(3))
```
Output:
```
108
```
### Slice:
This method is used to extract a part of a string.
Example:
```
const str="Hello Everyone"
console.log(str.slice(0,5))
```
Output:
'''
Hello

### substring()
This method is also used to extract a part of a string.
Example:
```
const str="Hello Everyone"
console.log(str.substring(0,5))
```
Output:
```
Hello
```
### substr()
This method is similar to slice.
Example:
```
const str="Hellooo Everyone"
console.log(str.substr(0,4))
```
Output:
```
Hell

```
### toUpperCase()
This method is used to convert the string to uppercase.
Example:
```
const str="welcome home"
console.log(str.toUpperCase())
```
Output:
```
WELCOME HOME

```
### toLowerCase()
This method is used to convert the string to lowercase.
Example:
```
const str="HELLO"
console.log(str.toLowerCase())
```
Output:
```
hello
```
### concat()
This method is used to join two or more strings.
Example:
```
const str="HELLO"
const str1="hi"
console.log(str.concat(str1))
```
Output:
```
HELLOhi
```
### trim()
This method is used remove whitespace on both sides.
Example:
```
const str="  HELLO  "
console.log(str.trim())
```
Output:
```
HELLO
```
### trimEnd()
This method is used to remove whitespace on the end of the string.
Example:
```
const str="HELLO  "
console.log(str.trim())
```
Output:
```
HELLO
```
### trimStart()
This method is used to remove whitespace on the starting of the string.
Example:
```
const str="   HELLO"
console.log(str.trim())
```
Output:
```
HELLO
```
### padStart()
This method is used to pad a string to another string until it reaches a given length.
Example:
```
const str="HELLO"
console.log(str.padStart(8,'hii'))
```
Output:
```
hiiHELLO
```
### padEnd()
This method is used to pad a string to another string from end.
Example:
```
const str="HELLO"
console.log(str.padEnd(9,'hii'))
```
Output:
```
HELLOhiih
```
### toString()
This method is used to convert to a string.
Example:
```
const val=24
console.log(val.toString())
```
Output:
```
24
```
### repeat()
This method is used to create copies of a string.
Example:
```
const val="hi"
const a=val.repeat(2)
console.log(a)
```
Output:
```
hihi
```
### replace()
This method is used to replace a specified value with another.
Example:
```
const val="hi everyone"
console.log(val.replace("hi","hello"))
```
Output:
```
hello everyone
```
### replaceAll()
This method is used to replace a value with another wherever that word is found.
Example:
```
const val="hi everyone hi"
console.log(val.replaceAll("hi","hello"))
```
Output:
```
hello everyone hello

```
### split()
This method is used to convert a string into array.
Example:
```
const val="hi everyone hi"
console.log(val.split(" "))
```
Output:
```
[ 'hi', 'everyone', 'hi' ]

```