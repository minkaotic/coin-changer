# Solving the Coin Changer kata in C#

The aim of the exercise is to produce the minimal amount of change for a given monetary amount.
The currency unit used will be GBP pence.

For instance, If the input is: 99 pence, the output should be: one 50 pence coin, two 20 pence coins, one 5 pence coin and 2 two pence coins. The output can be something as simple as 50, 20, 20, 5, 2, 2 which is the same as 99 pence.


## 3 Rules of TDD to have in mind for solving the exercise
1. You are not allowed to write any production code unless it is to make a failing unit test pass
1. You are not allowed to write any more of a unit test than is sufficient to fail
1. You are not allowed to write any more production code than is sufficient to pass the one failing unit test
