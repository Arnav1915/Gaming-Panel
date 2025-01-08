
# Gaming Panel

A Python-based multi-game platform featuring classic and interactive games, wrapped in a user-friendly interface for seamless gaming.

## Features
- **Multiple Games**: Includes Snake, Asteroids, DodgeBlock, Connect 4, and more.
- **User Authentication**: Secure registration and login system with SQLite.
- **Game Stats Tracking**: Stores and tracks user information and game progress.
- **Modular Design**: Organized codebase with reusable functions.
- **Interactive Interface**: Simple GUI for an engaging gaming experience.

## Tech Stack
- **Programming Language**: Python
- **Database**: SQLite
- **UI**: Built using `tkinter` and `Pillow`.

## Prerequisites
1. Python 3.x installed on your system.
2. Install required Python libraries:
   ```bash
   pip install Pillow numpy pygame
   ```

## How to Run
1. Clone this repository:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the project directory:
   ```bash
   cd Gaming-Panel-main
   ```
3. Run the main file to start the panel:
   ```bash
   python HomePage.py
   ```

## Project Structure
- **`HomePage.py`**: Main entry point for the gaming panel.
- **`Account.py`**: Handles user account operations.
- **`AllFunctions.py`**: Utility functions shared across modules.
- **Game Files**:
  - `Asteroids.py`, `DodgeBlock.py`, `connect4.py`, `snake.py`: Game implementations.
- **Database**:
  - `GameDB.db`, `demo.db`: SQLite databases for user data and stats.

## Preview
### Login Page
![Login Page Preview](Gaming-Panel-main/login_page_preview.jpg)

### Homepage
![Homepage Preview](Gaming-Panel-main/homepage_preview.jpg)

## Libraries Used
- `Pillow`: For image handling in the interface.
- `numpy`: For numerical computations.
- `pygame`: For game logic and rendering.
- `tkinter`: For GUI development.

## Future Enhancements
- Add more games.
- Improve user experience with advanced GUI features.
- Add a leaderboard to display high scores.

## Contribution
Feel free to fork this repository and contribute by submitting a pull request. Suggestions and feedback are welcome!

## License
This project is licensed under the MIT License - see the LICENSE file for details.

---

Enjoy gaming with this Python-powered panel!
