# Problem 1
```
let a = 5 ; 
console.log(a) 
const  a = 20  
console.log(a)  
What is the output of this ?
```
## Solution
Error. The variable a is already declared. It cannot be redeclared.
# Problem 2
 ```
 ;   let  const  a  ‘’  name  surfboard  =   ; 
 ```
Use these to frame a valid program.
	
## Solution
```
const name='surfboard';
let a=name;
console.log(a)
```
Output
```
surfboard
```
# Problem 3
```
let  a = 25 , b , d , c ;  
b = c = d = a ; 
What happens during lexical analysis of this program ?
```
## Solution
<ins>First Line:
```
let -> Keyword
a -> variable
= -> Assignment Operator
25 -> Literal
, -> Separator
b -> Variable
, -> Separator
d -> Variable
, -> Separator
c -> Variable
; -> Terminator (semicolon)
```
<ins>Second Line:
```
b -> Variable
= -> Assignment operator
c -> Variable
= -> Assignment operator
d -> Variable
= -> Assignment operator
a -> Variable
; -> Terminator (semicolon)
```
# Problem 4
```
let g , h , i , j ; 
let g = 5 ; 
h = 3 ; 
i = g ; 
console.log (g , h , i ) 
What is the output of this ? 
```
## Solution
```
Error. The variable g is already declared, cannot declare it again.
```
# Problem 5
Imagine a situation : You are asked to design a identity card for the employees of your company , you are told that identity card must contain the following properties like : 		
name , address , name_of_company , address_of_the_company , age ,gender ,  		blood_group .
You are asked to submit a sample design for the name Alice , whose age is 24 , her blood group is O+ , and address - Chennai , working in AB solutions , Chennai .
Represent the above details in form of object .
## Solution
```
const identity={
    name:"Alice",
    Age:24,
    Gender:"Female",
    Blood_Group:"O+",
    Address:"Chennai",
    Name_Of_Company:"AB Solutions",
    Address_Of_Company:"Chennai"
}
```
# Problem 6
What happens when the following code goes through the compiler . List down each steps .
```
const a ; 
a = 25 ;
```
## Solution
- The code is converted into tokens
- It throws syntax error because the const variable is not initialized when it is declared. So the execution is stopped.

# Problem 7
```
letgameplayer 
gamecricketplayersachin 
playerdravid 
```
Use relevant punctuations in relevant places
## Solution
```
let gameplayer;
let game="cricket";
let player=["sachin","dravid"]
```
# Problem 8
```
let a = 5 ; 
let b = c = d = a ; 
c = 20 ; 
b = 25 
Is there any error in this program ? If yes - What is it ? , If No 
What are the values in a , b , c , d ?
```
## Solution
```
a=5
b=25
c=20
d=5
```
# Problem 9
variabi2abi

Use relevant punctuations in relevant places
## Solution
```
var i="abi2abi";
```
# Problem 10
```
identifier_keyword  identifier_name punctuator identifier_name   
assignment_operator value statement_terminator
Write an expression using this syntax and state if there is error in it ?
```
## Solution
let a=b=5;
# Problem 11
identifier_keyword identifier_name assignment_operator punctuator key punctuator value separator key punctuator value separator key  punctuator value separator key punctuator value separator key punctuator value punctuator statement_terminator 

Write an expression using this syntax and state if there is error in it. 
## Solution
```
const details={
    name:"abc",
    age:21,
    address:"chennai",
    id:1,
    blood_group:"O+"
};
```
# Problem 12
```
letaconstb5a7letcdec1d2e3
Use relevant punctuations in relevant places
```
## Solution
```
let a;
const b=5,a7;
let c="dec1d2e3";
```
# Problem 13
Represent the following statement in form of JavaScript code ( follow the proper grammar )
	
Assign the name of the company ( Surfboard ) to an identifier so that it cannot be changed in any future instance in the code .
## Solution
```
const name="surfboard";
```
# Problem 14
constab:3d:kinny

Use relevant punctuations in relevant places

## Solution
```
const ab="3d:Kinny";
```
# Problem 15
```
let name = 200 ; 
let num = ‘200’ ; 
num = 200 ; 
name = ‘200’ ; 
```
What happens during lexical analysis and syntax analysis of this program ?
## Solution
<ins>Lexical Analysis of First line:
- let -> Keyword
- name -> variable
- = -> Assignment operator
- 200 -> Value
- ; -> Terminator

<ins>Lexical Analysis of Second line:
- let -> Keyword
- num -> variable
- = -> Assignment operator
- 200 -> Value
- ; -> Terminator

<ins>Lexical Analysis of Third line:
- num -> Variable
- = -> Assignment operator
- 200 -> Value
- ; -> Terminator

<ins>Lexical Analysis of Fourth line:
- name -> Variable
- = -> Assignment operator
- 200 -> Value
- ; -> Terminator

The above code is syntactically correct because let keyword allows us to re-assign values.
# Problem 16
```
const book = { 
name : ‘ Extreme Ownership’ , 
Author : ‘Jocko Willink’  
} 
```
How do you access the value of name of object book ?
How do you add a new property  no_of_pages with value 322 ?
## Solution
Access the value with dot operator.
```
console.log(book.name)
```
Add new property using dot operator.
```
book.no_of_pages=322
```
# Problem 17
Represent the following statement in form of JavaScript code ( follow the proper grammar )
Assign any value to an identifier , declare a new identifier , assign a new value to the newly declared identifier , now re - assign the value of the identifier declared initially with any	other new value .
## Solution
```
let a=5;
let b;
b=10;
a=15;
```
# Problem 18
let   ,  {  }  =  :  ‘’  0 - 9  a - z  ;  

Write a program which will use all these symbols .  Symbols are repeatable .
## Solution
```
const names = {
  name1: 'Jack',
  name2: 'John'
};
```
# Problem 19
Represent the following statement in form of JavaScript code ( follow the proper grammar ).
Assign 5 to a variable - 1 , 10 to a variable - 2 , reassign variable - 2 as 20 , declare a new variable , assign the sum of variable - 1 and variable - 2 to the new variable.
## Solution
```
let v1=5
let v2=10
v2=20
let sum=console.log(v1+v2)
```
# Problem 20
```
const name = { 
first_Name : ‘Marwah’ , 
last_Name : ‘Ford’ , 
}; 
 ```
What happens during lexical analysis of this program ?
## Solution
- const -> Keyword
- name -> Variable
- = -> Assignment operator
- { -> Punctuation(opening braces)
- first_name -> Variable
- : -> Punctuation(Colon)
- 'Marwah' -> String 
- , -> Separator
- last_name -> Variable
- : -> Punctuation(colon)
- 'Ford' -> String
- } -> Punctuation(closing braces)
- ; -> Terminator

# Problem 21
```
let p = 20 ; 
let q = r = s = p ; 
p = 10 ; 
r = 30 ; 
s = r = 40 ; 
``` 
 What happens during lexical analysis ?
 Does this code have error ? If yes - what is it ? If No - what is the end value of p,q,r,s ?
## Solution
<ins>Lexical analysis of first line:
- let -> Keyword
- p -> Variable
- = -> Assignment operator
- 20 -> Value
- ; -> Terminator

<ins>Lexical analysis of second line:
- let -> Keyword
- q -> Variable
- = -> Assignment operator
- r -> Variable
- = -> Assignment operator
- s -> Variable
- = -> Assignment operator
- p -> Variable
- ; -> Terminator

<ins>Lexical analysis of third line:
- p -> Variable
- = -> Assignment operator
- 10 -> Value
- ; -> Terminator

<ins>Lexical analysis of fourth line:
- r -> Variable
- = -> Assignment operator
- 30 -> Value
- ; -> Terminator

<ins>Lexical analysis of fifth line:
- s -> Variable
- = -> Assignment operator
- r -> Variable
- = -> Assignment operator
- 40 -> Value
- ; -> Terminator

Output:
```
p=10
q=20
r=40
s=40
```
# Problem 22
```
let  
  a   , 
 b ; 
 b  
                    =               34 ; 
 a   
                           =             
              
 b           ;   
        console.log( a , b ) 
```
Will this code run ? If yes - What is output ?  (  console.log ( ) is used to print ( display ) the value inside it )

## Solution
```
a=34
b=34
```
# Problem 23
```
let laptop = { 
RAM : ‘8 GB’, 
storage : ‘ 1 TB’ , 
colour : ‘Silver’ , 
OS : ‘Mac OS ’ , 
owner : ‘Kaydan’ 
      }; 
Write code to - 
Add a new property - Model with value - MacBook 
Delete the property owner 
Change the colour to Gold
```
## Solution
```
let laptop = { 
RAM : '8 GB', 
storage : '1 TB' , 
colour : 'Silver' , 
OS : 'Mac OS' , 
owner : 'Kaydan' 
      }; 
laptop.Model='MacBook';
let {owner, ...newlaptop}=laptop
newlaptop.colour='Gold';
console.log(newlaptop)
```
Output:
```
{
  RAM: '8 GB',
  storage: '1 TB',
  colour: 'Gold',
  OS: 'Mac OS',
  Model: 'MacBook'
}
```
# Problem 24
```
const paint = { 
 color1 : ‘red’, 
 color2 : ‘yellow’, 
 brand_options : { 
   ‘ 1 ’ : ‘Nippon’, 
   ‘ 2 ’ : ‘Asian’, 
   ‘ 3 ’ : ‘Berger’ 
   } 
 }; 
	
Is this valid ? If No - What is the error ?
```
## Solution
```
{
  color1: 'red',
  color2: 'yellow',
  brand_options: { ' 1 ': 'Nippon', ' 2 ': 'Asian', ' 3 ': 'Berger' }
}
```