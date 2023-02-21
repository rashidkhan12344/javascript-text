

           // test 


//         ### Question 1

// Write a JavaScript function to capitalize the first character of the string.

// ```
// for example:
// wecodeacademy

// output:
// Wecodeacademy
// ```

// ### Question 2

// Write a JavaScript function to insert a string within a string at a particular position

// ```
// for example:
// We are learning exercises.

// now insert the word JavaScript at 14 position so output will be :

// We are learning JavaScript exercises.
// ```

// ### Question 3

// Write a JavaScript function to count the occurrence of a substring in a string.

// ```
// "My name is wecode academy and my friend name is Arun Kumar."

// find count of 'is' in this word is 2.
// ```

// ### Question 4

// Ask user below questions:

// 1. What is your name?
// 2. What is your mobile number?
// 3. What is your account number?
// 4. What is your atm card number?
// 5. What is your aadhar number?

// Now do below tasks:

// 1. Mask last 3 digits of the mobile number
// 2. Mask middle of 5 numbers of the account
// 3. Mask last 8 digit of atm card number
// 4. Mask starting 4 digits and last 4 digits of aadhar number

// ### Question 5

// Print below pattern using repeat function

// ```
//      $
//     $$$
//    $$$$$
//   $$$$$$$
//  $$$$$$$$$
// $$$$$$$$$$$
// ```

// ### Question 6

// Ask below questions :

// 1. What is your name?
// 2. What is your birth year?
// 3. What is your address ?
// 4. What is your country code?
// 5. What is your mobile number?

// Now using string template literal syntax show below output based on your answer:

// My name is Sajid Khan. I was born in 1993 and my current age is 30 years. My address is Jhotwara, Jaipur and my mobile number is +919565465654.

// ### Question 7

// Divide a string in two part.

// Now in right side part add Hello in the end
// In left side of the string add World in starting

// for example:

// ```
// let str = "Wecode Academy"

// output:
// Wecode Hello World Academy
// ```

// ### Question 8

// Guessing Game?
// Ask user what character is present at particular index in a word.

// If user guess is right then show him Congrulations message otherwise show Sorry message.

// for example:
// Wecode Academy

// What is the character you are guessing? A
// What is the index? 3

// Sorry

// ### Question 9

// Print Pattern using repeat function
// ```
// ***********
//  *********
//   *******
//    *****
//     ***
//      *
// ```

// ### Question 10

// Print below Series using repeat function
// ```
// 1 224 3339 44412 555520
// ```


        //   answer


// ans-1

// let str = "wecodeacademy";

// let arr = str.split(" ");

// for (var i = 0; i < arr.length; i++) {
//   arr[i] = arr[i].charAt(0).toUpperCase() + arr[i].slice(1);
// }

// let str2 = arr.join(" ");
// console.log(str2);




// ans-5

// let n = 6;
// let string = "";

// for (let i = 1; i <= n; i++) {

//   for (let j = 1; j <= n - i; j++) {
//     string += " ";
//   }

//   for (let k = 0; k < 2 * i - 1; k++) {
//     string += "$";
//   }
//   string += "\n";
// }
// console.log(string);




// ans-6

// let Name=prompt("What is your name");
// let birth=Number(prompt("What is your birth year"));
// let address=prompt("What is your address ");
// let countryCode=Number(prompt("What is your country code"));
// let mobileNnumber=Number(prompt("What is your mobile number"));

// console.log(`My name is ${Name}.I was born in ${birth} and my current age is 30 year .my address is ${address} and my mobile number is
//  ${mobileNnumber}
// `
// )



// ans-7

// let str="Wecode Academy";

// console.log(str .replace("Wecode","Hello","Academy","World"))




// // ans-8

// let str = "Wecode Academy";
// let a = str.indexOf("A");

// if (a === 3) {
//   console.log("Congrulations");
// } else {
//   console.log("sorry");
// }




// ans-9

// let a = 6;
// let string = "";

// for (let i = 0; i < a; i++) {
//   for (let j = 0; j < i; j++) {
//     string += " ";
//   }

//   for (let k = 0; k < 2 * (a - i) - 1; k++) {
//     string += "*";
//   }
//   string += "\n";
// }
// console.log(string);



// ans-2

// let str="We are learning exercises";

// let a=str.length
// console.log(a)

// str.split




