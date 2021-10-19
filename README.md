# CS361-ADV-ALGORITHMS-DATA-STRUCTURES---Homework03

In this assignment the professor provided us with an almost working version of the guessing game, "20 Questions"". Our asignment was to implement the input and output functions for the question tree. Both the input and the output algorithms resemble tree traversal algorithms. The user acts as `player 1` and provides the input file, as well as answers to the yes-or-no questions. Meanwhile, the program acts as `player 2` guessing the answer based off the input provided by `player 1`. The input file contained several lines, each describing a single question or answer. An input line begins with either 'Q' or 'A', followed by one or more whitespaces, to indicate whether it is a question or answer. Each 'Q' is immediately followed by lines describing its "yes" descendants, then lines describing its "no" descendants.

Example:
* Q Does it live in water?
* Q Does it have webbed feet?
* A Duck
* A Fish
* A Cat
