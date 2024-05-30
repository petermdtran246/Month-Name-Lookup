# Month Name Lookup

This project provides a simple program to determine the name of a month based on its numerical value (1-12).

## Algorithm:

1. The program includes the <iostream> header file for input/output operations.

2. The MonthName function takes an integer m representing the month number (1 for January, 2 for February, and so on).

3. Inside the MonthName function:
  -  A series of if statements check the value of m.
  -  If the m value matches a specific month number (1 to 12), the corresponding abbreviated month name ("jan", "feb", etc.) is printed using cout.

4. In the main function:
  -  An integer variable m is declared to store the user-provided month number.
  -  The program prompts the user to enter a month number between 1 and 12.
  -  The user's input is stored in the m variable using cin.
  -  The MonthName function is called with the m value as an argument. This triggers the lookup logic based on the entered number.

5.The program returns 0 to indicate successful execution.
