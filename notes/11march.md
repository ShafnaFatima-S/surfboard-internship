## fill()
The array.fill() method is used to replace all the elements of an array with the specified value.

Example:
```
const a=[10,20,30]
a_fill=a.fill(2)
console.log(a_fill)
```
Output:
```
[ 2, 2, 2 ]
```
## CRUD
The crud operations are:
- CREATE
- READ
- UPDATE
- DELETE

With these operations we can create, take input, manipulate and delete objects.
### Create operation:
creating operations refers to creating a new object or adding a new property to the existing object. We can create object in two way

- **<ins>By creating object constructor**

It is a function to create and initialize an object. The return value is stored in a variable. The variable contains reference to the new object.

Example:
```
const details= new Object()
    details.name='shafna',
    details.age=21

console.log(details)
```
Output:
```
{ name: 'shafna', age: 21 }
```
- **<ins>By creating object literals**

It is a key-value pair separated by comma for creating an object.

Example:
```
const details={
    name:'shafna',
    age:21
}
console.log(details)
```
Output:
```
{ name: 'shafna', age: 21 }
```
### Read operation:
The read operation refers to accessing the properties and values of an object. We can access by,
- Destructuring Assignment

Example:
```
const details={
    name:'shafna',
    age:21
}
const {name}=details
console.log(name)
```
Output:
```
shafna
```
- Dot Notation

Example:
```
const details={
    name:'shafna',
    age:21
}
const Age=details.age
console.log(Age)
```
Output:
```
21
```
- Square brackets

Example:
```
const details={
    name:'shafna',
    age:21
}
const Age=details['age']
console.log(Age)
```
Output:
```
21
```
### Update operations
To update any value
- Dot Notation

Example:
```
const details={
    name:'shafna',
    age:21
}
details.name='fatima'

console.log(details['name'])
```
Output:
```
fatima
```
- Square brackets

Example:
```
const details={
    name:'shafna',
    age:21
}
details['age']=22

console.log(details.age)
```
Output:
```
22
```
### Delete operations
To delete any value
- Delete operator

Example:
```
const details={
    name:'shafna',
    age:21
}
details['city']='chennai'

delete details.name
console.log("After deletion= ",details)
```
Output:
```
After deletion=  { age: 21, city: 'chennai' }
```
- Destructuring assignment

Example:
```
const details={
    name:'shafna',
    age:21
}
details['city']='chennai'

const {name, ...new_details}=details
console.log("Original object= ",details)
console.log(new_details)

```
Output:
```
Original object=  { name: 'shafna', age: 21, city: 'chennai' }
{ age: 21, city: 'chennai' }
```
