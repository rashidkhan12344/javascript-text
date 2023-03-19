
# Exericse 16

### Question 1



## Write a JavaScript program to check whether a string "Code" presents at 5th (index 4) position in a given string, if "Code" presents in the string return the string without "Code" otherwise return the original one.
```
function check_script(str)
{
  if (str.length < 6) {
    return str;
  }
  let result_str = str;
    
  if (str.substring(10, 4) == "Script") 
    {
    
   result_str = str.substring(0, 4) + str.substring(10,str.length);
      
  }
  return result_str;
}

console.log(check_script("JavaScript"));
console.log(check_script("wecode"));
```

### Question 2

Write a JavaScript program to capitalize the first letter of each word of a given string.

```
Example string : 'the quick brown fox'
Expected Output : 'The Quick Brown Fox'
```
```
function capital_letter(str) 
{
    str = str.split(" ");

    for (var i = 0, x = str.length; i < x; i++) {
        str[i] = str[i][0].toUpperCase() + str[i].substr(1);
    }

    return str.join(" ");
}

console.log(capital_letter("the quick brown fox"));
```

  ### Question 3

### Write a JavaScript program to check whether all the digits in a given number are the same or not.
```
let array=[2,2,2,2]

same=2

ans=array.every(test)


function test(num){
    return num===same
}
console.log(ans)
```
### Question 4

### Write a JavaScript function that reverse a number.
```
function reverseNumber(num) {
  num = num + "";
  return num.split("").reverse().join("");
}
console.log(Number(reverseNumber(123)));
```

### Question 5

### Write a JavaScript function to extract unique characters from a string.

```
Example string : "thequickbrownfoxjumpsoverthelazydog"
Expected Output : "thequickbrownfxjmpsvlazydg"
```

### Question 6

## Write a JavaScript function to chop a string into chunks of a given length.
Test Data :

```
console.log(string_chop('w3resource'));
console.log(string_chop('w3resource',2));
console.log(string_chop('w3resource',3));
["w3resource"]
["w3", "re", "so", "ur", "ce"]
["w3r", "eso", "urc", "e"]
```

### Question 7

## Write a JavaScript function to find a word within a string.
Test Data :

```
console.log(search_word('The quick brown fox', 'fox'));
console.log(search_word('aa, bb, cc, dd, aa', 'aa'));
Output :
"'fox' was found 1 times."
"'aa' was found 2 times."
```

```
function searchWord(str, word) {
    let words = str.split(" ");
    let count = 0;
    for (let i = 0; i < words.length; i++) {
      if (words[i] === word) {
        count++;
      }
    }
    return word + " was found " + count + " times.";
  }
  console.log(searchWord("The quick brown  fox fox", "fox"));
  console.log(searchWord("aa, bb, cc, dd, aa", "aa"));
```
### Question 8

## Create an array of numbers. Now filter out all the numbers from the array where number is in between 30-50. After filtering the numbers, add 20 to each number and finally print the sum of all numbers using reduce function.



### Question 9

Convert below array

```
[[1,2], [3,4], [5,6], [7,8], [9,10]]
to
[3,7,11,15,19]
```
```
let arr = [
    [1, 2],
    [3, 4],
    [5, 6],
    [7, 8],
    [9, 10],
  ];
  let newArr = [];
  for (let i = 0; i < arr.length; i++) {
    let inArr = arr[i];
    let sum = inArr[0] + inArr[1];
    newArr.push(sum);
  }
  console.log(newArr);
  ```

### Question 10

Print below pattern

```
1 2 3 4 5
 2 3 4 5
  3 4 5
   4 5
    5
```
```
for (let a = 1; a <= 5; a++) {
    str = "";
    for (let b = 1; b <= a; b++) {
      str += " ";
    }
  
    for (let c = a; c <= 5; c++) {
      str += c + " ";
    }
    console.log(str);
  }
```