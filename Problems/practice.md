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
    name=name.padStart(16,"Surfboard")
    console.log(name) 
}

```
Output:
```
Abraham
SurfboardAbraham
Abraham
SurfboardAbraham
Abraham
SurfboardAbraham
Abraham
SurfboardAbraham
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
# Problem 4
 
 1: Start
 
 2: Set numberToCheck <- 1001001001001, 12345567891, 559922932941
 
 3: Remove the last digit
 
 5: From the last digit multiply each digit by 2
 
 6: Take each of the products derived and add them together
 
 7: Reduce the number until you get a single digit
 
 8: Check if the calculated value is equal to the last digit from Step 3
 
 9: Decide if the number is valid (If the value is equal, the number is valid. 
Otherwise it is invalid)

 10: Print the validity
 
 11: Stop
## Solution
```
function answer(value){
const split_val=value.split("")
const neww=split_val.pop()
split_val.reverse()
const c = split_val.map((v)=> parseInt(v)*2)
       const val = reduce(c)
       if(neww==val){
           return "valid"
       }
       else{
           return "Invalid"
       }

}
function reduce(data){
    const res= data.reduce((e,i)=>e+parseInt(i),0)
    const result = JSON.stringify(res).split("")
       if(result.length<=1) return res
     return reduce(result)
     
}

console.log(answer('1001001001001'))
console.log(answer('12345567891'))
console.log(answer('559922932941'))

```
Output:
```
Invalid
valid
valid
```
# Problem 5
 Your computer has received a message in Morse Code. However instead of the .s 
and _s, its replaced with ; and :. Everything else seems to be in the same 
structure as standard Morse code. How will you program your computer to this 
decrypt message. -> Eg: ;: :;;; ;:; ;: ;;;; ;: ::
## Solution
```
function code(val){
    
    const a=".s,_s"
    const new_val=val.split("")
    const replace_val=new_val.map((n1)=>n1.toString().replace(';','.s').replace(':','_s'))
    const val1=replace_val.join().replaceAll(',','')
    return val1
        
}
console.log(code(";: :;;; ;:; ;: ;;;; ;: ::"))
```
Output:
```
.s_s _s.s.s.s .s_s.s .s_s .s.s.s.s .s_s _s_s
```
# Problem 6
Your computer needs to sort 5000 degree certificates from SRM University in 
reverse alphabetical order. How will you teach your computer to do this?
## Solution
- Take all the degree certificates.
- Arrange all the certificates in descending order.
- Stack all the certificates in a way that each box has only 5000 certificates.
- Continue until all the certificates are stacked.

