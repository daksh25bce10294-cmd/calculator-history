# calculator-history

Simple Command-Line Calculator

Overview of the Project

This project is a simple, command-line calculator written in Python. It performs basic arithmetic operations and includes functionality to view and clear the history of calculations. It is an excellent example of a basic interactive program for a college project.


Features

*    Basic Arithmetic Operations: Supports addition (+), subtraction (-), multiplication (*), and division (/).

*    Advanced Operations: Includes support for exponentiation (power, **) and modulus (remainder, %).

*    Division by Zero Handling: Prevents errors by checking and notifying the user if they attempt to divide by zero.

*    Calculation History: Stores all successful calculations in a separate file (history.txt).

  History Management:

        *    View History: Users can view the calculation history with the history command.

        *    Clear History: Users can clear the stored history with the clear command.

*    User-Friendly Interface: Provides clear instructions and error messages for invalid input or operations.

Technologies/Tools Used

*    Language: Python

*    File Handling: Used for persistent storage of calculation history in the history.txt file.

Steps to Install & Run the Project

1.  Clone the Repository:
   

Bash


git clone [Your-GitHub-Repository-Link](#Your-GitHub-Repository-Link)
cd [Your-Project-Folder-Name](#Your-Project-Folder-Name)


2.  Ensure Python is Installed: This program requires Python 3. You can check your version by running:
   

Bash


python --version


If you don't have it, please install it from the official Python website.

3.  Run the Calculator: Execute the main script from your terminal:
   

Bash


python Vityarthi Project.py


The calculator will start, and you will see the welcome message: -----SIMPLE CALCULATOR(type history,clear or exit)

Instructions for Testing

Once the calculator is running, you can test its features using the following instructions:

1. Basic Calculations
   
   
*    Enter your calculations in the format: number operator number (e.g., 10 + 5).

*    Addition: 10 + 5 (Expected Output: Result : 15.0)

*    Subtraction: 25 - 12 (Expected Output: Result : 13.0)

*    Multiplication: 5 * 4.5 (Expected Output: Result : 22.5)

*    Division: 100 / 4 (Expected Output: Result : 25.0)


2. Advanced Calculations
   
   
*    Power/Exponentiation: 2 ** 3 (Expected Output: Result : 8.0)

*    Modulus/Remainder: 10 % 3 (Expected Output: Result : 1.0)

3. Error Handling

   
*    Division by Zero: 5 / 0 (Expected Output: You Cannot divide by Zero)

*    Invalid Format: 5 + (Expected Output: Invalid input.use Format:- number operator number(Example :- 13 + 5))

*    Invalid Operator: 10 $ 5 (Expected Output: Invalid operation . Use only +,-,/,*,**(for power),%(for Finding Reminder)

4. History Commands

   
  *    View History:

        *    After performing a few successful calculations, type: history
  

        *    (Expected Output: A list of your recent calculations and results, most recent first.)
  

  *   Clear History:
  

      *    Type: clear
  

      *    (Expected Output: History Cleared.)
  

*    Exit Program:
  

      *    Type: exit


      *    (Expected Output: Good Bye!)
