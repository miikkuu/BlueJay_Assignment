# BlueJay Assignment

This repository contains the codebase for the assignment for Software Devloper Role in BlueJay Delivery. The assignment involves reading an Excel file containing timecard data, identifying employees who meet certain criteria, and printing the name and position of the identified employees to the console and to a file.

## How it works

The program is written in Python and uses the pandas library to read and manipulate the Excel file. The program iterates through the data structure to identify employees who meet the following criteria:

- Have worked for 7 consecutive days
- Have less than 10 hours of time between shifts but greater than 1 hour
- Have worked for more than 14 hours in a single shift

The program prints the name and position of the identified employees to the console and writes the console output to a file named `output.txt` in the base folder of the Git repository.

## How I completed the assignment

To complete the assignment, I used the pandas library to read and manipulate the Excel file. I used Python to write the program and tested it using sample data provided in the assignment. I then created a public Git repository on GitHub and pushed the codebase and console output to the repository.

## Requirements

To run the program, you will need to have Python 3 and the pandas library installed on your machine. You will also need to have an Excel file containing timecard data in the same directory as the Python script.

## Usage

To run the program, navigate to the directory containing the Python script and the Excel file and run the following command:

`python assignment.py` 

The program will print the name and position of the identified employees to the console and write the console output to a file named `output.txt` in the base folder of the Git repository.
