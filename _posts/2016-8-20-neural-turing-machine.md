---
layout: post
title: Neural Turing Machine
description: NTM large scale parenthesis matcher
image: assets/images/ntm_clr_invert.png
redirect_url: https://github.com/sankhoroy/Neural-Turing-Machine/blob/master/NTM%20large%20scale%20parenthesis%20matcher.ipynb
---

# Neural Network learns parenthesis matching problem
**Scenario:**
Given an expression string expression , write a program to examine whether the pairs and the orders of '(' or ')' are correct in expression For example, the program should print true for expression ((()(())))() and false for expression ()))

*Naive algorithm for parenthesis matching involves 4 steps*<br>

**Old School Algorithm:**
- Declare a character stack S.
- Now traverse the expression string exp.
    - If the current character is a starting bracket ('(' ) then push it to stack.
    - If the current character is a closing bracket (')' ) then pop from stack and if the popped character is the matching starting bracket then fine else parenthesis are not balanced.
- After complete traversal, if there is some starting bracket left in stack then “not balanced”
In the following pictures we will see initial tour of points given in orange line
and optimized solution will be in orange line.i.e Our solution path should be as short as possible<br>

**What Neural Network does,** it learns algorithm instead of pattern of brackets and determines whether its more probable to be open or a closed parenthesis.

**Neural Turing Machine Algorithm :**
- We will feed input bracket sequence and output (0 or 1 ) if it is matched parenthesis or not.
- After some examples we feed it will learn the algorithm and *able to detect parenthesis sequence is matched or not.*


