# super-palm-tree
## Brief
We are thrilled to see what you can do. You have come far. The following is a backend exercice that you may write in any language you like, such as python, js, c++, you name it.

### Rules
* **Dont** use AI, or copy pase from StackOverflow, we will know.
* **Do** use documentation available on the internet like MDN or ECMAScript2023.

### What are we looking for?
* We dont care if you take a lot of time.
* We want to see your ability to solve problems and rationalize.

### How to submit
You can either fork this repo and share it to us, however we suggest you share us a [Replit](https://replit.com/) so we can reproduce and code easely during our interview.

## Exercice #1 - Parallel Sums
Have the function ParallelSums(arr) take the array of integers stored in arr which will always contain an even amount of integers, and determine how they can be split into two even sets of integers each so that both sets add up to the same number. If this is impossible return -1. If it's possible to split the array into two sets, then return a string representation of the first set followed by the second set with each integer separated by a comma and both sets sorted in ascending order. The set that goes first is the set with the smallest first integer.

For example: if arr is [16, 22, 35, 8, 20, 1, 21, 11], then your program should output 1,11,20,35,8,16,21,22

## Exercice #2 - Pattern Chaser
Have the function PatternChaser(str) take str which will be a string and return the longest pattern within the string. A pattern for this challenge will be defined as: if at least 2 or more adjacent characters within the string repeat at least twice. So for example "aabecaa" contains the pattern aa, on the other hand "abbbaac" doesn't contain any pattern. Your program should return yes/no pattern/null. So if str were "aabejiabkfabed" the output should be yes abe. If str were "123224" the output should return no null. The string may either contain all characters (a through z only), integers, or both. But the parameter will always be a string type. The maximum length for the string being passed in will be 20 characters. If a string for example is "aa2bbbaacbbb" the pattern is "bbb" and not "aa". You must always return the longest pattern possible.
