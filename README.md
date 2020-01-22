# STA 323 :: Homework 1

## Introduction

An n-digit number that is the sum of the nth powers of its digits is called an 
n-narcissistic number. It is also known as an Armstrong number. For example,
153 is an Armstrong number since ![](https://latex.codecogs.com/gif.latex?1^3&space;&plus;&space;5^3&space;&plus;&space;3^3&space;=&space;153).
However, 25 is not an Armstrong number since ![](https://latex.codecogs.com/gif.latex?2^2&space;&plus;&space;5^2&space;\neq&space;25).

## Tasks

#### Task 1

Write a function in R called `is.armstrong()` that performs a logical test
on if a positive integer is an Armstrong number. Your function should have
at least two arguments.

Arguments:
	
- `x` takes an atomic vector of positive integers 
  (need not by of type integer) up to 999.
- `na.rm` boolean argument on whether to remove missing values or not. The
  default should be set as `FALSE`.

Make your function as robust as possible.
You may only use functions and operators available in base R.

Please use code comments as you see fit. You do not need to document every line;
there is a write-up portion in Task 3.

#### Task 2

Perform testing and validation of your function. Try the test cases provided
and include additional cases to demonstrate the robustness of your function.
This may inspire you to go back and revise function `is.armstrong()`. 
Your function should appropriately handle invalid inputs by providing an
informative error message. There will be a hidden set of test cases that will 
be used for grading purposes. The more cases your function handles in an 
appropriate manner, the better your grade will be on this assignment.

#### Task 3

Include a write-up that describes how you approached the problem and 
constructed your solution. Some things to think about and include:

- how did you check if a number is an Armstrong number;
- explain some of your code choices;
- is your function robust; and
- do you see any weaknesses with how you wrote your function;

Please keep the tasks separated in your R Markdown file.

## Essential details

#### Deadline and submission

**The deadline to submit Homework 1 is 11:59pm on Wednesday, January 29.** Only
your final commit and code in the master branch will be graded. 
Do not forget to push your work to your assigned repository on GitHub before
the deadline.

#### Help

- Post your questions in the #hw1 channel on Slack. Explain your error / problem
  in as much detail as possible or give a reproducible example that generates 
  the same error. Make use of the code snippet option available in Slack.

- Visit the instructor or TAs in office hours.

- The instructor and TAs will not answer any questions unrelated to directions
  and interpretation within the first 12 hours of this homework being assigned, 
  and they will not answer questions within 6 hours of the deadline.

#### Academic integrity

This is an individual assignment. You may communicate with others in the
course, but you must write-up your own solution. As a reminder, any
code you use directly or as inspiration must be cited.

To uphold the Duke Community Standard:

- I will not lie, cheat, or steal in my academic endeavors;
- I will conduct myself honorably in all my endeavors; and
- I will act if the Standard is compromised.

#### Grading

| **Topic**             | **Points** |
|-----------------------|-----------:|
| Task 1                |         15 |
| Task 2                |          3 |
| Task 3                |          5 |
| 3 commits minimum     |          3 |
| Code style and format |          3 |
| Named R code chunks   |          1 |
| **Total**             |     **30** |

*Documents that fail to knit after minimal intervention will receive a 0*.