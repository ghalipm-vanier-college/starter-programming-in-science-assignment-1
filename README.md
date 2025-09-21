# Programming in Science - Assignment 1

This template repository is the starter project for Programming in Science Assignment 1. Written in Python, and tested with Pytest.

---

## Questions

### 1. Maximum of Three Numbers *(10%)*
Write a function to calculate the **maximum** of three numbers using Python’s built-in functions.

---

### 2. Minimum of Three Numbers *(10%)*
Write a function to calculate the **minimum** of three numbers using Python’s built-in functions.

---

### 3. Check Positive, Negative, or Zero *(10%)*
Write a function that checks if a number is positive, negative, or zero and returns a corresponding message.

---

### 4. Star Triangle Pattern *(10%)*
Write a function that prints a right-angled triangle of stars using a `for` loop with a given number of rows (rows>=3):
   
   ```
   *
   **
   ***
   ****
   *****
   ```
---

### 5. Right-Leaned Hollow Parallelogram Pattern *(10%)*
Write a function that prints a right-leaned hollow parallelogram using stars (`*`) and spaces.

- The function should take **one integer input** `n (n>=3)` representing the number of stars on each side.
- The pattern should look like this for `n = 5`:

``` 
      *****
     *   *
    *   *
   *   *
  *****
```
---  
### 6. Sum of Even Numbers *(10%)*
Write a function that calculates the sum of all even numbers from 1 to `n` (inclusive) using a `for` loop.

---

### 7. Multiples of 5 Using a While Loop *(10%)*
Write a function returning a list of all multiples of 5 between 1 and 50 (inclusive) using a `while` loop.

---

### 8. Ask Until Valid Range *(10%)*
Write a function that keeps asking for a number until the user enters a value between 1 and 7. Return the valid input.

---

### 9. Chemistry pH State Check *(10%)*
Write a function that takes a pH value and returns:
  - `"Acidic"` if pH < 7  
  - `"Neutral"` if pH == 7  
  - `"Basic"` if pH > 7

---

### 10. Rock, Paper, Scissors Evaluator *(10%)*
Write a function that determines the result of a Rock, Paper, Scissors round:
- The function should take **two integer inputs**: the player's choice and the opponent's choice:
   - `1` for `"rock"`, `2` for `"paper"`, `3` for `"scissors"`
- Return whether the player wins, loses, or ties (e.g., `"Player win!"`, `"Player lose!"`, or `"Tie!"`).
   - input: rock_paper_scissors(1, 3)  output: "Player win!"
   - input: rock_paper_scissors(2, 2)  output: "Tie!"
   - input: rock_paper_scissors(1, 2)  output: "Player lose!"
---

### Run Command

`pytest`
