# US-state-game
This is an interactive U.S. States guessing game built with Python and the `turtle` module. The game challenges players to name all 50 states by typing their names.

## Features
- Interactive GUI using `turtle`
- Users can type the names of U.S. states to guess them
- Correct answers are displayed on the map at the corresponding location
- The game tracks progress by counting correct guesses
- Unanswered states are saved in a CSV file for later learning

## Requirements
Ensure you have Python installed along with the following dependencies:
- `turtle`
- `pandas`

## How to Play
1. Run the `main.py` script.
2. A blank U.S. map appears.
3. Type the name of a U.S. state in the prompt box.
4. If correct, the state's name appears on the map.
5. If you type `Exit`, the game saves the missing states in `States_to_Learn.csv`.
6. Try to name all 50 states!

## File Structure
```
.
├── blank_states_img.gif  # Background image of U.S. map
├── main.py               # Main game logic
├── 50_states.csv         # Contains state names and coordinates
├── States_to_Learn.csv   # List of states the player missed
```

## Future Improvements
- Add difficulty levels
- Implement hints for hard-to-guess states
- Introduce a timer for added challenge

## Contributing
If you'd like to contribute, feel free to fork the repository and submit a pull request.

