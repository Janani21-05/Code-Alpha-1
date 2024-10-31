Name:Janani S
Company: CodeAlpha 
ID:CA/03/41583
Domain :Java programming
Duration: October 1.10.2024 - 31.10.2024
Task-1(Student Grade Tracker)

Overview of the project:-

The Student Grade Tracker is a Java application designed to help users input and manage student grades. Here’s an overview of its functionality:

Features
Input Grades: The program prompts the user to enter student grades one by one. Users can continue to enter grades until they choose to exit by typing "exit."

Validation:

The program checks if the entered grade is a valid number.
It ensures that grades are within a specified range (0 to 100). If an invalid grade is entered, it prompts the user for correction.
Grade Storage: Grades are stored in an ArrayList<Double>, allowing dynamic resizing as grades are added.

Calculations: Once the user finishes entering grades:

The program calculates the average, highest, and lowest grades from the entered values.
It handles the case where no grades are entered and informs the user accordingly.
Output: The results (average, highest, and lowest grades) are displayed in a formatted manner.

Code Structure
Main Method: The entry point of the program, which handles user interaction and grade management.
Loop: A do-while loop allows continuous input until the user decides to exit.
Error Handling: Try-catch blocks manage exceptions related to invalid number formats.
User Interaction
The program is command-line based, guiding the user through grade entry with clear prompts and feedback on input errors.

Overall, the Student Grade Tracker is a straightforward utility for anyone needing to collect and analyze student grades efficiently.
