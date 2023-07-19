 # Arrray basic qestion ans answer #
 
## 1. Array numbers ka. Loop chlana hai. Agar number odd hai to ODD print hai krna hai otherwise EVEN print krna ha ##

```
let arr = [2, 3, 4, 5, 6];

for (let i = 0; i < arr.length; i++) {
  if (arr[i] % 2 === 1) {
    console.log("odd");
  } else {
    console.log("even");
  }
}
```

 ## 2. Array numbers ka. Sare numbers ko add krke print krna hai ##
 ```
let arr = [2, 3, 4, 5, 6];

let sum = 0;

for (let i = 0; i < arr.length; i++) {
  sum = sum + arr[i];
}
console.log(sum);
```

## 3. Array numbers ka. Sare Odd numbers ko add krke print krna hai
```
let arr = [2, 3, 4, 5, 6];
let oddNumberSum = 0;

for (let i = 0; i < arr.length; i++) {
  if (arr[i] % 2 === 1) {
    oddNumberSum = oddNumberSum + arr[i];
  }
}
console.log(oddNumberSum);
```

## 4. Array numbers ka. Sare Even numbers ko add krke print krna hai ##
```
let arr = [2, 3, 4, 5];
evenNumberSum = 0;
for (let i = 0; i < arr.length; i++) {
  if (arr[i] % 2 === 0) {
    evenNumberSum = evenNumberSum + arr[i];
  }
}
console.log(evenNumberSum);
```
## 5. Array numbers ka. Maximum number btana hai ##
```

let arr=[3,4,5,777,,999,7,7,4];

let max=arr[0];
for(let i=0;i<arr.length;i++){
  if(max<arr[i]){
    max=arr[i]
  }
}
console.log(max)
```

## 6. Array numbers ka. Minimum number btana hai
```
let arr = [10, 4, 5, 777, , 999, 7, 7, 4];

let min = arr[0];
for (let i = 0; i < arr.length; i++) {
  if (min > arr[i]) {
    min = arr[i];
  }
}
console.log(min);
```
## 7. Array ka phla number print krvana hai ##
```
let arr=[3,4,5,6]
console.log(arr[0])
```
 ## 8. Array ka last number print krvana hai ##
 ```
let arr=[2,34,5,6]
console.log(arr[arr.length-1])
```
## 9. Array me kitne numbers aise hai jo 100 se bde hai ##
```
let arr = [3, 45, 555, 6, 770, 545];
let count = 0;
for (let i = 0; i < arr.length; i++) {
  if (arr[i] > 100) {
    count++;
  }
}
console.log(count);
```
## 10. Array me kitne numbers aise hai jo 20 se bde or Even hai ##
```
let arr = [3, 55, 40, 44, 20, 22];
let EvenMaxcount = 0;
for (let i = 0; i < arr.length; i++) {
  if (arr[i] % 2 === 0 && arr[i] > 20) {
    EvenMaxcount++;
  }
}
console.log(EvenMaxcount);
```
