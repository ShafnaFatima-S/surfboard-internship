# Problem 1
Declare a function to multiply two numbers and execute it .
## Solution
```
function mul(a,b){
    let c=a*b;
    return c;
}
console.log('The product is:',mul(2,5))
```
<ins>Output:

The product is: 10
# Problem 2
Use these symbols to write a valid code . Symbols are not repeatable .
```
)  ‘  =  (  ;  {  }  ’  ) ; ( ;
```
Use any number of identifiers — to arrive at a valid code.
```
let a={name:'shafna'};
console.log(a);
```
# Problem 3
```
function division (dividend , divisor ){ 
   
  let quotient = dividend / divisor ; 
  let remainder = dividend % divisor ; 
   
  return quotient ; 
 }; 
 ```
Write execution statement for this expression and explain how your computer processes this step-by-step. 

 Execution statement:
 ```
 console.log(division(15,5))
 ```
 The function is called inside the print statement. It takes 2 arguments and these arguments are passed onto the 2 parameters (dividend, divisor). The variable quotient stores the value for the division operation . The variable
 remainder stores the value for the modulus operation. Then the quotient value is returned.
# Problem 4
```
function  sentence(a, b, c, d){
      finalSentence = a + ' ' +b + ' ' +    c + ' ' +   d ; 
      return finalSentence 
 }; 
  let k = 'your'; 
  let g = 'Frame' ; 
  let l = 'own' ; 
  let h = ‘a'; 
  let i = 'sentence'; 
  let j = 'on' ; 
   
 sentence(g, h, i, j, k, l); 
 ```
 Is this expression valid ? If Yes what is the output ? If No - Correct the error and find the  output.
## Solution
```
function  sentence(a, b, c, d,e,f){
      finalSentence = a+' '+b+' ' +c+' '+d+' '+e+' '+f ; 
      return finalSentence 
 }; 
  let k = 'your'; 
  let g = 'Frame' ; 
  let l = 'own' ; 
  let h = 'a'; 
  let i = 'sentence'; 
  let j = 'on' ; 
   
 console.log(sentence(g, h, i, j, k, l)); 
 ```
 Output:
 ```
 Frame a sentence on your own
```
# Problem 5
```
const myDetails = function(name , college , institution, review) {
   
  const info = ‘My name is ’ + name + ‘ I did my college in ’   
     + college ; 
  const presentStatus = ‘ I am doing my internship in ’ +institution ; 
   
  const internReview = ‘ I find this internship very ’ + review ; 
  return info + presentStatus + internReview 
  } ; 
  
 myDetails( ____ , _____ , _____ , _____ ) ; 
 
```
Does this expression have error ? If yes - state the error ? If No  find a output .
## Solution
```
const myDetails = function(name , college , institution, review) {
   
  const info = 'My name is ' + name +' I did my college in '   
     + college ; 
  const presentStatus = ' I am doing my internship in ' +institution ; 
   
  const internReview = ' I find this internship very ' + review ; 
  return info + presentStatus + internReview 
  } ; 
  
 console.log(myDetails('Shafna', 'IJCASW','Surfboard','useful')) ; 
 ```
 Output:
 ```
My name is Shafna I did my college in IJCASW I am doing my internship in Surfboard I find this internship very useful
 ```
# Problem 6
```
function mathematicalOperation = ( a , b )  { 
  let sum = a + b ; 
  let subtract = a - b ; 
  let multiplication = a * b ; 
  let division = a / b ; 
  let square1 = a * a ; 
  let square2 = b * b ; 
  let sumAll = sum + subtract + multiplication + division +   
     square1 + square2 ; 
  let operations = { 
   sum : sum , 
   subtract : subtract ,  
   multiplication : multiplication, 
   division : division , 
   square1 : square1, 
   square2 : square2, 
   sumAll : sumAll, 
  } 
  return operations; 
  
  } 
 mathematicalOperation(2,4);
 ```
Is this expression valid ? If Yes what is the output ? If No - Correct the error and find the  output. 
## Solution
```
function mathematicalOperation( a , b )  { 
  let sum = a + b ; 
  let subtract = a - b ; 
  let multiplication = a * b ; 
  let division = a / b ; 
  let square1 = a * a ; 
  let square2 = b * b ; 
  let sumAll = sum + subtract + multiplication + division +   
     square1 + square2 ; 
  let operations = { 
   sum : sum , 
   subtract : subtract ,  
   multiplication : multiplication, 
   division : division , 
   square1 : square1, 
   square2 : square2, 
   sumAll : sumAll, 
  } 
  return operations; 
  
  } 
 console.log(mathematicalOperation(2,4));
 ```
 Output:
 ```
 {
  sum: 6,
  subtract: -2,
  multiplication: 8,
  division: 0.5,
  square1: 4,
  square2: 16,
  sumAll: 32.5
}
```
# Problem 7
Class teacher of 10 : C , wanted marks scored by  her class students in different subjects to be expressed in form of single variable. Can you help her in doing it .

		Class 10 C 
		Maths - 89 , 90 , 97 , 45, 72 , 80 , 76 .
		Science - 93 , 88 , 83 , 54 , 65 , 77 , 70 .
		Social Science - 85 , 94 , 87 , 40 , 69 , 70 , 81 .
		English - 88 , 84 , 89 , 60 , 79 , 83 , 81 .
		Language - 84,87 , 92 , 73 , 80 , 79 , 84 .
## Solution
```
const Marks = {
  maths: [89,90,97,45,72,80,76],
  science: [93,88,83,54,65,77,70],
  socialScience: [85,94,87,40,69,70,81],
  english: [88,84,89,60,79,83,81],
  language: [84,87,92,73,80,79,84]
}
```
# Problem 8
Can this block of elements be represented in the form of an array . Is yes create an array with all these elements .
## Solution
```
const elements=[5,'internship',{fruit:'apple',color:'red'},true,[3,4,15,16,18],"23lock",function add(a,b){
    return a+b
}]
```
# Problem 9
```
 let teamDetails = { 
       batsmen : 5 , 
       bowlers : 5 , 
       allRounders : 1 , 
       subs : 4 ,  
  }; 
 function teamInfo( a, b, c){ 
      a.players = b; 
      a.order = c ; 
      return a; 
 }; 
 let players11 = [ 'Sachin' , 'Sehwag' , 'Gambhir' , 'Dravid' ,   
   'Ganguly' , 'Yuvraj' , 'Harbhajan' , 'Zaheer' ,    
   'Nehra' , 'Kumble' , 'Irfan' ]; 
 let battingOrder = { 
       '1' : 'Sehwag', 
       '2' : 'Gambhir', 
       '3' : 'Sachin', 
       '4' : 'Dravid', 
       '5' : 'Ganguly', 
       '6' : 'Yuvraj', 
       '7' : 'Irfan', 
       '8' : 'Harbhajan', 
       '9' : 'Kumble', 
       '10': 'Zaheer', 
       '11': 'Nehra', 
 }; 
 teamInfo( teamDetails, players11 , battingOrder); 
 ```
 What happens during lexical Analysis ?Is this a valid program ? If Yes - What is the output ? If No - State the error.
## Solution
```
{
  batsmen: 5,
  bowlers: 5,
  allRounders: 1,
  subs: 4,
  players: [
    'Sachin',    'Sehwag',
    'Gambhir',   'Dravid',
    'Ganguly',   'Yuvraj',
    'Harbhajan', 'Zaheer',
    'Nehra',     'Kumble',
    'Irfan'
  ],
  order: {
    '1': 'Sehwag',
    '2': 'Gambhir',
    '3': 'Sachin',
    '4': 'Dravid',
    '5': 'Ganguly',
    '6': 'Yuvraj',
    '7': 'Irfan',
    '8': 'Harbhajan',
    '9': 'Kumble',
    '10': 'Zaheer',
    '11': 'Nehra'
  }
}
```
# Problem 10
```
 const groceryList = { 
      tomato : '1 kg' , 
      potato : '1/2 kg' , 
      calculatePrice : function (a, c, d){ 
         _________; 
         return a; 
      } ; 
      }; 
 groceryList.calculatePrice(groceryList ,55,25) 
 Output : 
  
 groceryList = { 
    tomato: ‘1 kg’, 
    potato: ‘1/2 kg’, 
    calculatePrice: [Function: calculatePrice], 
    price: 80 
 } 
	Find the  missing statement .
```
## Solution
```
 a.Price=c+d; 
 ```
# Problem 11
 ```
 const add = function (number1 ,number2){ 
      return number1 + number2 ; 
 }; 
 const sub = function(number1 ,number2){ 
      return number1 - number2 ; 
 }; 
 const mul = function(number1 ,number2){ 
      return number1 * number2 ; 
 }; 
 function div(number1 ,number2){ 
      return number1 / number2 
 }; 
 const add1 = function ( _function1 ,number1 ,number2){ 
      function newFn (_function2 ,number1 ,number2){ 
          return _function2(number1 , number2) 
      } ; 
  let sum1 = _function1(number1 ,number2) ; 
  let diff1 = sub(number2 ,number1) ; 
  let ans1 = newFn(mul ,sum1, diff1) ; 
  let ans2 = newFn(div ,sum1 ,diff1); 
  return add(ans1 , ans2) ; 
 } ; 
  
 ```
Check if the function declared above is valid . If yes - what happens when the function add1 (give suitable inputs) is executed ?. If No - What is the error ? 
## Solution
```
const add = function (number1 ,number2){ 
      return number1 + number2 ; 
 }; 
 const sub = function(number1 ,number2){ 
      return number1 - number2 ; 
 }; 
 const mul = function(number1 ,number2){ 
      return number1 * number2 ; 
 }; 
 function div(number1 ,number2){ 
      return number1 / number2 
 }; 
 const add1 = function ( _function1 ,number1 ,number2){ 
      function newFn (_function2 ,number1 ,number2){ 
          return _function2(number1 , number2) 
      } ; 
  let sum1 = _function1(number1 ,number2) ; 
  let diff1 = sub(number2 ,number1) ; 
  let ans1 = newFn(mul ,sum1, diff1) ; 
  let ans2 = newFn(div ,sum1 ,diff1); 
  return add(ans1 , ans2) ; 
 } ; 
 console.log(add1(add, 10, 5));
```
Output:
```
-78
```
# Problem 12
```
let array = [  
  [function(b){  
   return 'This a function inside ' + b ;}] ,  
  function(b) 
   {  
   let c = 'a array' + b ;   
   return array[0][0](c); 
   }; 
   ]; 
 
 ```
Is this a valid function declaration ? If Yes - Execute the function in first position of ‘array’ - if No — correct the error and do the same . 
## Solution
```
let array = [  
  [function(b){  
   return 'This a function inside ' + b ;
  }] ,  
  function(b) 
   {  
   let c = 'a array ' + b ;   
   return array[0][0](c); 
   }
   ]; 
   console.log(array[1]('example'))
```
Output:
```
This a function inside a array example
```
# Problem 13
```
sq = function(a){
      return a * a ; 
    }; 
    cu = function (b){ 
       return b*b*b ; 
    }; 
    function di(j , k){ 
      return j / k ; 
    }; 
    function problem (a , b ){ 
      integer1 = sq(a); 
      integer2 = cu(b); 
      integer3 = sq(a*b); 
      integer4 = di(a, b); 
    return (integer1 + integer2 + integer3 + integer4 ); 
    }; 
    const calculation=function (g, h){ 
      answer = problem (g, h); 
      return answer; 
    }; 
 calculation(10,5); 
 ```
Is this expression valid ? If Yes what is the output ? If No - Correct the error and find the  output
## Solution
```
sq = function(a){
      return a * a ; 
    }; 
    cu = function (b){ 
       return b*b*b ; 
    }; 
    function di(j , k){ 
      return j / k ; 
    }; 
    function problem (a , b ){ 
      integer1 = sq(a); 
      integer2 = cu(b); 
      integer3 = sq(a*b); 
      integer4 = di(a, b); 
    return (integer1 + integer2 + integer3 + integer4 ); 
    }; 
    const calculation=function (g, h){ 
      answer = problem (g, h); 
      return answer; 
    }; 
 console.log(calculation(10,5));
 ```
 Output:
 ```
 2727
 ```
 
 