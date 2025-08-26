# Tideman Voting Algorithm (CS50 Problem Set 3)

This project implements the **Tideman ranked pairs voting system** in C.

## Features
- Records voter preferences
- Generates candidate pairs
- Sorts pairs by strength of victory
- Locks pairs avoiding cycles
- Prints election winner

## How to Run
```bash
make tideman
./tideman Alice Bob Charlie

Example

Number of voters: 5
Rank 1: Alice
Rank 2: Bob
Rank 3: Charlie
...
Winner: Alice
