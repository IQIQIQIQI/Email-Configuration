Game concept

We create a simple guessing game where the player has to guess a number between 1 and 100.

Step 1: Installation

Make sure you have Python installed. You can download Python from python.org.

Step 2: Create script

Open a text editor or IDE (e.g. Visual Studio Code, PyCharm) and create a new file named ratespiel.py.

Step 3: Write code

Paste the following code into the file:

import random
    while True:
        try:
            tipp = int(input("Gib deinen Tipp (1-100) ein: "))  # Player input
            attempts += 1  # Count the attempts
            
            if tipp < 1 or tipp > 100:
                print("Please enter a number between 1 and 100.")
            elif tipp < zahl:
                print("Too low! Try again.")
            elif tipp > zahl:
                print("Too high! Try again.")
            else:
                print(f"Congratulation! You guessed the number {number} in {tries} attempts.")
                break  # End Game
        except ValueError:
            print("Please enter a valid number.")

if __name__ == "__main__":
    guessing game()

Step 4: Run script

Save the file and open a terminal or command prompt. Navigate to the folder where ratespiel.py is located and run the following command:

python guessgame.py

Step 5: Play Game

Follow the instructions in the terminal to make your estimates. You will receive feedback whether your guess is too high, too low or correct.

Explanation of the code

	• Import random: Imports the module for random number generation.
	• guessgame(): Defines the main function of the game.
	• random.randint(1, 100): Generates a random number between 1 and 100.
	• while True: Starts a loop that runs until the number is guessed.
	• try/except: Handles errors that may occur if the user does not enter a number.

Adjustments

You can expand the game by:

	• Add a limit on attempts.
	• Adjusts the difficulty (e.g. changing the number range).
	• Create a graphical user interface (GUI) using a library such as Tkinter.

Have fun!
