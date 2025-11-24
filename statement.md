## Problem Statement
Title: Automated Relative Grading and GPA Predictor for VIT Students

Context: In academic institutions like VIT, the grading system is often "Relative" rather than "Absolute." This means a student's grade depends not just on their raw score, but on how they perform compared to the class average and the highest score in the class.

The Problem: Students often struggle to estimate their Grade Point Average (GPA) during the semester because manual calculation involves complex comparisons against class statistics (Average Marks and Highest Marks). Additionally, calculating the cumulative effect of multiple subjects on the final GPA is tedious and prone to human error.

The Solution: To resolve this, there is a need for a computational tool that allows students to input their raw marks, the class average, and the highest marks to instantly determine their probable grade for each subject and their overall semester GPA.]

## Scope of the ProjectThe scope defines the boundaries of what this Python application currently does and what it aims to achieve.
The scope of work for this project encompasses the development of a console-based automated GPA calculator designed to simulate the relative grading mechanism used in academic institutions like VIT. The application is engineered to profile students based on their academic year and process performance across a dynamic number of subjects by analyzing three specific data points per course: the student's raw score, the class average, and the highest recorded mark. Functionally, the system applies conditional logic to categorize performance into specific letter grades ranging from S to F based on statistical deviation, subsequently aggregating these values to compute and display a final semester GPA alongside a detailed summary of the student's subject-wise performance, assuming equal credit weightage for all courses.

## Target Users
The primary target users for this application are undergraduate students, particularly those enrolled in institutions like VIT that employ a relative grading system or Fully Flexible Credit System (FFCS). It is specifically designed for students who need to translate their raw exam scores into probable letter grades by comparing their performance against the class average and the highest achiever. This tool serves as an essential utility for both freshmen trying to understand the competitive grading logic and senior students aiming to accurately forecast their Semester GPA to maintain academic standing or secure placement eligibility.

## High-Level Features
The project features a dynamic data processing engine that accommodates variable course loads, allowing students to input details for any number of subjects within a single semester. Its core functionality rests on a relative grading algorithm, which replaces standard percentage calculations with a comparative logic system that evaluates a student's raw score against the class average and the highest recorded marks to automatically assign letter grades (S through F). Additionally, the system includes a cumulative GPA aggregator that translates these letter grades into numerical values based on subject count, and it concludes with a comprehensive reporting module that generates a summarized transcript of subject names, raw scores, and the final calculated GPA for immediate performance assessment.
