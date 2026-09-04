# Python Loops Assignment - Beginner Level

## Overview
This assignment focuses on mastering loops in Python through practical, real-world scenarios. You'll work with both `for` and `while` loops to solve meaningful problems.

## Assignment: Number Pattern Generator & Statistics Calculator

### Part 1: Number Pattern Generator (For Loops)
Write a program that uses a `for` loop to generate and display number patterns.

**Requirements:**
1. Ask the user to enter a number `n` (between 1 and 10)
2. Display a pyramid pattern using that number:
   ```
   For n = 4:
   1
   1 2
   1 2 3
   1 2 3 4
   ```
3. Display a multiplication table for that number (1-10)

**Example Output:**
```
Enter a number (1-10): 5
Pyramid:
1
1 2
1 2 3
1 2 3 4
1 2 3 4 5

Multiplication Table for 5:
5 x 1 = 5
5 x 2 = 10
...
5 x 10 = 50
```

---

### Part 2: Statistics Calculator (While Loops)
Write a program that uses a `while` loop to calculate statistics from user input.

**Requirements:**
1. Keep asking the user to enter numbers until they type "done"
2. Calculate and display:
   - Sum of all numbers
   - Count of numbers entered
   - Average of the numbers
   - Highest number
   - Lowest number

**Example Output:**
```
Enter numbers (type 'done' to finish):
Enter a number: 15
Enter a number: 23
Enter a number: 8
Enter a number: 42
Enter a number: 16
Enter a number: done

Statistics:
Sum: 104
Count: 5
Average: 20.8
Highest: 42
Lowest: 8
```

---

### Part 3: Nested Loops Challenge (Bonus)
Create a program that prints a multiplication table grid for numbers 1-5.

**Expected Output:**
```
    1   2   3   4   5
1   1   2   3   4   5
2   2   4   6   8  10
3   3   6   9  12  15
4   4   8  12  16  20
5   5  10  15  20  25
```

---

## Learning Objectives
- ✅ Understand how `for` loops iterate through sequences
- ✅ Understand how `while` loops work with conditions
- ✅ Practice input validation and error handling
- ✅ Use loops to solve multi-step problems
- ✅ Work with variables inside and outside loops
- ✅ Format and display data clearly

## Submission
1. Create a Python file named `assignment.py`
2. Include all three parts in your solution
3. Test your code thoroughly
4. Add comments explaining your logic
5. Push to your repository

## Tips
- Start with Part 1, then move to Part 2
- Test each section separately before combining
- Use `int()` to convert string input to numbers
- Handle the case where a user might enter invalid input
- Use meaningful variable names

## Resources
- Python Loops: https://www.w3schools.com/python/python_while_loops.asp
- For Loops: https://www.w3schools.com/python/python_for_loops.asp
