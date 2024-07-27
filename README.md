# Java Programs

This repository contains three Java programs:
1. Student Grade Calculator
2. ATM Interface
3. Number Guessing Game

## Table of Contents
1. [Student Grade Calculator](#student-grade-calculator)
2. [ATM Interface](#atm-interface)
3. [Number Guessing Game](#number-guessing-game)

---

## Student Grade Calculator

### Description
The Student Grade Calculator program calculates the grade of a student based on the average percentage of marks obtained in various subjects. It assigns a grade based on the following criteria:

- `A` for 85% and above
- `B` for 75% to 84%
- `C` for 65% to 74%
- `D` for 60% to 64%
- `E` for 50% to 59%
- `F` for below 50%

### How to Run
1. Compile the program:
    ```bash
    javac StudentGradeCalculator.java
    ```
2. Run the program:
    ```bash
    java StudentGradeCalculator
    ```

### Output
```
Enter the number of subjects:
3
Enter marks for subject 1: 85
Enter marks for subject 2: 90
Enter marks for subject 3: 80
Total Marks: 255
Average Percentage: 85.00%
Grade: A
```

---

## ATM Interface

### Description
The ATM Interface program simulates a simple ATM machine using a graphical user interface (GUI). It allows users to deposit and withdraw money and check their account balance. The GUI is created using Java Swing.

### How to Run
1. Compile the program:
    ```bash
    javac Atm_Interface.java
    ```
2. Run the program:
    ```bash
    java Atm_Interface
    ```

### Output
A GUI window will appear with the following components:
- A text field to enter the amount.
- Buttons for "Withdraw", "Deposit", and "Check Balance".
- A label to display the result of transactions.
- A text area to display the transaction log.

Example GUI actions:
1. Enter `100` in the amount field and click "Deposit":
    ```
    Deposited: 100.0
    ```
2. Enter `50` in the amount field and click "Withdraw":
    ```
    Withdrawn: 50.0
    ```
3. Click "Check Balance":
    ```
    Balance: 50.0
    ```

---

## Number Guessing Game

### Description
The Number Guessing Game allows the player to guess a randomly generated number between 0 and 100. The player has up to 12 attempts to guess the correct number. After each guess, the program provides feedback on whether the guess was too high, too low, or correct.

### How to Run
1. Compile the program:
    ```bash
    javac NumberGuessingGame.java
    ```
2. Run the program:
    ```bash
    java NumberGuessingGame
    ```

### Output
```
I have generated a number between 0 and 100.
You have 12 attempts to guess it.
Enter your guess: 50
Your guess is too low.
Attempts left: 11
Enter your guess: 75
Your guess is too high.
Attempts left: 10
Enter your guess: 63
Congratulations! You've guessed the number correctly.
Do you want to play again? (yes/no): no
You won 1 round(s). Thanks for playing!
```

---
