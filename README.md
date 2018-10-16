# Multi-Armed Bandit algorithm solutions on advertisement data

~ Added in code for Epsilon-Greedy strategy and fixed issue for python division where integers and floats are handled property ~

Continued work based on code/concepts covered in https://www.analyticsvidhya.com/blog/2018/09/reinforcement-multi-armed-bandit-scratch-python/#comment-155315 that aims to apply the Multi-Armed Bandit algorithm to online advertising.

This Jupyter Notebook contains 3 solutions to the Multi-Armed Bandit Problem (MABP), which are random selection, epsilon-greedy, and upper confidence bound (most optimal).

In terms of regret (a.k.a. the loss that is obtained over time due to opportunity cost of learning, or exploring, compared to exploiting), the upper confidence bound solution yields a log(n) complexity for regret while the others yield linear complexity with varying slopes.

The sample dataset used is based on 10 different ads targeted towards a particular group of users on a website. The columns represent different ads (1-10) and the value in each cell represents if the add was clicked (1) or not clicked (0). This dataset can be found here - https://drive.google.com/file/d/1whkIInL4FKeHg2IfdcbT1j18L26fg9aF/view


