1. Problem Statement
   
The goal of this project is to develop a reliable, command-line interface (CLI) application that can perform fundamental arithmetic operations (addition, subtraction, multiplication, division, power, and modulus). Furthermore, it addresses the need for non-volatile memory by requiring a history feature to record all successful calculations, allowing users to review their past work easily without relying on external logs or journals.

2. Scope of the Project 🔭
   
The project focuses on creating a minimum viable product (MVP) for a calculator with defined limitations:

Supported Operations: Limited to binary operations: +, -, *, /, ** (power), and % (modulus).

Input Format: Strict input format is required: number operator number (e.g., 10 + 5).

Persistence: History is saved to a local plain text file (history.txt).

Non-Scope: The project does not include advanced functions (trigonometry, logarithms), handling of complex nested expressions (e.g., parentheses), or a graphical user interface (GUI).

3. Target Users 👤
   
This application is designed for users who require fast, accessible arithmetic calculations directly within a terminal environment:

Students: For quick checks on homework or simple formula execution.

Programmers/Developers: For debugging, calculating array indices, or performing quick math without leaving the terminal.

Technical Users: Individuals who prefer command-line tools over graphical applications for efficiency and speed.

4. High-Level Features ✨
   
The core functionalities of the Simple Command-Line Calculator are:

Core Arithmetic     :    Handles the six primary operations: addition, subtraction, multiplication, division, power, and modulus.

Input Validation    :    Checks the input structure and data types to ensure the calculation can be processed correctly.

Error Handling	    :    Includes specific checks to prevent the application from crashing, notably an explicit safeguard against division by zero.

Calculation History	:    Automatically saves every successful equation and its result to a persistent file (history.txt).

History Management	:    Provides commands (history, clear) to view the saved results or erase the history file.



Interactive CLI	Runs in a continuous loop, prompting the user for calculations or commands until the exit command is explicitly used.
