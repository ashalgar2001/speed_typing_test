Speed Typing Test

This project is a Speed Typing Test implemented in Python. It allows users to test their typing speed and accuracy by providing a random sentence or paragraph to type. The program calculates the user's typing speed in words per second and reports the number of errors in the typed input.

Features --
Generates random sentences or paragraphs for typing tests.
Calculates typing speed in words per second.
Reports the number of errors made during typing.
User-friendly interface with options to start or exit the test.

Prerequisites --
Python 3.x
Ensure Python is installed on your system. You can download it from the official Python website.

How to Run --
Clone or download the repository containing the script.
Open the terminal or command prompt and navigate to the directory where the script is saved.
Run the script using the following command:
python speed_typing_test.py

Follow the on-screen instructions:
Type yes to begin the test.
Type no to exit the program.

Code Explanation --

Functions:

mistake(partest, usertest)
Compares the provided sentence with the user input to count the number of errors.
Returns the total number of errors.

speed_time(time_s, time_e, userinput)
Calculates the time taken to type the input.
Computes typing speed in words per second.
Returns the rounded typing speed.

Main Program Flow --

Prompts the user with a random sentence or paragraph.
Tracks the start and end time for typing.

Collects user input and calculates:
Typing speed
Number of errors

Displays the results to the user.

License --
This project is open-source and available for modification or enhancement. Feel free to use and improve it for your own purposes!
