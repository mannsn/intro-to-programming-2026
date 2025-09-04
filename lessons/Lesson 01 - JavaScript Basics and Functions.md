# Problem Solving

<details>
  <summary>Click this link to expand/collapse the content about Problem Solving</summary>
  
  ### The following is an excerpt from The Odin Project's Problem Solving page.  We've extracted the parts from that content that you need.  Please read the following content...

### Introduction
Before we start digging into some pretty nifty JavaScript, we need to begin talking about *problem solving*: the most important skill a developer needs.

Problem solving is the core thing software developers do. The programming languages and tools they use are secondary to this fundamental skill.

V. Anton Spraul defines problem solving in programming as:

> "Problem solving is writing an original program that performs a particular set of tasks and meets all stated constraints."
- Think Like a Programmer

The set of tasks can range from solving small coding exercises all the way up to building a social network site like Facebook or a search engine like Google. Each problem has its own set of constraints, for example, high performance and scalability may not matter too much in a coding exercise but it will be vital in apps like Google that need to service billions of search queries each day.

New programmers often find problem solving the hardest skill to build. It's not uncommon for budding programmers to breeze through learning syntax and programming concepts, yet when trying to code something on their own, they find themselves staring blankly at their text editor not knowing where to start. 

The best way to improve your problem solving ability is by building experience by making lots and lots of programs. The more practice you have the better you'll be prepared to solve real world problems.

In this lesson we will walk through a few techniques that can be used to help with the problem solving process.

### Learning Outcomes
By the end of this lesson, you should be able to do the following:

* Explain the three steps in the problem solving process.
* Explain what pseudo code is and be able to use it to solve problems.
* Be able to break a problem down into subproblems.

### Understand the Problem
<span id="problem-solving-stages"></span>
The first step to solving a problem is understanding exactly what the problem is.<span id="important-understand-problem"> If you don't understand the problem you won't know when you've successfully solved it and may waste a lot of time on a wrong solution</span>.

<span id="help-understand-problem">To gain clarity and understanding of the problem, write it down on paper, reword it in plain English until it makes sense to you, and draw diagrams if that helps. When you can explain the problem to someone else in plain English, you understand it.</span>

### Plan
Now that you know what you're aiming to solve, don't jump into coding just yet. It's time to plan out how you're going to solve it first.
<span id="planning-stage"></span>
Some of the questions you should answer at this stage of the process:

* Does your program have a user interface? What will it look like? What functionality will the interface have? Sketch this out on paper.
* What inputs will your program have? Will the user enter data or will you get input from somewhere else?
* What's the desired output?
* Given your inputs, what are the steps necessary to return the desired output?

The last question is where you will write out an algorithm to solve the problem. <span id="algorithm">You can think of an algorithm as a recipe for solving a particular problem. It defines the steps that need to be taken by the computer to solve a problem in pseudo code.</span>

### Pseudo Code
<span id="pseudo">Pseudo code is writing out the logic for your program in natural language instead of code. It helps you slow down and think through the steps your program will have to go through to solve the problem.</span>

Here's an example of what the pseudo code for a simple program that prints all numbers up to an inputted number might look like:

~~~
When the user inputs a number
Initialize a counter variable and set its value to zero
While counter is smaller than user inputted number increment the counter by one
Print the value of the counter variable
~~~

This is a very simple program to demonstrate how pseudo code looks. There will be more examples of pseudo code included in the assignments.

### Divide and Conquer
From your planning, you should have identified some subproblems of the big problem you’re solving. Each of the steps in the algorithm we wrote out in the last section are subproblems. Pick the smallest or simplest one and start there with coding.

It's important to remember that you might not know all the steps that you might need up front, so your algorithm may be incomplete -— this is fine. Getting started with and solving one of the subproblems you have identified in the planning stage often reveals the next subproblem you can work on. Or, if you already know the next subproblem, it’s often simpler with the first subproblem solved.

Many beginners try to solve the big problem in one go. **Don’t do this**. <span id="breaking-problem">If the problem is sufficiently complex, you’ll get yourself tied in knots and make life a lot harder for yourself. Decomposing problems into smaller and easier to solve subproblems is a much better approach. Decomposition is the main way to deal with complexity, making problems easier and more approachable to solve and understand.</span>

In short, break the big problem down and solve each of the smaller problems until you've solved the big problem.


</details>

# Javascript Basics

**You can _either_ use the written Odin Project lessons _or_ the video lessons in Scrimba. You can do both if you have them time and want to, but using just one or the other will teach what is needed to complete the coding assignments.**

For the Odin Project, Go to each link in this list and read through the content on that page. If there are links you are redirected to as you read/work through the content, follow those links as well and read the content there too.

### Odin Project

- [The Odin Project – Fundamentals Part 1](https://www.theodinproject.com/paths/foundations/courses/foundations/lessons/fundamentals-part-1)
- [The Odin Project – Fundamentals Part 2](https://www.theodinproject.com/paths/foundations/courses/foundations/lessons/fundamentals-part-2)
- [The Odin Project – Fundamentals Part 3](https://www.theodinproject.com/paths/foundations/courses/foundations/lessons/fundamentals-part-3)

### Scrimba

- [V2 Scrimba - JS Deep Dive - Variables and Strings](https://v2.scrimba.com/javascript-deep-dive-c0a/~04)
- [V2 Scrimba - JS Deep Dive - Types & Conditionals](https://v2.scrimba.com/javascript-deep-dive-c0a/~0g)
- [V2 Scrimba - JS Deep Dive - Functions](https://v2.scrimba.com/javascript-deep-dive-c0a/~0q)

# Javascript Naming and Style Conventions

- [Naming and Style Conventions](https://raw.githubusercontent.com/Code-the-Dream-School/intro-to-programming-2026/refs/heads/main/assets/Lesson01/Lesson01-Naming-Conventions.md?raw=true)

# Debugging Basics

- [Debugging Basics](https://raw.githubusercontent.com/Code-the-Dream-School/intro-to-programming-2026/refs/heads/main/assets/Lesson01/Lesson01-Debugging-Basics.md?raw=true)

**_TBD Video and Lesson Section on debugging basics_**

# Software Repositories

A software repository, often called a "repo", is a centralized storage location for code and related files used in software development. Software repositories allos developers to track changes to code, revert to previous versions of code and merge different branches of development.

Software repositories are especially important on projects being developed by a software team where multiple people are working on the same code base. This is true for the majority of software projects.

There are many cloud based software repositories. In this class we will use GitHub which is based on git which is a distributed version control system. We will learn more about git in lesson 2.

**_TBD Video - Create a new repository on Github_**

## Assignment - Create a New GitHub Repository
Create a new repository in your GitHub account by following these steps:

- [ ] Go to your GitHub page and click the Repositories tab
- [ ] Click the green "New" button in the top right
- [ ] Fill in the fields to give your repository a name (use your name-**_classname_** as the name example: `maria-santiago-jupiter`) and description (example: portfolio project for Intro to Programming course with Code the Dream)
- [ ] Be sure PUBLIC is selected and check the "Initialize this repository with: Add a README file" check box.
- [ ] Click "Create Repository"

