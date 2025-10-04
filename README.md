# Build an RPG Character

In this lab you will practice the basics of Python by building a small app that creates a character for an RPG adventure.

## Objective
Fulfill the user stories below and get all the tests to pass to complete the lab.

## User Stories

1.  You should have a function named create_character.

2.  The function should accept, in order, a character name followed by three stats: strength, intelligence, and charisma.

3.  The character name should be validated:
    - If the character name is not a string, the function should return The character name should be a string.
    - If the character name is longer than 10 characters, the function should return The character name is too long.
    - If the character name contains spaces, the function should return The character name should not contain spaces.

4.  The stats should also be validated:
    - If one or more stats are not integers, the function should return All stats should be integers.
    - If one or more stats are less than 1, the function should return All stats should be no less than 1.
    - If one or more stats are more than 4, the function should return All stats should be no more than 4.
    - If the sum of all stats is different than 7, the function should return The character should start with 7 points.

5.  If all values pass the verification, the function should return a string with four lines:
    - the first line should contain the character name
    - lines 2-4 should start with the stat abbreviation, STR, INT or CHA (in this order), then a space, and then a number of full dots (●) equal to the value of the stat, and a number of empty dots (○) to reach 10. Example: if the value of strength is 3 there must be 3 full dots followed by 7 empty dots. The dots are given in the editor.
  
## Example

ren
STR ●●●●○○○○○○
INT ●●○○○○○○○○
CHA ●○○○○○○○○○

## Note
while str and int are common abbreviations for the stats, remember that those are reserved keywords in Python and should not be used as variable names.

## 🛠 Skills
Python
