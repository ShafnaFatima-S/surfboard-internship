# Problem 1
 1: Start
 
 2: Set Name <- ‘Abraham’
 
 3: Print Name
 
 4: Add ‘Surfboard ‘ to the beginning of Name
 
 5: Print Name
 
 6: Goto Step 2 and continue till you print Name(Abraham) 5 times
 
 7: Stop
 
 ### Solution:
 ```
 let name="Abraham"
for(let i=0;i<5;i++){
    let name="Abraham"
    console.log(name)
    
}
name=name.padStart(16,"Surfboard")
console.log(name) 
```
Output:
```
Abraham
Abraham
Abraham
Abraham
Abraham
SurfboardAbraham
```
# Problem 2
 1: Start
 
 2: Set max <- 0
 
 3: Take a number from the input
 
 4: Check if number is greater than max, if it is, set max <- number
 
 5: Goto Step 3, until all given numbers are exhausted
 
 6: Print max
 
 7: Stop
 ## Solution
 ```
 let max=0
let input=[3,7,5]
console.log("Input: " +input)
for(i=1;i<=input.length;i++){
    if(input[i]>max){
    max=input[i]
}
}
console.log("max: "+max)
 ```
 Output:
 ```
 Input: 3,7,5
max: 7
```
 # Problem 3
 Write the algorithm to multiply two 4 digit numbers. Assume the computer knows 
nothing about multiplication and only about addition.
## Solution
- Get the two four digit numbers
- Add the value1 by itself and store it.
- with the stored value again add the value1, repeat it for value2 times.
- Print the answer.
```
function multiply(a,b){
    let res=0
    for(let i=0;i<b;i++){
        res+=a
    }
    console.log(res)
}
multiply(1232,5678)
```
Output:
```
6995296
```