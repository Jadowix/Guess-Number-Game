# Number Guessing Game

This JavaScript project implements a basic number guessing game where the user tries to guess a randomly generated number between 1 and 100. The game interface is built using HTML elements and controlled by JavaScript code.

## How to Play

1. Open the `index.html` file in your web browser.
2. Enter your guess into the input field.
3. Click the "Submit" button to check your guess.
4. Receive feedback on your guess and continue guessing until you guess the correct number.

## Getting Started

To get a local copy of this project and run it on your machine, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/number-guessing-game.git
   ```

2. Navigate to the project directory:

   ```bash
   cd number-guessing-game
   ```

3. Open the `index.html` file in your preferred web browser.

## Features

- Generates a random number between 1 and 100 for the user to guess.
- Provides feedback to the user based on their guess (whether it's too low, too high, or correct).
- Keeps track of the number of attempts made by the user.
- Interactive user interface with input field and submit button.

## Code Structure

- The random number is generated using `Math.random()` and stored in the variable `randomNum`.
- The user's guess is retrieved from the input field and compared with the random number using conditionals.
- Feedback messages are displayed based on the comparison result.
- The number of attempts is incremented with each guess and displayed to the user.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, feel free to fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
