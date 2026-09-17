# Week 3 Assignment: Conditions and Loops

This assignment practices Python conditions, loops, debugging, and calculations.

### Files

- `grade_reporter.py` - Uses a for loop and conditions to calculate grades, pass/fail counts, and the average score.
- `bug_hunt.py` - Fixes three bugs in a while loop program and calculates the sum from 1 to 5.

The hardest bug to find was the one that did not produce an error message. I knew something was wrong because the program ran successfully but produced 10 instead of the required answer of 15. I checked the loop condition and realized that using `< 5` stopped the loop before adding 5, so I changed it to `<= 5`.
