
``` javascript

//-------------------------------------------
// LESSON 3 OBJECTS
//-------------------------------------------

//# JavaScript Objects
// This is the coding assigment for the third week of the Intro to Programming course from Code the Dream. The concepts touched on in this assignment include:
//   - Object Basics
//   - Primitive vs Object Types
//   - Manipulating Objects

// In this assignment you will write your own code. Your instructions are listed as "comments", meaning the instructions are grayed out and start with '//' at the beginning of the line of code. Put your answers immediately below the instructions for each question. As mentioned in the Welcome to week 3 information to the right, you'll need to use console logs for all the questions to check your code output. Using a function in a console.log is very similar to how you were using them with variables last week. To invoke/call the function use the syntax:

//  console.log("Q#: ", functionName(anyInput))

// Please be sure to check the output of your called functions and console logs in the Console tab to the bottom right of this screen. If your Console is not showing, click the Inspect Button in the top right (see the Welcome to week 3 information to the right if you need help finding that)  Check to make sure that the output you get in your Console is the expected output.

// ---------- QUESTION 1 Defining and Displaying the Object, Displaying properties ----------
// Objects are a way to store property:value pairs of data in a variable.  First, create an object called 'myPet'.  Add three properties called 'name', 'species', and 'color' to the 'myPet' object below and assign each of the values. Use your console.log to print the object.  Use your console.log's to print the values of each property to the console.

// EXAMPLE LOG:
//    console.log("Q1 object: ", myPet);
//    console.log("Q1 name: ", myPet.name);
//    console.log("Q1 species: ", myPet.species);
//    console.log("Q1 color: ", myPet.color);

// EXAMPLE OUTPUT:
//    Q1 object:  {"name":"Teddy","species":"ferret","color":"brown"} 
//    Q1 name: Teddy
//    Q1 species: ferret
//    Q1 color: brown
//   
// PUT YOUR CODE HERE

// ---------- QUESTION 2 Displaying properties with a template---------
// Now let's see how we can use the property:value pairs in template literals.  Create a variable called 'aboutPet' and assign it a template literal that uses the 'myPet' object to make a sentence sharing all the pet details.  The sentence should look something like this: "Teddy is a brown ferret."

// EXAMPLE LOG:
//    console.log("Q2: ", aboutPet);
// EXAMPLE OUTPUT:
//    Q2: Teddy is a brown ferret.

// PUT YOUR CODE HERE

// ---------- QUESTION 2 Modifying properties ---------
// Now let's see how we can modify the properties. Modify the 'name' property of the 'myPet' object. This name should be different than the value used in Question 1 (e.g. Henry ). Use your console.log's to print the myPet console. Verify the 'name' property is different than the value in Question 1.

// EXAMPLE LOG:
//    console.log("Q3 updated object", myPet);
// EXAMPLE OUTPUT:
//    Q3 updated object:  {"name":"Teddy","species":"ferret","color":"brown"} 


// PUT YOUR CODE HERE

// ---------- QUESTION 3 Looping thru properties ---------
// Now let's see how we can loop thru the properties - this is a common task in JavaScript. Use a for...in loop, a special type of loop in JavasScript designed specifically for iterating over the properties of an object.  See https://www.w3schools.com/js/js_loop_forin.asp for reference.
//  Write a for...in loop that iterates through each property in the myPet object and prints the property name and its value to the console in the following format:
//Q4: propertyName: propertyValue
//Use console.log() inside the loop to display each key-value pair.

// EXAMPLE LOG in the loop - replace <..>  :
//    console.log("Q4: "+ <Supply key here> + ":",  <Supply value here> );
// EXAMPLE OUTPUT:
//    Q4: name: Henry
//    Q4: species: ferret
//    Q4: color: brown

// PUT YOUR CODE HERE

// ---------- QUESTION 4 ----------
//Let’s explore how to work with object data inside a function. Your task is to define a method called describe on the myPet object. This method should take no parameters and return a sentence using a template literal that describes your pet using its properties.

//Add a method named describe to the myPet object.
//Inside the method, use a template literal to construct a sentence using the name, color, and species properties.
//Use console.log() to display the result in the format shown below.

// EXAMPLE LOG:
//    console.log("Q4: ", myPet.describe());
// EXAMPLE OUTPUT:
//Q4: Teddy is a brown ferret. 

// PUT YOUR CODE HERE


// ---------- QUESTION 3 ----------
// Let's add a method to our object.  Create a method called 'age' that takes no parameters, and uses no outside variables (hint: use 'this').  The method should return the age of the pet in years.


// EXAMPLE LOG:
//    console.log("Q3: ", myPet.age());
// EXAMPLE OUTPUT:
//    Q3: 7

// PUT YOUR CODE HERE

// Don't forget your console.logs!

// ---------- QUESTION 4 ----------
// Now, let's see how we can use data within objects in functions.  Write a function called 'isDog' that takes one object parameter.  In the function, create a variable called 'speciesChecker' and assign it the value 'dog'.  Then, still in the function, return true if the object's species value is equal to the variable 'speciesChecker', or false if not.

// EXAMPLE LOG:
//    console.log("Q4: ", isDog(myPet));
// EXAMPLE OUTPUT: (if your 'myPet' object from Question 1 is about any animal other than a dog)
//    Q4: false
// NOTE: if when you made 'myPet' in Question 1, you did put dog as species, you should get true as your output instead.

// PUT YOUR CODE HERE

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
