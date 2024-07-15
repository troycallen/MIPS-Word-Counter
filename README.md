# Shakespeare Word Analyzer and Counter

## Overview
This MIPS assembly program analyzes a given Shakespearean dialogue to find and count words containing a specific target string. It demonstrates string manipulation, word parsing, and list management in MIPS assembly language.

## Features
- Searches for words containing a target string (default: "th")
- Identifies unique words in the text
- Counts the number of unique words containing the target
- Outputs a list of found words and their count

## Main Components
1. `main`: Entry point of the program
2. `findwords`: Core subroutine that processes the text
3. `hastarget`: Checks if a word contains the target string
4. `isunique`: Verifies if a word is unique in the found list
5. `strcmp`: Compares two strings
6. `isletter`: Determines if a character is a letter

## Input
- A predefined Shakespearean dialogue stored in the `.data` section
- A target string (default: "th")

## Output
- A list of unique words containing the target string, each on a new line
- The count of unique words found


## Author
Troy Allen

## Course
CDA 3100
