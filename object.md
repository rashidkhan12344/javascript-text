# Object Questions

## 1 . What is an object in JavaScript?
```
let details = {
    name: "khan",
    mobile: 2323324,
    age: 21,
    
    function: function test() {},
  };
  console.log(
    "My name is " + details.name + " My mobile number is " + details.mobile
  );
```
 ## 2 . What is the difference between dot notation and bracket notation for accessing object properties?

 ## 3 . How do you loop through the properties of an object in JavaScript?
```
const obj = {
    name: "rashid",
    mobile: 234434343,
    address: "jaipur",
  };
  let arr = Object.entries(obj);
  for (let value of arr) {
    console.log(value);
  }
  ```
 ## 4 . What is the difference between an object and an array in JavaScript?

 ## 5 . Write a JavaScript function to convert an object into a list of `[key, value]` pairs.
```
let obj = {
  name: "rashid",
  mobile: 23343334,
  address: "jaipur",
};
console.log(Object.entries(obj));

```

 ## 6 . Write a function that takes an object representing a person and returns their full name.
```
let person = {
    firstName: "rashid",
    lastName: " khan ",
    fatherName: "kayyum",
    address: " jaipur",
  };
  console.log(
    "my name is " +
      person.firstName +
      person.lastName +
      "and my father name is " +
      person.fatherName +
      " I am from" +
      person.address
  );
```
##  7 . Create an Object with your personal details. Now print all the keys of the object in ascending order.
```
let obj = {
  name: "rashid",
  age: 21,
  city:"hindaun",
  college: "wecode",
  location: "jaipur",
};

let sortedKeys = Object.keys(obj).sort();

for (let key of sortedKeys) {
  console.log(key);
}
```
 ## 8 . Create an Object with your personal details. Now filter out all the values of the object and show them in descending order.



 ## 9 . Create an object to hold information on your favorite recipe. It should have properties for title (a string), servings (a number), and ingredients (an array of strings).
 ```
On separate lines (one console.log statement for each), log the recipe information so it looks like:
Mole
Serves: 2
Ingredients:
cinnamon
cumin
cocoa
```
 ## 10 . Create a JavaScript function inside an object which finds max of 3 numbers. Now call this function of the object and print the maximum number.
