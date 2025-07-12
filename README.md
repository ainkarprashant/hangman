# Hangman Game

Welcome to the **Hangman Game**! This is a simple Python implementation of the classic word-guessing game. Test your vocabulary and guessing skills by trying to uncover the hidden word before you run out of lives!

## Features

- Random word selection from a predefined word list.
- Visual representation of lives using ASCII art.
- Tracks guessed letters and prevents duplicate guesses.
- Displays progress as you guess letters correctly.
- Win or lose messages based on the outcome of the game.

## How to Play

1. Run the game using Python.
2. A random word will be selected, and you will see placeholders (`_`) for each letter.
3. Guess one letter at a time by typing it into the console.
4. If your guess is correct, the letter will be revealed in the word.
5. If your guess is incorrect, you lose a life. You have 6 lives in total.
6. The game ends when you either guess the word correctly or run out of lives.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/hangman.git
   ```
2. Navigate to the project directory:
   ```bash
   cd hangman
   ```
3. Ensure you have Python installed (version 3.6 or higher).
4. Run the game:
   ```bash
   python main.py
   ```

## Project Structure

```
hangman/
├── hangman_art.py       # Contains ASCII art for the game
├── hangman_words.py     # Contains the word list for the game
├── main.py              # Main game logic
└── README.md            # Project documentation
```

## Example Gameplay

```
Welcome to Hangman!
**************************** 6 /6 LIVES LEFT ****************************
Word to guess: _ _ _ _ _
Guess a letter: a
Word to guess: _ a _ _ _
**************************** 5 /6 LIVES LEFT ****************************
Guess a letter: z
You guessed 'z', that's not in the word. You lose a life.
...
```

## Contributing

Feel free to contribute to this project by submitting issues or pull requests. Suggestions for improvements are always welcome!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- ASCII art and word list inspired by various online resources.
- Developed as a fun project to practice Python programming.

---

Enjoy playing Hangman and have fun guessing!