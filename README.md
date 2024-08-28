# Python-fundamentals

This repository contains Python programs and explanations that cover fundamental concepts, data structures, and programming techniques. Below are the descriptions and details of the various tasks included.

Contents
Palindrome Check Using a Stack
List Comprehension in Python
Compound Data Types in Python
Generating Bigrams from a String
Finding the Closest Key in a Dictionary
1. Palindrome Check Using a Stack
Description:
A Python program to check whether a given string is a palindrome using a stack data structure. A palindrome is a word, phrase, number, or any other sequence of characters that reads the same forward and backward (ignoring spaces, punctuation, and capitalization).

Data Structure Used: Stack
Implementation Steps:
Push each character of the string onto a stack.
Pop characters off the stack to reverse the string.
Compare the reversed string with the original string to determine if it is a palindrome.
2. List Comprehension in Python
Description:
List comprehension provides a concise way to create lists. It consists of brackets containing an expression followed by a for clause, and optionally one or more if clauses.

Examples:
Creating a list of squares of numbers from 0 to 9.
Generating a list of even numbers.
Combining of lists.
3. Compound Data Types in Python
Description:
Compound data types are those that can hold multiple values. Examples include lists, dictionaries, and tuples.

Examples:
List: A collection that is ordered, changeable, and allows duplicate elements.
Dictionary: An unordered collection that stores data in key-value pairs.
Tuple: An ordered collection that is immutable and allows duplicate elements.
4. Generating Bigrams from a String
Description:
A function that takes a string as input and returns a list of bigrams. Bigrams are pairs of consecutive elements from a sequence of items, such as characters in a string or words in a sentence.

Example:
Input: "you are my love"
Output: ['yo', 'ou', 'ua', 'ar', 're', 'em', 'my', 'yl', 'lo', 'ov', 've']
5. Finding the Closest Key in a Dictionary
Description:
A function closest_key that takes a dictionary with keys as letters and values as lists of letters. The function finds the key with the input value that is closest to the beginning of its list.

Example Usage:
Given the dictionary:
{'A': ['x', 'y', 'z'], 'B': ['a', 'b', 'c'], 'C': ['y', 'c', 'a']}
Input: "y"
Output: "C"
