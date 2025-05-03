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

# python_assignments 2

Task 1: Check if a Number is Even or Odd
Problem Statement:  Write a Python program that:
1. 	Takes an integer input from the user.
2. 	Checks whether the number is even or odd using an if-else statement.
3. 	Displays the result accordingly.


solution:
Algorithm:

1.  START
2.  PROMPT the user to "Enter an integer: "
3.  READ the input and store it in a variable called `number_str`.
4.  ATTEMPT to convert `number_str` to an integer and store it in a variable called `number`.
5.  IF a ValueError occurs during conversion (meaning the input is not a valid integer):
    a. DISPLAY "Invalid input. Please enter an integer."
    b. GO TO step 8.
6.  CALCULATE the remainder when `number` is divided by 2.
7.  IF the remainder is 0:
    a. DISPLAY "`number` is even."
8.  ELSE:
    b. DISPLAY "`number` is odd."
9.  END



Task 2: Sum of Integers from 1 to 50 Using a Loop
 
Problem Statement: Write a Python program that:
1.   Uses a for loop to iterate over numbers from 1 to 50.
2.   Calculates the sum of all integers in this range.
3.   Displays the final sum.


solution:

Algorithm:

1.  START
2.  INITIALIZE a variable `sum` to 0.
3.  USE a loop to iterate through numbers from 1 to 50 (inclusive).  Let the loop variable be `i`.
4.  INSIDE the loop:
    a.  ADD the current value of `i` to `sum`.
5.  AFTER the loop finishes:
6.  DISPLAY the message "The sum of integers from 1 to 50 is: " followed by the value of `sum`.
7.  END








