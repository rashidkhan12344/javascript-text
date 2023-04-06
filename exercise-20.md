
    








###  1. Write a function that takes a string and returns a new string with all the words reversed using the spread operator.


```
let str="rashid";

function test(str){
    newstr="";
    newstr=[...str].reverse().join("")
    return newstr
}

console.log(test(str))
```


### 2. Create a function that takes in an array and uses the rest operator to remove the first element from the array and finally return the array without first element.
```
let arr=[2,3,4,5,6,7]

let [,...a]=arr

function test([,...a]){
    return [...a]
}

console.log(test(arr))
```

### 3. Create a function that takes in an unknown number of arrays and uses the rest operator to flatten them into a single array
```
let arr = [1, 2, 3, 4, 5];
let arr1 = [6, 7, 8, 9, 10]

function number([...arr]) {
    console.log(arr);
  }
 
  number([...arr, ...arr1]);
  ```


### 4. Write a function that takes an object as a parameter and returns the value of its "x" property if it exists, otherwise it returns null. Hint : (Use optional chaining)

### 5. Write a function which takes in an array and create two separate arrays for odd numbers and even numbers and finally merge them in the order that all odd numbers will move to the left of the array and all even numbers to right of the array.
```
let arr=[2,3,4,5,6,7]

let oddnumber=arr.filter((num)=>num%2===1)
console.log(oddnumber)

let evennumber=arr.filter((num)=>num%2===0)
console.log(evennumber)

let newarr=[...oddnumber,...evennumber]
console.log(newarr)
```
### 6. Create an array of numbers. Now change the position of each element with their next element. 
```
For example : [1,2,3,4,5,6,7]
Output : [2,1,4,3,6,5,7]
```




### 7. Ask user below questions 
```
What is your age  : 12
What is your mobile : 9581894461
What is your address : Jaipur
```

Now create an object and use enhanced object literal property computation to create below object 
```
{
    age12 : 12
    9581894461 : 'Mobile',
    Jaipur12Address : 'Jaipur'
}
```



### 8. Using enhanced object literal function, create a function sum which takes an array as parameter and return sum of all the numbers in the array.



### 9. Take a number and check if number is greater than 80 or not. If yes then assign 100 to number else assign 200. Use short circuiting whereever possible.

```
let num = 100;
if (num > 80) {
console.log(num && 100);
} else {
console.log(num && 200);
}

```
### 10. Create an array of 10 numbers. Now create a new array of 0 and 1 using Array destructring based on if number is odd then 1 else 0
```
Array : [1,2,3,4,5,6,7,8,9]
Output: [1,0,1,0,1,0,1,0,1,0]
```





### 11. Given an array of price, use map function to return a new array where each price is converted to new price including tax, which is the price with a 10% tax added.

### 12. Given an array of strings, use reduce to return the total number of characters in all the strings.
```
let arr=["wecode","hello","jaipur"]

for(let i=0;i<arr.length;i++){
    console.log(arr[i])
}
let ans=arr.reduce(test)

function test(total,value){
    return total+value
}

console.log(ans)
```
### 13. Given an array of strings, use map and reduce to return the total number of characters in all the strings with a length less than 5.

```


let arr=["wecode","he","she"]

let arrlength=arr.filter((num)=>num.length<5)
console.log(arrlength)

let ans=arrlength.reduce(sumlength,0)

function sumlength(total,value){
    return total+value.length

}
console.log(ans)
```

### 14. Given an array of numbers, use map, filter, and reduce to return the sum of all the odd numbers multiplied by 3
````
let arr = [1, 2, 3, 4, 5,];

let oddnumber=arr.filter((num)=>(num%2===1))
console.log(oddnumber)

let multinumber=oddnumber.map((num)=>num*3)
console.log(multinumber)

let sumnumber=multinumber.reduce((total,value)=>(total+value))
console.log(sumnumber)
````



## 15. Given a string, reverse the order of the words in the string. For example, "the quick brown fox" becomes "fox brown quick the".
```


let str = "the quick brown fox";

let  spt=str.split(" ")

console.log(spt.reverse().join(" "))

```