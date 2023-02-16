## Answer Key for JS Loops Lab

Please note that this key only reflects one of many possible solutions for the "JS Loopy Math" lab. If your output meets the criteria for each exercise, you are on the right track!

1. 
```javascript
for(let i = 0; i <= 100; i++) {
  console.log(i)
}
```

2. 
```javascript
let sum = 0

for(let i = 0; i <=100; i++){
    sum += i
}

console.log("your total is " +sum)
```
The sum of all numbers from 0 to 100 = 5,050

3. 
```javascript
for(let i = 0; i < 100; i++){
    n = Math.pow(i,2)
    if(n <= 100){
        console.log(n)
    }  
}
```
4. 
```javascript
for(let i = 0; i < 100; i++){
    n = i % 2
    if(n === 0){
        console.log(i)
    }  
}
```

5. 
```javascript
for(let i = 0; i <= 1007; i++){
    if(i % 10 == 7){
        console.log(i)
    }  
}
```

6. 
```javascript
for(let i = 0; i <= 100; i++){
    if(i % 3 == 0){
        console.log(i)
    }  
}
```


Challenge 1. 
```javascript
let days = 0
for (let i = 0; i <= 30; i++){
    days += 1
    if (days <= 30){
        let grain = Math.pow(2,i) 
        console.log("On day "+days+" you will have "+grain+" grain(s) of rice.")  
    }         
} 
```


Challenge 2:
```javascript
for(let i = 0; i <= 100; i++){
    if(i % 2 == 0){
        console.log("These are the multiples of 2: " + i)
    }  
}

for(let i = 0; i <= 100; i++){  
   if(i % 3 == 0){
        console.log("These are the multiples of 3: " + i)
    } 
}

for(let i = 0; i <= 100; i++){
    if(i % 2 == 0 && i % 3 == 0){
        console.log("These are the multiples of 2 & 3: " + i)
    } 
}
```


Challenge 3:
```javascript
for(let i = 0; i <= 100; i++){
    if(i % 2 == 0 || i % 3 == 0){
        console.log("These are the multiples of 2 OR 3: " + i)
    } 
}
```