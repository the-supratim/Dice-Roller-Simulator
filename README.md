# Overview
The Dice Roller Simulator is a simple Python program that simulates the rolling of a six-sided die. Each time the program runs, it randomly generates a number between 1 and 6, and then displays a graphical representation of the die face corresponding to the generated number. The user can choose to roll the die multiple times or exit the program.

# How It Works
## 1. Initialization:
* The program starts by setting a variable x to "Y", indicating that the user wants to roll the die.

## 2. Main Loop:
* The program enters a while loop that continues as long as x is "Y".
* Inside the loop, the program generates a random number between 1 and 6 using random.randint(1, 6).
* Based on the generated number, the program prints the corresponding graphical representation of the die face.

## 3. Graphical Representation:
* The program uses if statements to determine which die face to display based on the random number generated.
* Each possible number (1 through 6) has a specific block of code that prints the die face using ASCII art.

## 4. User Interaction:
* After displaying the die face, the program prompts the user to roll again by pressing "Y" or to exit by pressing "N".
* The user's input is read and stored in the variable x.
* If the user presses "Y", the loop continues, generating and displaying a new die face.
* If the user presses "N", the loop terminates, and the program exits.

# Usage
## 1. Run the Program:
* Execute the Python script to start the dice rolling simulator.

## 2. Rolling the Die:
* The program will automatically roll the die and display the result.
* To roll the die again, press "Y" when prompted.
* To exit the program, press "N" when prompted.

# Requirements
* Python 3.x
* No additional libraries are required.
