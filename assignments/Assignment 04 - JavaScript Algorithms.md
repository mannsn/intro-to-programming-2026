**NOTE: If the CodeSandbox file gets updated, the code example below may not be up to date.  You can confirm the most recent version of this assignment by clicking this:**
[Link to CodeSandbox Assignment](https://codesandbox.io/p/sandbox/lesson-4-javascript-array-methods-2025-w4mycz?file=%2Fsrc%2Findex.mjs)

``` javascript

//----------------------------------
// LESSON 4 ALGORITHMS
//----------------------------------

// ----- Practice JS array methods: forEach -----
//---------- QUESTION 1 ----------
// Create an variable called 'names' and assign it an array of people's names.  Write a function called 'printNames' that uses the forEach array method to log each name in an array to the console.  Remember, since you're using the console.log in the function, you'll just want to call your function and pass it the array of names when testing your code.

// EXAMPLE CALL:
//    let names = ["Juan Marcos", "Aleksandra Ivanov", "Zhang Wei", "Bernice King"];
//    console.log("Q1 printNames:");
//    printNames(names);

// EXAMPLE OUTPUT:
//   Q1 printNames:
//   Juan Marcos
//   Aleksandra Ivanov
//   Zhang Wei
//   Bernice King

// PUT YOUR CODE HERE

//---------- QUESTION 2 ----------
// Create a variable called 'trees' and assign it an array of 3 objects.  Each object should have a 'type' property and a 'height' property.  You can use 'type' to describe the type of tree (ex. Dogwood, Maple, Oak, Elm, etc.) and give them any height.  Now write a function called 'logTreeType' that uses forEach to log the type of each tree object to the console.

// EXAMPLE CALL:
//   const trees = [
//     { type: "oak", height: "30m" },
//     { type: "elm", height: "25m" },
//     { type: "birch", height: "18m" } ]
//   console.log("Q2 logTreeType:");
//   logTreeType(trees);

// EXAMPLE OUTPUT:
//   Q2 logTreeType:
//   oak
//   elm
//   birch

// PUT YOUR CODE HERE

//---------- QUESTION 3 ----------
// Create a variable called 'myNumbers' and assign it an array of numbers.  Now write a function caled 'totalPoints' that uses forEach to add up all the numbers in that array of numbers.

// EXAMPLE CALL:
//   let myNumbers = [1, 2, 7, 5, 8];
//   console.log (`Q3 totalPoints [${myNumbers}]:`, totalPoints(myNumbers));

// EXAMPLE OUTPUT:
//   Q3 totalPoints [1,2,7,5,8]:  23

// Try a few different input arrays to verify your code is working.

// PUT YOUR CODE HERE

//---------- QUESTION 4 ----------
// Create a variable called 'myWords' and assign it an array of words.  Then write a function called 'buildSentence' that takes in an array of words and uses forEach to add the strings together. It should also add a space, " ", after each word.

// EXAMPLE CALL:
//    myWords = ["You","can","if","you","think","you","can","!"];
//    console.log (`Q4 buildSentence [${myWords}]: `, buildSentence(myWords));

// EXAMPLE OUTPUT:
//   Q4 buildSentence [You,can,if,you,think,you,can,!]:  You can if you think you can !

// Note: You should have a space after the ! too
// Try a few different input arrays to verify your code is working.

// PUT YOUR CODE HERE

//---------- QUESTION 5 ----------
// Create a variable called 'decimals' and assign it an array of decimal numbers.  Write a function called 'logPercentages' that takes an array of decimal numbers and uses forEach to log each one with the numbers formatted as percentages. That means:
//    Multiply by 100
//    Include the percent symbol (%) at the end of the string

// EXAMPLE CALL:
//   let decimals = [0.75, 0.91, 0.2, 1.34];
//   console.log("Q5 logPercentages:");
//   logPercentages(decimals);

// EXAMPLE OUTPUT:
// Q5 logPercentages:
//   75%
//   91%
//   20%
//   134%

// PUT YOUR CODE HERE




// ---------- QUESTION 8 ----------
// Create a function called 'absDiff' that takes 2 parameters and returns the absolute difference between them. For example, if the first parameter is smaller than the second, the first parameter will be subtracted from the second. If the first parameter is larger than the second, the second parameter will be subtracted from the first. If they are both equal, return the first parameter subtracted by the second.  It's important to consider boundary cases - situations that may change how you expect your code to behave.  For this reason, work with same numbers and negative numbers as well to see if you get your absDiff function to calculate the absolute difference regardless of number type.

// EXAMPLE LOG 1:
//    console.log("Q8 first larger: ", absDiff(29, 5));
// EXAMPLE OUTPUT: (if using the numbers 29 and 5 as in the example log)
//    Q8 first larger: 24
// EXAMPLE LOG 2:
//    console.log("Q8 second larger: ", absDiff(3, 16));
// EXAMPLE OUTPUT: (if using the numbers 3 and 16 as in the example log)
//    Q8 second larger: 13
// EXAMPLE LOG 3:
//    console.log("Q8 same nums: ", absDiff(5, 5));
// EXAMPLE OUTPUT 3: (if using the numbers 5 and 5 as in the example log)
//    Q8 same nums: 0
// EXAMPLE LOG 4:
//    console.log("Q8 neg num: ", absDiff(-6, 5));
// EXAMPLE OUTPUT 4: (if using the numbers -6 and 5 as in the example log)
//    Q8 neg num: 11

// PUT YOUR CODE HERE

// ---------- QUESTION 9 ----------
// Create a function called 'convertTemp' that takes 1 temperatue parameter in celsius and return the temperature in Fahrenheit.  Log both the input and output values

// EXAMPLE LOG:
//    console.log("Q9 convertTemp: ", celsiusTemp, convertTemp(celsiusTemp));
// EXAMPLE OUTPUT:
//    Q9 convertTemp: 0 32
// Create logs for several different celsium temperatures

// PUT YOUR CODE HERE

// ---------- QUESTION 10 ----------
// Create a function called 'reverseString' that takes 1 string parameter and returns the reverseString.  Log both the input and output values

// EXAMPLE LOG:
//    console.log("Q10 reverseString: ", inputString, reverseString(inputString));
// EXAMPLE OUTPUT:
//    Q10 reverseString: HelloWorld dlroWolleH

// PUT YOUR CODE HERE

// ---------- QUESTION 11 ----------
// Declare a variable named "diameter" and assign it an integer value. Through a series of math calculations and variables, calculate the "radius" (which is half the diameter), the "circumference" (which is 2 multiplied by the Math value pi, multiplied by the radius) and the "area" (which is the Math value pi, multiplied by the radius squared).

// PUT YOUR CODE HERE

// Don't forget your console.logs!

// ---------- QUESTION 12 ----------
// Let's make a useful math problem - create a tip calculator! Declare two variables called "billTotal" and "tipPercentage". Assign billTotal a floating point number with two decimal places. Assign tipPercentage a floating point number between 0.1 and 0.9. Create a third variable called "tip" that will multiply tipPercentage and billTotal then use the addition assignment operator to add that amount back to billTotal. Example: if our bill 35.75 and we want to leave a 20% tip (0.2) our new billTotal should come out to 42.90.

// PUT YOUR CODE HERE

// Don't forget your console.logs!

// ---------- QUESTION 13 ----------
// Create two variables named 'num1' and 'num2' and assign them integer values. Create a function called 'multiplyThese' that takes 2 parameters and returns the product  of the two parameters (as a reminder, a product is the resulting number when two numbers are multiplied together).

// EXAMPLE LOG:
//    console.log("Q13: ", multiplyThese(num1, num2));
// EXAMPLE OUTPUT: (if num1 and num2 are 2 and 5 respectively))
//    Q13: 10

// PUT YOUR CODE HERE

// ---------- QUESTION 14 ----------
// Building on the last question, create a function called 'getAverage' that takes 2 parameters and returns their average (hint: there is no built-in average operator in JavaScript).  Use the variables (num1 and num2) you created in Question 6 to test your function.  NOTE: In some programming languages, the types of numbers you use in equations can effect what type of number (integer/floating point) you get as a result.  We suggest using 2.0 instead of 2 as you're calculating the average.

// EXAMPLE LOG:
//    console.log("Q14: ", getAverage(num1, num2));
// EXAMPLE OUTPUT: (based on num1 and num2 above)
//    Q14: 3.5

// PUT YOUR CODE HERE
