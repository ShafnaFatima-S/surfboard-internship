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


















