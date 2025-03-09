## Return a sentence in CamelCase
### Solution
```
function camelcase(s){
    const str=s.split(" ")
    let firstWord=str[0].toLowerCase()
    for(let s=1;s<str.length;s++){
            const n=str[s].slice(0,1)
            const newWord=n.toUpperCase()
            const newSlice=str[s].slice(1)
        firstWord=firstWord.concat(newWord).concat(newSlice)
    }
    return firstWord
}
console.log(camelcase("Make a sentence in camel case"))
```
Output:
```
makeASentenceInCamelCase
```