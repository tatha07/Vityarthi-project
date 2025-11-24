# Vityarthi-project
GPA calculator using python

## Project Overview
The VIT GPA Calculator is a Python-based software utility designed to address the complexities of the Relative Grading System employed by academic institutions like VIT. Unlike traditional grading tools that rely solely on absolute percentages, this system evaluates a student's academic standing by comparing their raw scores against two critical statistical benchmarks: the Class Average and the Highest Score achieved in the course. By automating this comparison through a series of logical conditions, the program assigns specific letter grades (S, A, B, C, D, E, F) and computes the resulting Grade Point Average (GPA). This tool provides students with an immediate, data-driven forecast of their semester performance, eliminating manual calculation errors and offering clarity on how peer performance influences their final academic results.

## Features
The project integrates several key functionalities designed to simulate an academic grading environment, primarily featuring a dynamic input interface that allows users to define variable subject counts for the semester. At its core is a comparative logic engine that implements relative grading by evaluating individual performance against the class average and the highest recorded score to assign appropriate letter grades (S through F). Additional features include academic profiling to track student details and a summative reporting module that aggregates these relative grades into a final calculated GPA, providing a detailed transcript of subject-wise performance upon completion.

## Technologies and Tools Used
The project is developed entirely using the Python programming language, chosen for its readability and robust handling of mathematical logic. It operates as a Command Line Interface (CLI) application, requiring only a standard Python interpreter to execute, with no dependency on external third-party libraries or databases. The underlying architecture utilizes Python's standard library, leveraging built-in data structures such as lists for dynamic storage and fundamental control flow constructs (conditional statements and iterative loops) to process the relative grading algorithm and compute the cumulative results efficiently.

## Steps to Install and Run
To execute this project, ensure that Python is installed on your system. First, copy the provided source code and save it as a Python file (e.g., gpa_calculator.py) in a known directory. Open your system's Command Prompt (Windows) or Terminal (macOS/Linux) and navigate to the folder where you saved the file using the cd command. Finally, execute the program by typing python gpa_calculator.py and pressing Enter; the application will launch in the console, prompting you to input your details and marks interactively.

## Instructions for Testing
Testing the application involves executing the script and inputting varied data sets to validate the accuracy of the relative grading logic and final GPA computation. Users should verify distinct scenarios: first, input a score within 5 marks of the "Highest Class Score" to confirm the assignment of an 'S' grade, and second, input a score significantly below the "Class Average" to ensure 
