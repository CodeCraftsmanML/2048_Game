# 2048 Game

**2048 Game** is a Python implementation of the classic 2048 game. The project features an interactive graphical user interface (GUI) and adheres to the original game rules. It is organized into three main directories for clarity and efficiency.

## Project Structure

- **Notebooks/**: 
  - **`Logics.ipynb`**: Contains the core game logic and algorithms. It includes functions such as `start_game`, `add_constant_2`, `transpose_matrix`, `reverse_matrix`, `move_left`, `move_right`, `move_up`, and `move_down`.

- **Script/**:
  - **`Logics.py`**: Implements the updated game logic based on the functions described in `Logics.ipynb`.
  - **`2048.py`**: Utilizes Tkinter to create the GUI for the game, handling frame management, layout, and user interactions.
  - **`constants.py`**: Defines constants like grid size, tile colors, background color, and key bindings for game controls.

- **venv/**:
  - **`requirements.txt`**: Lists the Python dependencies required to run the game, ensuring all necessary packages are installed in the virtual environment.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/2048-game.git
    ```

2. **Navigate to the project directory**:
    ```bash
    cd 2048-game
    ```

3. **Create and activate a virtual environment** (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

4. **Install the required dependencies**:
    ```bash
    pip install -r venv/requirements.txt
    ```

## Usage

1. **Run the main game script**:
    ```bash
    python Script/2048.py
    ```

2. **Interact with the game** using the GUI. The game features keyboard controls for movement and follows the classic 2048 rules.

## Contributing

Feel free to fork the repository and submit pull requests for improvements or bug fixes. Contributions are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or issues, please contact [your email address].
