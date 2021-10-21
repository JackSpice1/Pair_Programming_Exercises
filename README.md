# Pair_Programming_Exercises

Problems picked from here - https://adriann.github.io/programming_problems.html

It might be good to start with an easier problem that you have the best chance of completing. From there you can either iterate on your solution or move on to a harder problem.

Feel free to be creative with the problems. They are meant to be a starting point for the exercise. Adjust the criteria as you see fit. Add requirements, remove some. Change them. It's up to you.

# Beginner - Guessing Game 

> #1 Write a guessing game where the user has to guess a secret number. After every guess the program tells the user whether their number was too large or too 
>small. At the end the number of tries needed to guess should be printed. It counts only as one try if they input the same number multiple times consecutively.

> #2 Write a program that asks the user for a number `n` and prints the sum of the numbers `1` to `n`.
Example: User provides `6`. The program would calculate the sum - `1 + 2 + 3 + 4 + 5 + 6 = 21`
Thoughts: Start with a hard-coded number and get the addition working. From there move to getting user input.

# Intermediate

> #1 Write a function that takes a list of strings and prints them, one per line, in a rectangular frame. 

Example: The list `["Hello", "World", "in", "a", "frame"]` gets printed as:

```
*********
* Hello *
* World *
* in    *
* a     *
* frame *
*********
```

Thoughts: Input could either be hard-coded, or user supplied via a file of command line, etc. To add difficulty to the problem, you could ask the user if they'd like their words let aligned or right aligned. (Center aligned for even more difficulty.) 

> #2 Write a program that plays 'Spaceman'. In this game, the player must guess a mystery word represented by dashes by selected letters they think make up that word. 
 
Thoughts: You can use a large dictionary like this and select the letter that excludes most words that are still possible solutions. 
Try to make the program as efficient as possible, i.e. don’t scan the whole dictionary in every turn.

> #3 Write a program that outputs all possibilities to put + or - or nothing between the numbers 1,2,…,9 (in this order) such that the result is 100. For example 1 + 2 + 3 - 4 + 5 + 6 + 78 + 9 = 100.

# Hard Scrable Score

Write a program that, given a word, computes the scrabble score for that word.

## Letter Values

You'll need these:

```plain
Letter                           Value
A, E, I, O, U, L, N, R, S, T       1
D, G                               2
B, C, M, P                         3
F, H, V, W, Y                      4
K                                  5
J, X                               8
Q, Z                               10
```

## Examples
"cabbage" should be scored as worth 14 points:

- 3 points for C
- 1 point for A, twice
- 3 points for B, twice
- 2 points for G
- 1 point for E

And to total:

- `3 + 2*1 + 2*3 + 2 + 1`
- = `3 + 2 + 6 + 3`
- = `5 + 9`
- = 14

## Extensions
* You can play a `:double` or a `:triple` letter.
* You can play a `:double` or a `:triple` word.

## Source

Inspired by the Extreme Startup game [view source](https://github.com/rchatley/extreme_startup)
  
