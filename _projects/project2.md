---
title: Project 2
description: Spelling Bee
due: "11:59 PM PST on Thursday, 9/26"
gradescope_assignment_id: 4968690
submission_files:
    - starter.xml
---

*Version 3.0. Last Updated: 2024-09-15.*

*We highly recommend reading through this spec in its entirety before you begin.*

*[Project walkthrough guide.pdf](https://drive.google.com/file/d/1eJQpY5PpUwt3vesplElChY293NFQk4Vp/view?usp=sharing)*

## To begin, load [this starter project](https://snap.berkeley.edu/snap/snap.html#present:Username=imenguechtouli&ProjectName=BJC%20CS10%20Project%202%3a%20Spelling%20Bee&editMode&Run)

> Any important updates or clarifications will be made here.

## Content

[I. Submission Guidelines](#Submission-guidelines)  
[II. Preface](#preface)  
[III. Introduction](#Introduction)  
[IV. Part 1: "letter" Block](#)
[V. Part 2: "has letter" Block](#)  
[VI. Part 3: "uppercase" Block](#)  
[VII. Part 4: "lowercase" Block](#)  
[VIII. Part 5: "has only" Block](#)    
[IX.  Part 6: "pangram" Block](#)  
[X. Part 7: "solution" Block](#)  
[XI. Rubric](#rubric)  
[XII. Feedback Form](#feedback-form)  


## Submission Guidelines 

- Review the guidelines to learn how to export your projects and turn them in. 
- Make sure to click “Add Group Member” in the top-right corner of the screen and add your partner!
- Your final score out of X on this project is your score on Gradescope.
- Once submitted, finish Project 2 Feedback Form 


## Preface

*Do remember that while you may discuss general ideas with other students, sharing code with anyone but your partner would be academically dishonest.*

**Important: Ensure that you use the starter file we’ve linked above- do NOT create your own Snap! file for this project!**

You are NOT allowed to use explicit iteration (i.e. create for loops / repeat until loops) or recursion (which you’ll learn soon) in this project. Instead, you should rely on HOFs: specifically, `map`, `keep`, and `combine`. You are also not allowed to import any blocks.<br/> <br/>  Also, you may NOT use the built-in lowercase or uppercase blocks shown below:  <br/> <br/> ![Length of text snap block with uppercase/lowercase options](/fa24/assets/images/p2/length.png)  <br/> <br/>  You **are allowed** to use `length of text`. 

## Introduction 

In this project, you will need to collaborate with a partner to complete seven blocks in an existing program for *Spelling Bee*, a popular one-player word-guessing game. The blocks range in difficulty, with the first two being relatively easy, the middle two medium, and the last three more challenging.

In the game, the computer takes about ten seconds to generate (and solve) a hexagonally-shaped word puzzle composed of seven letters, with the center one depicted in yellow and six others on the outside. A reference photo of this puzzle display can be seen below:

![Example of the hexagonally-shaped puzzle, with the center one 'D', and six others'R, E, C, H, N, W'](/fa24/assets/images/p2/spellingbee-example.png)

To play the game, you need to create words using only the seven letters provided, and every word must include the middle letter to be considered valid. After typing your guess, press the “Return” (or “Enter”) key to submit it. Your guess will be added to the list of correct guesses if it meets the following criteria: it includes the middle letter, uses only the seven letters from the puzzle, is in the wordlist `WORDS`, and has not been guessed before.

A word that contains **ALL** the letters of the puzzle is called a **PANGRAM** and is shown in **UPPERCASE**. Each puzzle contains at least one pangram. In the original game, only words of four letters or more are allowed, so we already removed words of three letters or fewer from the `WORDS` list.

If you make a mistake, press the “Delete” (or “Backspace”) key to fix or edit your entry. To shuffle the outside letters, hit the spacebar. To see the answers at any point, press the “Option” (or “Alt”) key. To start a new puzzle, click the green “lightning bolt” button at the top right. The program is automatically set to “Turbo Mode” for faster play. If it’s off (green flag instead of lightning bolt), manually turn it back on in Settings.

We strongly encourage you to play this game on the [NY Times Spelling Bee site](https://www.nytimes.com/puzzles/spelling-bee) to get a feel for it. It’s super addictive, but sadly, you can only play once a day for free. If you want to play multiple times in one sitting, use [this link](https://freebee.fun/play/) instead. But the best part is that we are going to build an exact replica of this in Snap! that you can play and show to your friends!

If you’re having trouble, please contact the course staff for assistance — Ed, Office Hours, and Project Parties- are all here to help you feel good about the work you’re doing, or get you unstuck!

## **Part 1:** <Letter []> Block

First, you’ll build a **predicate block** (aka the “letter” block) that should report *True* iff (if and only if) the input is a single-character letter a-z or A-Z, and *False* if it is not. E.g.,

![Testcases for Part 1 Block](/fa24/assets/images/p2/P2-Part1Tests.png)

## **Part 2:** < [] has letter [] > Block 

Next, you’ll build a **predicate** (aka the “has letter” block) that should report *True* iff the first input (a word) contains the letter. E.g.,

![Testcases for Part 2 Block](/fa24/assets/images/p2/P2-Part2Tests.png)

**For this block, you may assume that both inputs will always utilize uppercase letters.**

> Pro Tip: We found the following blocks extremely useful: <br/>
![Two Snap! Blocks, Split [] by [] and <list contains[]>](/fa24/assets/images/p2/P2-Part2ProTip.png)

## **Part 3:** (uppercase word []) Block

Next, you’ll build a reporter (aka the “uppercase” block) that should report all the letters of its input (assumed to be a-zA-Z) in uppercase. E.g.,

![Testcases for Part 3 Block](/fa24/assets/images/p2/P2-Part3Test.png)

**Reminder: You may NOT use the built-in lowercase or uppercase blocks shown below:**  
 ![Length of text snap block with uppercase/lowercase options](/fa24/assets/images/p2/lengthoftest.png)

 The intention is to learn how to implement these blocks yourself. You are however, allowed to use length of text. 

> Pro Tip: We found these blocks extremely helpful <br/>
 ![Snap Blocks: `split [] by []`, `unicode () as letter`, `unicode of []`](/fa24/assets/images/p2/P2-Part3ProTip.png)


## **Part 4:** (lowercase word []) Block

Next, you’ll build a reporter (aka the “lowercase” block) that should report all the letters of its input (assumed to be a-z and A-Z) in lowercase. E.g.,

![Testcases for Part 4 Block](/fa24/assets/images/p2/P2-Part4Tests.png)

> See same **reminder** and **Pro Tip** above

## **Part 5:** < [] has only these letters [] > Block 

Next, you’ll build a predicate (aka the “has only” block) that should report *True* iff the first input word is comprised only of the letters given, and *False* otherwise. You may assume the letters are all unique. E.g.,

![Testcases for Part 5 Block](/fa24/assets/images/p2/P2-Part5Tests.png)

**For this block, you may assume that both inputs will always utilize uppercase letters.**

> Pro Tip: We found the following blocks extremely useful: <br/>
![Three Snap! Blocks, <list contains[]>, is [list] empty, and Split [] by []](/fa24/assets/images/p2/P2-Part5ProTip.png)

## **Part 6:** < [] is a pangram using all letters [] > Block 

Next, you’ll build a predicate (aka the “pangram” block) that should report *True* iff the first input word uses all of the letters given, and  otherwise. It’s ok if the first word contains letters not in the letters parameter, as in the fourth example. You may assume the letters are all unique. E.g.,

![Testcases for Part 6 Block](/fa24/assets/images/p2/P2-Part6Tests.png)

**For this block, you may assume that both inputs will always utilize uppercase letters.**

> Pro Tip: We found the following blocks extremely useful: <br/>
![Three Snap! Blocks, <list contains[]>, is [list] empty, and Split [] by []](/fa24/assets/images/p2/P2-Part5ProTip.png)

## **Part 7:** complete solution to puzzle () using words [] Block 

Next, you’ll build a reporter (aka the “solution” block) that reports the solution to the Spelling Bee puzzle given the word list. The solution is a list of words, where each word has two properties: (1) it contains the first letter of the puzzle (how we store the "center" word), (2) it only includes the letters of the puzzle. All pangrams (words that use all the letters of the puzzle) are listed in UPPERCASE. There are no limits to the number of letters in the puzzle or the number of letters in the words in the list. For the autograder to work, the words need to stay in the same order as the original word list.

![Testcases for Part 7 Block](/fa24/assets/images/p2/P2-Part7Tests.png)


## Rubric 
You have seven blocks to write, and they will be scored according to the following table; a perfect score would earn 25 points. Note that for a particular block, the test cases may have different weights. PrairieLearn’s autograder needs the number between 0 and 1, so we divided the total score by 25 to send to the autograder. You should continue to work on your code until all test cases pass and the score reported by says: {"score": 25}. 
If at any point you’d like to see more details about how we calculate that out-of-25 score, you can run the  block we provide, which reports a nicely-formatted table (with headers) showing every test case, the expected value, the actual value, how many points it is worth, and how many points you’ve earned. The sum of all the earned points is tallied in the bottom-right cell.
Note: correct, working code should handle those test cases, but not have the test cases hardcoded into your solution; they should be able to handle any inputs according to the specifications.


| Block    | Points | Function Type | Inputs | Outputs
| -------- | ------- | ------- | ------- | ------- |
| letter _   | 1    | Predicate | string | boolean
| _ has letter _ | 1    | Predicate | strings | boolean
| uppercase word _ | 2   | Reporter | string | string
| lowercase word _ | 2   | Reporter | string | string
| _ has only these letters _ | 5   | Predicate | strings | boolean
| _ is a pangram using all letters _ | 6.5   | Predicate | strings | boolean
| complete solution to puzzle _ using words _ | 7.5   | Reporter | list and string | string

## Feedback Form 
Congratulations on finish your first project in CS10🥳. Please spend some time completing this [feedback form](https://forms.gle/R7bYuwgrPRHtd3ca6). This will be worth 1 point of your project grade. Thank you!
