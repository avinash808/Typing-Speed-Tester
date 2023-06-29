Typing Speed Tester GUI
This code provides a graphical user interface (GUI) for testing and measuring typing speed. It allows the user to enter text in an input field and calculates various metrics such as characters per second (CPS), characters per minute (CPM), words per second (WPS), and words per minute (WPM). The user's input is compared to a randomly selected sample text, and the input field color changes to indicate correctness.

Dependencies
tkinter: Python's standard GUI package for creating GUI applications.
time: A module providing various time-related functions.
threading: A module for creating and managing threads in Python.
random: A module for generating random numbers.
Usage
Create a text file named "texts.txt" and populate it with the sample texts you want to use for typing speed tests. Each text should be on a separate line.
Import the necessary dependencies (tkinter, time, threading, random).
Instantiate the TypeSpeedGUI class to create the GUI application.
The GUI window will open with the sample text displayed at the top and an input field below it.
Start typing in the input field to measure your typing speed.
As you type, the program will continuously update the speed metrics (CPS, CPM, WPS, WPM) based on your input.
The input field color will change to red if the entered text does not match the sample text's beginning, indicating an error. It will change to green if the entered text matches the sample text.
To reset the test, click the "Reset" button. It will clear the input field and select a new random sample text.
Close the GUI window to exit the program.
