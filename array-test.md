

   # array test

## 1. Create an array called fruits that contains the following elements: "apple", "banana", "orange". Now check if "orange" is in the fruits array.
```
let fruits = ["apple", "banana", "orange"];
arr=fruits.includes("banana");
console.log(arr)
```
 ## 2. Given an array of numbers, write a function that returns the sum of all the even numbers in the array.
```
let arr=[2,3,4,2]

function sumNumbers(num){
    let sum=0;
    for(let i=0;i<arr.length;i++){
        if(arr[i]%2===0){
            sum=sum+arr[i]
        }
    }

    return sum
}

console.log(sumNumbers(arr))
```
## 4. Given an array of strings, write a function that returns the longest string in the array.
```
let str = ["rashid","wecodeAcademy","khan"]
function longeststr(str){
    let max = str[0].length
    let ans = str[0]
    for(i = 0 ; i < str.length ; i++){
        let maximum = str[i].length
          if(maximum>max){
            max = maximum
            ans = str[i]
        }
    }
    return ans
}
console.log(longeststr(str))
```
## 5. Write a function that takes an array of numbers and returns the largest number in the array.
```
function max(arr) {
  let max = arr[0];
  for (let i = 0; i < arr.length; i++) {
    if (max < arr[i]) {
      max = arr[i];
    }
  }
  return max;
}
console.log(max([1, 2, 8, 4, 6]));
```
## 6. Write a function that takes an array of numbers and returns a new array that only contains the even numbers from the original array.
```
let array = [2, 3, 4, 5, 6];

even = array.filter(evennumber);
function evennumber(num) {
  return num % 2 === 0;
}
console.log(even);
```
## 7. Write a function that takes an array of strings and returns a new array that only contains strings with more than 5 characters.
```
let strWord = ["rashid", "khan", "wecode", "academy"];

function checking(num) {
  let maxx = [];
  for (let i = 0; i < strWord.length; i++) {
    if (strWord[i].length > 5) {
      maxx.push(strWord[i]);
    }
  }
  return maxx;
}
console.log(checking(strWord));
```
## 8. Write a function that takes two arrays of numbers and returns a new array that contains the intersection of the two arrays (i.e. only the numbers that appear in both arrays).
```
let oneArr = [2,2,3,4,5]
let secondArr = [6,2,13,4,2]
function inter(value) {
  let intersection = []
for(let value of oneArr){
if(secondArr.includes(value)){
  intersection.push(value)
}
}
return intersection
 } console.log(inter(oneArr,secondArr))
```
## 9. Write a function that takes an array of numbers and returns a new array where each element is the square of the original element
```
let array = [2,3,4]
ans=array.map(test)

function test(num){
    return num**2
}

console.log(ans)
```
## 11. Write a function that takes an array of numbers and returns a new array that only contains numbers that are greater than 5. Use filter function
```
let array = [3, 4, 5, 8, 7, 9];

ans = array.filter(test);

function test(num) {
  return num > 5;
}
console.log(array);
console.log(ans);
```
## 12. Write a function that takes an array of numbers and returns a new array where each element is the original element plus 1. use map function
```
let array=[2,3,4,5]

array=array.map(test)

function test(num){
    return num+1
}
console.log(array)
```
## 15. Write a function that takes an array of strings and sorts them by their length in ascending order.

```
// Example usage
let strings = ["apple", "banana", "cherry", "date"];
console.log(sortStringsByLength(strings)); // Output: ["date", "apple", "cherry", "banana"]
```
```
let str2 = ["apple", "banana", "cherry", "date"];
console.log(str2.sort(fruits));
function fruits(num, num1) {
  return num - num1;
}
```
## 19. Write a function that takes an array of numbers and returns a new array with the numbers sorted in ascending order.
```
let num2 = [2, 5,3,3,5,7];
console.log(num2.sort(ascendingNumber));

function ascendingNumber(num, num1) {
  return num - num1;
}
```