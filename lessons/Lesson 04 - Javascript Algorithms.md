

This week we are going to look at algorithms.  An algorithm sounds like it might be something hard and complex, but it really is just a set of steps that you are going to code in order to accomplish an end goal. An algorithm is just a set of step-by-step instructions written in Javascript to solve a specific problem or performa  task.


TBD - add more about functions here ??

TBD - maybe add more about testing / edge cases here?


## **Callbacks**

Callbacks are functions that you provide to another function or system to be executed when a certain condition or event occurs. They are a way of saying, "Hey, when this thing happens, do this specific task.”

Here is some additional information on callbacks:
https://www.w3schools.com/js/js_callback.asp

Imagine you have a button on a website, and you want something to happen when the button is clicked. You could create a callback function that specifies what should happen when the button is clicked. This callback function is then associated with the button.

```jsx
// A function that adds two numbers and uses a callback to return the result
function addNumbers(a, b, callback) {
  const result = a + b;
  callback(result);
}

// Define a callback function to handle the result
function handleResult(result) {
  console.log("The result is: " + result);
}

// Call the addNumbers function with a callback
addNumbers(5, 3, handleResult);
```

In this example, the **`addNumbers`** function takes two numbers **`a`** and **`b`**, adds them together, and then calls a provided **`callback`** function with the result. The **`handleResult`** function is the callback, and it prints the result to the console.

This demonstrates how callbacks can be used to pass control from one function to another, allowing you to specify what should happen after a specific operation (in this case, addition) is complete.

Watch this video on the mistake with functions every developer makes, because remember **making mistakes is a great way to learn!** [YouTube Video Link](https://www.youtube.com/watch?v=7UMuJMiNjSk&t=98s)

Callbacks are a versatile and powerful concept in programming, and they can be used in various scenarios. Here are some common situations where callbacks are useful:

1. **Asynchronous Operations:** Callbacks are often used with asynchronous operations, like making network requests, reading files, or interacting with databases. They allow you to specify what should happen when the operation is completed without blocking the rest of your program.
2. **Event Handling:** In user interfaces, callbacks are used to respond to user interactions such as button clicks, mouse movements, or keyboard input. You define a callback function that gets triggered when the event occurs.
3. **Modular and Reusable Code:** Callbacks make it easier to write modular and reusable code. You can create functions that accept callbacks to perform specific tasks, allowing you to reuse those functions with different behaviors depending on the callback provided.
4. **Iterations and Loops:** Callbacks can be used in iterations and loops to execute a function for each element in a collection, like an array or a list. This is known as "callback-based iteration."
5. **Promises and Promisified Code:** In JavaScript, promises often work with callbacks to handle asynchronous tasks more cleanly. Promises provide a structured way to handle callbacks and make asynchronous code easier to read and maintain.

Overall, callbacks are a fundamental building block in software development, enabling you to define what should happen when a particular event or operation occurs, making your code more flexible, modular, and responsive.

We will be covering all these aspects of the uses of callbacks in later lessons, but it is important to understand how they work at a very basic level.


## OPTIONAL: **Data Structures**
This section is useful for students who plan to take Python or Node

TBD


