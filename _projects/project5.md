---
title: Project 5
description: Pyturis
due: "11:59 PM PST on Thursday, ???"
submission_files:
    - project folder or individual files
---

*Version 1.0. Last Updated: 2024-10-31.*

*We highly recommend reading through this spec in its entirety before you begin.*

*[Project walkthrough guide.pdf]()*

> Any important updates or clarifications will be made here.

## Content

[I. Submission Guidelines](#submission-guidelines)  
[II. Intoruction](#introduction)  
[III. Part 0: Set Up](#preface)  
[IV. Part 1: Board](#Introduction)  
[V. Part 2: Pytromino](#)
[VI. Rubrics, Grading and Submission](#)  
[VII. Appendix: Pyturis Game Rules](#)


## Submission Guidelines 
To run the PrairieLearn autograder, you'll need to submit models.py and board.py to the assignment titled *Pyturis* on **PrairieLearn**. You can either submit these filed individually or submit the entire project folder to the PL assignment, as irrelevant files will be filtered and not processed automatically. 

## Introduction

### Brief 

![Testcases for Part 1 Block](/fa24/assets/images/p2/P2-Part1Tests.png)

In this project, you’ll code the game Tetris in Python, with the Turtle library rendering the graphical user interface (GUI). Python + Turtle + Tetris = Pyturis! This game involves fitting blocks called “pytrominoes'' together to fill and clear horizontal lines.
When you’ve correctly implemented all the required functions, you’ll be able to play Pyturis on a screen that looks like the one to the right.

### Preliminaries

You’ll need to have watched the Python lectures to complete this project. We also highly recommend completing Lab 13: Intro to Python before starting this project to get acquainted with Python and a text editor. Lab 14: Lists + Mutability and Lab 15: Data Structures in Python may help your understanding of how to use lists in Python, and Lab 16: OOP in Python offers a helpful tutorial with object-oriented programming (OOP) in Python, which is the basis of this project.


**We require you to complete this project with a partner. **

### Goal 

The goal of this project is to provide an opportunity for practicing working with object-oriented programming (OOP) in Python by building a practical program with a structure that mimics real-world projects. In this project, you’ll:
- practice working with row-major order (a common model for board structures, similar to the new 4x4 board with values block you used in Project 3)
- learn how to implement and work on either side of an abstraction barrier
- become familiar with using and extending an existing codebase rather than starting from scratch

### TODO 

All of the files you’ll need to implement are marked in the files with TODO: your solution here, which you can search for with CTRL+F when you open the starter code in your preferred text editor. You can play a few games of [Tetris](https://tetris.com/games-content/play-tetris-content/index-mobile.php#google_vignette) here, or read [this additional section](#appendix:-pyturis-game-rules) of the spec to become familiar with the game rules. If you’re writing more than 10 lines of code for any function, we recommend you consider other ways to achieve what you’re trying to do, or take a break and head to OH for assistance!



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
