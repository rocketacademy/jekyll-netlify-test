# Day 1: Coding Tools

## Overview

The first meeting of the course sets the tone for the rest of the sessions.

This day has a heavier section of content than the other days so be prepared for the review portion to take a bit longer. There may also be setup questions.

**Some things to keep in mind overall for the first meeting:**

Always encourage questions from the students.

Running on time is important. Respect people's time- begin the session on time and don't end after 9.

Sorting out setup problems from students \(with VSCode or the terminal or folders\) will be an issue on the first meeting. Unless you know for sure that it is a quick fix, don't spend any time in front of everyone to fix one person's problem. Either wait until the pairing or, even better, wait to meet with them after the session.

## Pre-Class Material

Total Video Watch Time: **~48 mins**

## [1.1: What is Coding?](../../1-introduction/1.1-what-is-coding.md)

### Overview:

This section is to get the students thinking about the high level context of what the course is about.

### Discussion questions:

Ask one or two students to answer the exercise questions.

Possible answers:

AirPods

Input: Opening the case. Output: starting to play sound.

An office building

Input: a change of temperature inside. Output: run AC at higher or lower level.

Car engine

Input: Readings from engine sensors. Output: instructions to the engine parts \(i.e., fuel injectors, etc.\)

## [1.2: Web Browsers](../../1-introduction/1.2-web-browsers.md)

### Overview

This section moves one level lower in the context of how the course runs. The students should understand that the only way to run the `script.js` file is to run the HTML file.

### Discussion questions:

Did you know that basically every single thing you view in the browser window is HTML?

Show this by opening a random webpage in the browser and right clicking **View Page Source**.

## [2.1: Command Line](../../2-organising-and-managing-code-files/2.1-command-line.md)

### Overview

We are mainly doing the command line so that the students can use Git. The students also get some benefit from understanding how to use the computer in a more strict, programmer-focused interface.

### Discussion questions:

Q: What is the command line?

Q: Why are we learning the command line?

A: We need to sue the command line to use Git.

## [2.2: Git](../../2-organising-and-managing-code-files/2.2-git.md)

### Overview

Using Git is important for the students to do their work. At this stage is some are a bit confused this is ok, some understanding will come through practicing the commands.

### Discussion questions:

#### Q: What is Git for?

A: Git is used to save all the different versions of the program we are going to create..

Q: How would you define the difference between Git and the terminal?

#### A: Git is a program you use \*inside\* the terminal. The terminal is the computer interface where you \*run\* programs.

#### Student FAQ

#### Q: How do I get a previous version back?

A: There are specific Git commands for that, but it is out of the scope of the course. When we cover the section 7.2 on browsing GitHub we'll see how we can navigate and copy and paste a previous version.

### [3.1: Operations](../../3-basic-data-manipulation/3.1-operations.md)

### Overview

This section is relatively intuitive. It is important to establish here that an **operation** is the smallest bit of computation we can start with. All other code we'll write stems from doing operations, though they may not all be with integers.

## [3.2: Variables](../../3-basic-data-manipulation/3.2-variables.md)

### Overview

From operations we add in variables. Here it is important to re-emphasise the concept of accurate representation vs correct calculation.

#### Q: Why is variable naming important?

A: Accurate representation is just as important as correct calculation.

## [4.1: Intro to GitHub](../../4-getting-started-with-code/4.1-intro-to-github.md)

### Overview

It is a common misconception to confuse what Git and GitHub are responsible. To help we separate the two sections explicitly.

### Discussion Questions

#### Q: What does a GitHub fork do?

A: It copies a cloud \(remote\) repo from one GitHub account into your own account.

## [4.2: Our First Program](../../4-getting-started-with-code/4.2-our-first-program.md)

#### Overview

This is the first introduction on the starter code. Some students will have some questions about what the main function is, but keep in mind that functions will be covered in the next section.

Be ready to demonstrate this code for the students and have it setup in case you need to demonstrate anything related to their questions.

#### Discussion Questions

```javascript
console.log('papaya');

var main = function (input) {
  var myOutputValue = 'hello world';
  return myOutputValue;
};
```

#### Q: When I type something in the input in the browser how do I get it to display in the grey box?

#### Q: I want to write a program so that I can type a number in the input and then click the submit button and see that number multiplied by 12 in the grey box. For example, I type in 2, I see 24 in the grey box.

#### Q: To add on to the previous question, I also want to see the number I typed in inside the greay box, in a full sentence. Example: I type in 2. I click submit. In the grey box I see: "_You typed in 2. The result is: 24."_

## In-Class Material

#### [Day 1: Basic File and Data Manipulation](../../in-class-exercises/day-1-basic-file-and-data-manipulation.md)

#### Overview

This is the first pairing exercise the students will do. Set the tone for the exercise because this is the first time students have heard of pairing.

You might touch on the following points:

Pairing only works when both people are willing to commit to the experience and be open to learning from the other person and / or patiently explaining what the other person may not be familiar with.

Be coachable. Make an effort to listen well when someone wants to explain something.

Teaching is the best way to understand something deeply. Try to give the clearest explanations possible. This can be very difficult but will really cement a concept.

#### Things to look out for in the pairing session:

It's important that everyone is on the same page with the setup and command line / Git sections. Some will not be completely setup yet. It is better to spend the pairing time to clear up any misconceptions or setup errors now so the students can move forward easily.

Look out for people who don't have things setup according to the guidelines, such as:

* no folder structure setup ahead of time
* using a browser other than chrome
* using some other setup besides the starter code like codepen.io

Be clear with the students that it's important to follow along with the setup as outlined so that in pairing everyone begins with the same context.

Keep note of any students who already seem lost or confused.

## **Look Ahead / Wrap-up**

Our code doesn't do too much yet, we've named some values and done some calculations. THis is just the beginning. Next we'll see functions, which is a kind of control flow, a way to specify which groups of lines of code runs. We'll use this to build up our programs in pieces. After that we'll begin to talk about program logic with conditionals.

