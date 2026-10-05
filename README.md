# CSC649 - My First Python Experiment

## Project Description

This project is a simple Python program that accepts a sentence from the user and calculates the number of words and characters in the input.

The program also handles empty input by displaying a suitable message instead of processing an empty sentence.

## How to Run

1. Open the project in PyCharm.
2. Open `main.py`.
3. Run the program.
4. Enter a sentence when prompted.
5. The program will display the word count and character count.

## Test Results

### Test 1: Normal Sentence

**Input:**

```text
happy birthday
```

**Output:**

```text
Word count: 2
Character count (including spaces): 14
```

**Status:** Passed

### Test 2: Empty Input

**Input:**

Press Enter without typing anything.

**Output:**

```text
You did not enter a sentence. Please try again.
```

**Status:** Passed

### Test 3: Sentence with Extra Spaces

**Input:**

```text
happy   birthday
```

**Output:**

```text
Word count: 2
Character count (including spaces): 16
```

**Status:** Passed

## Git Commits

* **Initial commit:** Set up the Python program and `.gitignore`.
* **Second commit:** Improved the empty-input message to provide clearer instructions to the user.
* **Third commit:** Added this `README.md` file to document the project, how to run it, and the test results.

## Limitation

The program only processes one sentence at a time and does not save the user's input or results after the program ends.
"# First-Git" 
