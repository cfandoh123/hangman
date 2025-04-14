# Hangman Game

## Description
This project contains both a terminal-based and GUI-based hangman game. The game randomly selects a word from a JSON file and allows the player to guess the word letter by letter or by guessing the entire word at once.

## Features
- Terminal-based version for simple gameplay
- GUI version with:
  - Interactive clickable keyboard
  - Visual hangman images
  - Sound effects for game events
  - Clean, user-friendly interface

## Prerequisites
For the terminal version:
- Python 3.x

For the GUI version:
- Python 3.x
- Pygame (`pip install pygame`)
- Image files for the hangman stages
- Sound files for game events (optional)

## Files
- `hangman.py` - Original terminal-based version
- `hangman_pygame.py` - GUI version with Pygame
- `words.json` - Contains the word list for the game
- `images/` - Directory containing hangman stage images
- `sounds/` - Directory containing sound effects

## How to Run the Game

### Terminal Version
```
python hangman.py
```

### GUI Version
```
python hangman_pygame.py
```

## Setting Up the GUI Version
1. Install Pygame: `pip install pygame`
2. Create an `images` folder and add hangman stage images (hangman0.png through hangman6.png)
3. (Optional) Create a `sounds` folder and add sound effect files:
   - correct.wav - For correct letter guesses
   - wrong.wav - For incorrect letter guesses
   - win.wav - For winning the game
   - lose.wav - For losing the game

## How to Play
1. Run the game
2. For the terminal version, type letters or words to guess
3. For the GUI version, click on letters to make your guesses
4. Try to guess the word before the hangman is complete!

## Customization
- Add your own words to `words.json`
- Create custom hangman images
- Record your own sound effects

## License
[Your License Information Here]
