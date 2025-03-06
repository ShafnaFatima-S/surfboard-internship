# Conditional Statements

Conditional statements allows you to execute a particular block of code based on the conditions. The block of code executes only when the condition is satisfied. If the condition is not satisfied then the statements inside the block will  be executed based on any other conditons provided. Conditional statements are:
- if statement
- if..else statement
- else if statement
- switch statement
- Ternary operator
- Nested if..else statement

### if Statement:
The if statement is used to check whether the condition is satisfied or not. If the condition is satisfied then the block of code will be executed.

<ins>Example:
```
const a='hello'
const b=prompt("Enter a word: ")
if(a!==b){
     console.log("Incorrect")
}
```
<ins>Output:
```
Enter a word: Pink
Incorrect
```
### if-else Statement:
The if-else statement is used to check whether the condition is satisfied or not. If the condition is satisfied then the statements inside the if block will be executed. If not, the statements inside the else block will be executed.

<ins>Example:
```
const a='hello'
const b=prompt("Enter a word: ")
const fun=(a1,b1)=>{
if(a1!==b1){
     return "The word did not match!"
}
else{
     return "The word is matched!"
}
}
console.log(fun(a,b))

```
<ins>Output:

<ins>True Response:
```
Enter a word: hello
The word is matched!
```
<ins>False Response:
```
Enter a word: hi
The word did not match!
```
### else if Statement:
The else if statement can be used in the situation where we need to mention another condition if the first condition is false. Here the condition inside the if statement is checked , if the condition is satisfied then the block inside the if statement is executed. If the condition inside the if statement is not satisfied then the else if block gets checked. If it satisfies the condition then the block of code inside the else if statement gets executed. If not, the block of code inside the else statement gets executed.

<ins>Example:
```
const age=18
const fun=(a)=>{
    if(a>18){
        return "The age is greater than 18"
    }
    else if(a==18){
        return "The age is equal to 18"
    }
    else{
        return "The age is not 18"
    }
}
const result=console.log(fun(age))
```
<ins>Output:
```
The age is equal to 18
```
### Switch Statement:
The switch expression is evaluated once, then the value of the expression is compared with all the test cases. If the value is matched then the code inside that case is executed. If the value is not matched the default block is executed.

<ins>Example:
```
let a="blue"
let b
switch(a)
{
    case a="blue":
        b="Blue color"
        break;
    case a="red":
        b="red color"
        break;
    default:
        b="no color"
        break;
}
console.log(b)
```
<ins>Output:

Blue color
### Ternary Operator:
The ternary operator is an alternate for if else statement. The ternary operator is " ?: ". If the condition is satisfied then the statement after the question mark gets executed. If not, the statement after the colon gets executed.

<ins>Example:
```
const age=20
const fun=(a)=>{
    return (a>=18)?"Eligible for vote":"Not eligible for vote"
}

const b=console.log(fun(age))
```
<ins>Output:

Eligible for vote
### Nested if else:
Here you can have if-else statement inside another if statement or else statement.
<ins>Example:
```
const i = 10;
if (i==10) {  
    if (i<15) {
        console.log("i is smaller than 15");
    }
        else{
            console.log("i is greater than 15");
    }
}
```
<ins>Output:

i is smaller than 15

# Looping Statements:
Loops are used to repeatedly execute a block of code as long as the condition is true.

### For Loop:
The for loop executes a block of code until the condition becomes false. It has initialization, condition, and increment/decrement.
<ins>Example:
```
for (let i=1; i<=3; i++) {
    console.log(i);
}
```
<ins>Output:
```
1
2
3
```
### While Loop:
The while loop executes as long as the conditon is true.
<ins>Example:
```
let i = 0;
while (i<=3) {
    console.log("Number:", i);
    i++;
}
```
<ins>Output:
```
Number: 0
Number: 1
Number: 2
Number: 3
```
### Do-While Loop:
The do-while loop executes as long as the condition is true, but it executes atleast once before checking the condition.
<ins>Example:
```
let i = 5;
do {
    console.log("Count:", i);
    i++;
} while (i>3 && i<=9);
```
<ins>Output:
```
Count: 5
Count: 6
Count: 7
Count: 8
Count: 9
```

