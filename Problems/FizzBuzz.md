# Problem Solving
## Problem: FizzBuzz

Write a function called fizzBuzz that takes a number n as input and prints numbers from 1 to n with the following rules:

- If a number is divisible by 3, print "Fizz" instead.
- If a number is divisible by 5, print "Buzz" instead.
- If a number is divisible by both 3 and 5, print "FizzBuzz".
- Otherwise, print the number itself.

## Solution:
```
function fizzBuzz(n){
for(let i=1;i<=n;i++){
    if(i%3==0 && i%5==0){
        console.log("FizzBuzz")
        
        }
        
    if(i%3==0 && i%5!=0){
        console.log("Fizz") 
    }
     if(i%5==0 && i%3!=0)
    {
        
        console.log("Buzz")
    }
    if(i%3!=0 && i%5!=0){
        console.log(i )
    }
}
}
fizzBuzz(90)
```
In switch:
```
function fizzBuzz(n){
    for(let i=1;i<=n;i++){
        switch(true){
            case i%3==0 && i%5==0 :
                console.log("FizzBuzz")
                break;
            case i%3==0 && i%5!=0:
                console.log("Fizz")
                 break;
            case i%5==0 && i%3!=0:
                console.log("Buzz")
                 break;
            case i%3!=0 && i%5!=0 :
                 console.log(i)
                 break;
        }
    }
 }
fizzBuzz(50)
```
## Output:
```
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz
16
17
Fizz
19
Buzz
Fizz
22
23
Fizz
Buzz
26
Fizz
28
29
FizzBuzz
31
32
Fizz
34
Buzz
Fizz
37
38
Fizz
Buzz
41
Fizz
43
44
FizzBuzz
46
47
Fizz
49
Buzz
```
### Write an algorithm for this

Add different balls to a box, balls should be of different colours, every ball that has blue colour should be moved to a different box, and green colour balls should be painted pink and moved to a different box

Try to write a programming algo for this

#### Algorithm:
Step1: Add different colored balls to a box

Step2: Take the ball from the box, identify the color of the ball.

Step3: If the color of the ball is blue, place it inside the first box.

Step4: If the color of the ball is green, paint that ball to pink color and then place it inside the second box.

step5: Repeat the steps above until you categorize every balls.
Solution:
```
const randomBalls=[{ballNumber:1,colour:'green'},
         {ballNumber:2,colour:'blue'},
         {ballNumber:3,colour:'green'},
         {ballNumber:4,colour:'blue'},
         {ballNumber:5,colour:'green'},
         {ballNumber:6,colour:'blue'},
         {ballNumber:7,colour:'green'},
         {ballNumber:8,colour:'blue'},
         {ballNumber:9,colour:'green'},
         {ballNumber:10,colour:'blue'},
         {ballNumber:11,colour:'green'},
         {ballNumber:12,colour:'blue',},
         {ballNumber:13,colour:'blue'},
         {ballNumber:14,colour:'green'},
         {ballNumber:15,colour:'blue'},
         {ballNumber:16,colour:'green'},
         {ballNumber:17,colour:'blue'},
         {ballNumber:18,colour:'green'},
         {ballNumber:19,colour:'blue'},
         {ballNumber:20,colour:'green'},
        ]
const blueBucket=[]
const pinkBucket=[]

for(let i=0;i<randomBalls.length;i++){
      console.log(randomBalls[i])
    if(randomBalls[i].colour==="blue"){
        blueBucket.push(randomBalls[i])
    }
    if(randomBalls[i].colour==="green"){
        randomBalls[i].colour="pink"
        pinkBucket.push(randomBalls[i])
    }
}
 console.log(blueBucket)
 console.log(pinkBucket)
```
Output:
```
{ ballNumber: 1, colour: 'green' }
{ ballNumber: 2, colour: 'blue' }
{ ballNumber: 3, colour: 'green' }
{ ballNumber: 4, colour: 'blue' }
{ ballNumber: 5, colour: 'green' }
{ ballNumber: 6, colour: 'blue' }
{ ballNumber: 7, colour: 'green' }
{ ballNumber: 8, colour: 'blue' }
{ ballNumber: 9, colour: 'green' }
{ ballNumber: 10, colour: 'blue' }
{ ballNumber: 11, colour: 'green' }
{ ballNumber: 12, colour: 'blue' }
{ ballNumber: 13, colour: 'blue' }
{ ballNumber: 14, colour: 'green' }
{ ballNumber: 15, colour: 'blue' }
{ ballNumber: 16, colour: 'green' }
{ ballNumber: 17, colour: 'blue' }
{ ballNumber: 18, colour: 'green' }
{ ballNumber: 19, colour: 'blue' }
{ ballNumber: 20, colour: 'green' }
[
  { ballNumber: 2, colour: 'blue' },
  { ballNumber: 4, colour: 'blue' },
  { ballNumber: 6, colour: 'blue' },
  { ballNumber: 8, colour: 'blue' },
  { ballNumber: 10, colour: 'blue' },
  { ballNumber: 12, colour: 'blue' },
  { ballNumber: 13, colour: 'blue' },
  { ballNumber: 15, colour: 'blue' },
  { ballNumber: 17, colour: 'blue' },
  { ballNumber: 19, colour: 'blue' }
]
[
  { ballNumber: 1, colour: 'pink' },
  { ballNumber: 3, colour: 'pink' },
  { ballNumber: 5, colour: 'pink' },
  { ballNumber: 7, colour: 'pink' },
  { ballNumber: 9, colour: 'pink' },
  { ballNumber: 11, colour: 'pink' },
  { ballNumber: 14, colour: 'pink' },
  { ballNumber: 16, colour: 'pink' },
  { ballNumber: 18, colour: 'pink' },
  { ballNumber: 20, colour: 'pink' }
]
```
### count the letters of a string
Solution:
```
const word="hello"
const a=word.split("")
const b=a.length
console.log(b)
```
Output:

5

















