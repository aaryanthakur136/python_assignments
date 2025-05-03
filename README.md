# python_assignments 1 

Problem Statement 1 : Write a Python program that does the following:
1.  Takes two numbers as input from the user.
2.  Performs the basic mathematical operations on these two numbers:
o	Addition
o	Subtraction
o	Multiplication
o	Division
3.  Displays the results of each operation on the screen.
 solution :

Algorithm for Basic Calculator:

1. START
2. PROMPT the user to "Enter the first number: "
3. READ the first number and store it in a variable called `num1_str`.
4. ATTEMPT to convert `num1_str` to a floating-point number and store it in a variable called `num1`.
5. IF a ValueError occurs during conversion (meaning the input is not a valid number):
   a. DISPLAY "Invalid input. Please enter valid numbers."
   b. GO TO step 14.
6. PROMPT the user to "Enter the second number: "
7. READ the second number and store it in a variable called `num2_str`.
8. ATTEMPT to convert `num2_str` to a floating-point number and store it in a variable called `num2`.
9. IF a ValueError occurs during conversion (meaning the input is not a valid number):
   a. DISPLAY "Invalid input. Please enter valid numbers."
   b. GO TO step 14.
10. CALCULATE the addition of `num1` and `num2`, store the result in a variable called `addition`.
11. CALCULATE the subtraction of `num2` from `num1`, store the result in a variable called `subtraction`.
12. CALCULATE the multiplication of `num1` and `num2`, store the result in a variable called `multiplication`.
13. IF `num2` is equal to 0:
    a. SET the `division` result to "Cannot divide by zero".
14. ELSE:
    a. CALCULATE the division of `num1` by `num2`, store the result in a variable called `division`.
15. DISPLAY "--- Results ---"
16. DISPLAY the result of the addition: `num1` + `num2` = `addition`.
17. DISPLAY the result of the subtraction: `num1` - `num2` = `subtraction`.
18. DISPLAY the result of the multiplication: `num1` * `num2` = `multiplication`.
19. DISPLAY the result of the division: `num1` / `num2` = `division`.
20. END


Problem Statement2: Write a Python program that:
1.  Takes a user's first name and last name as input.
2.  Concatenates the first name and last name into a full name.
3.  Prints a personalized greeting message using the full name.

  solution:
Algorithm:

1.  START
2.  PROMPT the user to "Enter your first name: "
3.  READ the first name and store it in a variable called `first_name`.
4.  PROMPT the user to "Enter your last name: "
5.  READ the last name and store it in a variable called `last_name`.
6.  CONCATENATE `first_name` and `last_name` with a space in between, and store the result in a variable called `full_name`.
7.  DISPLAY the message "Hello, " followed by the value of `full_name` and an exclamation mark.
8.  END





