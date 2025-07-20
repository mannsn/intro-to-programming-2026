**NOTE: If the CodeSandbox file gets updated, the code example below may not be up to date.  You can confirm the most recent version of this assignment by clicking this:**
[Link to CodeSandbox Assignment](https://codesandbox.io/p/sandbox/lesson-3-javascript-objects-2025-hr9j68?file=%2Fsrc%2Findex.mjs)

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

// ---------- QUESTION 1 ----------
// Objects are a way to store property:value pairs of data in a variable.  First, create an object called 'myPet'.  Add three properties called 'name', 'species', and 'color' to the 'myPet' object below and assign each of them values.  Use your console.log's to print the values of each property to the console.

// EXAMPLE LOG:
//    console.log("Q1 name: ", myPet.name);
//    console.log("Q1 species: ", myPet.species);
//    console.log("Q1 color: ", myPet.color);
// EXAMPLE OUTPUT:
//    Q1 name: Teddy
//    Q1 species: ferret
//    Q1 color: brown

// PUT YOUR CODE HERE

// ---------- QUESTION 2 ----------
// Now let's see how we can use the property:value pairs in template literals.  Create a variable called 'aboutPet' and assign it a template literal that uses the 'myPet' object to make a sentence sharing all the pet details.  The sentence should look something like this: "Teddy is a brown ferret."

// EXAMPLE LOG:
//    console.log("Q2: ", aboutPet);
// EXAMPLE OUTPUT:
//    Q2: Teddy is a brown ferret.

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


// ---------- QUESTION 5 ----------
// Let's see how to use a callback.  First, create a function that simulates pushing a button.  Name the function buttonPushed and log the message "The button was pushed!" in the function.

// EXAMPLE CALL: (the log is within the function, so you do not need to log the call)
//    buttonPushed();

// EXAMPLE OUTPUT:  
//   The button was pushed!

// PUT YOUR CODE HERE


// ---------- QUESTION 6 ----------
// Now, create a function called simulateButtonPush and pass the function created in step 5 to that function.

// EXAMPLE CALL: (the log is within the function, so you do not need to log the call)
//    simulateButtonPush(buttonPushed);

// EXAMPLE OUTPUT: (if your 'myPet' object from Question 1 is about any animal other than a dog)
//   The button was pushed!

// PUT YOUR CODE HERE

```
