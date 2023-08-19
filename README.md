# U.S. States Game

The **U.S. States Game** is a Python program that utilizes the **Turtle graphics** library to create an interactive game for learning and guessing U.S. state names by their location on a map. This project also employs the **Pandas** library to manage and manipulate data.

![U.S. States Game](images/preview.gif)

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Learning the names and locations of all 50 U.S. states can be challenging. The **U.S. States Game** aims to make this process more engaging and interactive. The game displays a blank map of the United States and prompts the user to input the names of various states. The game continues until all 50 states have been correctly guessed or the user decides to exit.

## Installation

To run the U.S. States Game on your local machine, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/AbhiramInguva/US-States-Game.git
   ```

2. Change into the project directory:

   ```bash
   cd US-States-Game
   ```

3. Install the required dependencies (Turtle and Pandas). You might want to use a virtual environment:

   ```bash
   pip install turtle pandas
   ```

4. Download the required data file (50_states.csv) and place it in the project directory.

5. Run the Python script:

   ```bash
   python main.py
   ```

## Usage

1. Launch the game by running the Python script.
2. A window will open displaying a blank map of the United States and the prompt to guess a state's name.
3. Enter the name of a U.S. state you think corresponds to the displayed location.
4. If your guess is correct, the state's name will be displayed on the map.
5. Continue guessing until you've correctly identified all 50 states or choose to exit the game by typing "Exit".
6. After exiting the game, a CSV file named "states_to_learn.csv" will be generated containing the names of states you haven't guessed correctly yet.

## How It Works

1. The game uses the Turtle library to create a window and display the blank map of the United States.
2. The game reads the state data from the "50_states.csv" file using the Pandas library.
3. The user is prompted to input a state's name through a text input window.
4. If the entered state name is correct, it is displayed on the map using a Turtle graphics turtle.
5. The game continues until the user guesses all 50 states correctly or decides to exit.
6. If the user chooses to exit, a CSV file named "states_to_learn.csv" is generated, containing the names of the states that weren't correctly guessed.

## Contributing

Contributions to the U.S. States Game project are welcome! If you have ideas for improvements, bug fixes, or new features, feel free to submit issues and pull requests.

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and test thoroughly.
4. Submit a pull request explaining your changes.

Feel free to explore, learn, and enjoy the process of guessing the U.S. states with the U.S. States Game! If you encounter any issues or have questions, please don't hesitate to [contact us](mailto:contact@example.com).
