# AI-Powered Guess the Number Game
A Python command-line game where users attempt to guess a randomly generated number between 1 and 100. The project demonstrates the integration of machine learning libraries (scikit-learn) within a standard game loop.

# 📋 Description
The program generates a random target number (1–100) and asks the user to guess it. It provides feedback on whether the guess is "Too High," "Too Low," or "Very Close" (within 5 numbers).

Uniquely, the script initializes and trains a Linear Regression model using scikit-learn at the start of the game, demonstrating how to embed ML models into functional Python scripts.

# 🛠️ Prerequisites
To run this game, you must have Python 3.x installed. You also need the following external libraries:

numpy

scikit-learn

# 📦 Installation
Clone or download the script file to your local machine.

Install dependencies using pip:

Bash

pip install numpy scikit-learn
# 🚀 How to Run
Save the provided Python code into a file named game.py (or any name you prefer).

Open your terminal or command prompt.

Navigate to the folder containing the file.

Run the script:

Bash

python game.py
# 🎮 How to Play
The game will initialize (train the model) and pick a secret number between 1 and 100.

Enter an integer when prompted.

The game will give you hints:

Too Low: Your guess is smaller than the target.

Too High: Your guess is larger than the target.

Very Close!: You are within 5 numbers of the target.

The game ends when you guess the correct number.

# 📂 File Structure
game.py: The main Python script containing the game logic and model training.

README.md: Documentation file.
