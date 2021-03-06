# cs101
My own notes from CS101 course in Udacity.

Programs are instructions for machines to perform computation.
Python programs are interpreted by yet another program (the Python interpreter) to get the computer to do stuff.
Programming languages eliminates ambiguity and verbosity (using more words than necessary) to get instructions across.
Backus-Naur Form (BNF) is a formal notation to describe the syntax of a given language.

General guide to solving problems:

0. Understanding the problem
  Problems are defined by a set of possible inputs and the relationship between the inputs and outputs.
  Solutions to problems are the procedure that produces outputs from the set of inputs.
1. Identify the inputs
  What are the inputs, number of inputs, limits on inputs (set of possible valid inputs)?
  How are inputs represented?
2. Identify the outputs
  Similarly, decide what are the outputs, and how they are represented, and the set of possible valid outputs.
3. Identify test cases
  Test cases helps you to understand the relationship between inputs and outputs.
  Test cases basically specify the inputs and the expected outputs for the procedure, for a smaller subset of all possible inputs.
4. Consider a systematic approach to produce the output from the input
  Consider how a human may solve it.
  Try the approach on simple test cases and harder test cases.
  Create the pseudocode for the algorithm.
  Find simpler ways and simpler algorithm to solve the problem.
  Do not attempt to optimise prematurely. That comes later.
5. Divide and Conquer
  Split the procedure up into sub procedures and implement them one at a time.
  This reduces error, keeps the problem simple, and makes each component easy to test and code.
  Incrementally create the procedure and test, until a full solution is produced.

Aliasing are assignments refering to the same objects. Any mutation to the object from one assignment will be reflected when referenced from the other assignments.

Procedures allow codes to be used repeatedly.
Procedures can be defined as well-defined sequence of steps that can be exceuted mechanically. Procedures take in some inputs and produces results as outputs.
Algorithms are Procedures that are guaranteed to always finish and produce the correct results.
Algorithms are compared and measured based on the time and memory cost relative to size of input to the algorithm.

Recursive definition requires a base case that is defined by a basic input, and a recursive case that is defined in terms of itself.
A problem can be solved by recursion using relaxation. By limiting the number of recursion, from a starting point determined by guesswork, the procedure can be gradually adjusted to provide better solution.

There are 3 main themes to Computer Science:
1. Abstraction - hiding details
2. Universality - functionality can be used generally in all cases
3. Recursive Definition - to build complex systems from smaller components

