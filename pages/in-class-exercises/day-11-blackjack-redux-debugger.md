# Day 11: Blackjack Redux, Debugger

## Peer-Led Code Review \(with Debugger\)

Review your partner's code as per [Peer-Led Code Review instructions](../course-logistics/course-methodology.md#peer-review). Complete the [Debugger section](day-11-blackjack-redux-debugger.md#debugger) below before implementing new features together. Once both have a working game, work on [More Comfortable](day-11-blackjack-redux-debugger.md#more-comfortable) on one person's code.

## Code Review

On days when projects are due, we will review each others' code in groups of 2 or 3 during class. If there is a group of 3, the triplet will do individual code review together so that everyone gets to review someone else's code, then split into 2 groups for pairing.

### Individual Review

#### 0\) Push Your Own Code

Refer to the [push section](../7-github/7.1-github-fork-and-pull-request.md#git-push) for the commands needed for this. 

#### 1\) Clone Partner's Code

You'll be paired up so that you can exchange the links for your repos via Slack. Remember that the forked repo is the one that is under your GitHub account, not Rocket Academy's. If you have forked the repo but haven't pushed your latest code to GitHub, take a moment now to `git push`. Let your partner know you're updating the repo. Run a `git clone <REPO_URL> <NEW_FOLDER_NAME>` to get a copy of your partner's code.

 
Note: You need to rename the folder when you clone if you already have a folder named after the repo where you're making the clone.
 

#### 2\) Run Partner's Code

Open the code in the browser and test it. What does it do? If you're not sure what it does look inside `script.js` to see.

#### 3\) Read Partner's Code

Read the code and answer the following questions.

1. How does it work?
2. Does it have any obvious errors?
3. Does it implement something that you were trying to do?
4. Does it implement a feature that you haven't started yet? How does the code work?

#### 4\) Play with Partner's Code

It may be helpful to make changes to the code to help you understand it better. Write some `console.log` that would help you figure out what the code does. Break the code in a certain way to prove how it works or doesn't work.

#### 5\) Discuss

Once both partners are done with \#1-4, discuss what you saw.

### Peer Review

You'll be pair programming on one person's project at a time. The goal is to get working versions for each person. **The driver will be the person who is \*not\* working on their own code.** 

Once done with one person's code, send the code to your pair \(it's their project\) via a [Slack code snippet](https://slack.com/intl/en-sg/slack-tips/share-code-snippets). Switch to work on the other person's code.

 
Note: If you are working on your partner's code you can't push to their repo because GitHub repos are read-only to non-owners by default.
 

If you both have working versions, implement a new feature in one of the projects together.

## Debugger

Practice using the debugger on the game. Please switch driver so that each person gets a chance to set the debugger on their own computer.

### Someone Else's Code

Use the debugger to see into the code.

1. Create `console.log`s before and after where the cards are swapped in the shuffle function. Set the breakpoints on the `console.log`s.
2. If the code is using the deck generation function, set a breakpoint in the code where it pushes the individual card object into the deck array.

### Your Own Code

Switch to use the debugger on your own code.

1. Set a breakpoint inside the main part of the game when the cards are being dealt.
2. If you have an error, set a breakpoint to investigate the error.



## More Comfortable

Implement [More Comfortable exercises](../projects/project-3-blackjack.md#more-comfortable) in the project writeup. Once done, push your code to update your pull request in GitHub.

