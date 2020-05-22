#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)O(n)----While loop will run n times so 0(n).


b)O(n log n)----Outer loop runs n time and inner looops runs n log(n).


c)O(n)----Funtion will recurse n times until it reaches base case so 0(n).

## Exercise II
<!-- Suppose that you have an n-story building and plenty of eggs. Suppose also that an egg gets broken if it is thrown off floor f or higher, and doesn't get broken if dropped off a floor less than floor f. Devise a strategy to determine the value of f such that the number of dropped + broken eggs is minimized.

Write out your proposed algorithm in plain English or pseudocode AND give the runtime complexity of your solution. -->

This will be Binary Search Runtime O(log n).

Start at ground floor
Go to the middle and drop the egg if it breaks go to the middle floor from where you are and the ground
if the egg does not break move to the middle floor between where you are and the top floor
Conntinue that untill you find what floor the egg does not break and and that will be floor f.
Will reduce the ammount of droped eggs and reduce the amount of broken eggs. 



