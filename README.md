# Number Guessing Game

A simple Python-based number guessing game where you try to guess a randomly selected number within a specified range. The number of allowed guesses is determined using binary search logic.

## Features

- User selects the lower and upper bounds for the guessing range.
- The game randomly picks a number within that range.
- You get a limited number of guesses (based on binary search steps).
- After each guess, you receive feedback: "Too High!" or "Too Low!".
- Input validation for both range and guesses.

## Requirements

- Python 3.x
- numpy

## How to Run

1. Open `Game.ipynb` in Jupyter Notebook or Visual Studio Code.
2. Run the notebook cell to start the game.
3. Follow the prompts:
   - Enter the lower and upper bounds (e.g., `5-20`).
   - Try to guess the number within the allowed attempts.

## Example

```
Hi! Welcome to the Number Guessing Game.
Let's start!
Enter Lower Bound and Upper Bound (e.g. 5-10): 10-50

You have 6 chances to guess the number between 10 and 50. Let's start!
Take Guess 1: 30
Guess 1: 30 → Too Low!
Take Guess 2: 40
Guess 2: 40 → Too High!
...
```
