# PairProgrammingEx

## Overview
This is a simple program for reading exercises from a file, allowing the user to input their answers, and then checking those answers against the correct ones.

## User Interaction
 - The program will display each exercise from the file and prompt the user to input their answer.
 - After entering answers for all exercises, the program will display the number of correct answers and list any incorrect answers.
 - The user will then be prompted to continue answering questions or quit.
     
## File Description
 - `main.py`: Contains the main Python script for the exercise checking program.
 - `result.txt`: Sample input file containing exercises and correct results.

## Functionality
 - `file_reader()`: Reads exercises from the input file and prepares them for processing.
 - `addDecision(exercise_list)`: Allows the user to input their answers for each exercise.
 - `compare(exercise_list, counter)`: Compares the user's answers with the correct results and counts correct answers.
 - `printWrongAnswers(exercise_list)`: Prints exercises for which the user's answer was incorrect.
 - `makeChoice(exercise_list)`: Prompts the user to continue answering questions or quit.
 - `main()`: Orchestrates the execution of functions and controls the program flow.    

## Contributors
 - [giu-lio](https://github.com/giu-lio)
 - gelato0o
