# Wordle Solver

## Introduction
This project introduces a German version of the popular Wordle game, complete with a user-playable interface. Its highlight is a basic algorithm designed to automatically solve the game.


## Workflow
The solution process begins with a starting word, followed by the systematic filtering of a pre-defined word list. Initially, the list is narrowed down to words of the correct length. Then, words containing characters identified as not part of the target word are excluded. If the attempt yields no correct characters, the algorithm selects a new word, prioritizing those with the highest frequency of most common characters. This strategy aims to quickly eliminate a broad range of characters, focusing on those more likely to be in the target word.
The Wordle game provides feedback for each guess, indicating if characters are not in the word, in the word but misplaced, or correctly placed. The presence of repeated characters in a word adds a layer of complexity to the solving algorithm.
To test the algorithm's effectiveness, a loop is implemented. Each word in the list is set as a target, and the algorithm measures the number of attempts, time taken to solve, and overall success rate.

## Limitations
The word list used in the project is not included due to copyright restrictions. Various compatible lists are available online and can be easily integrated by altering the file path in the code. The project is compatible with dictionary files or text files with line-separated entries.


