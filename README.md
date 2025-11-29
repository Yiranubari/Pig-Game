#  Pig Game

The Pig Game is a simple, two-player dice game built using HTML, CSS, and vanilla JavaScript. The objective is to be the first player to reach a total score of 100 points.

##  Game Rules

The game is played between two players, and the rules are as follows:

1.  **Starting the Game**: The game starts with both players having a score of 0. Player 1 is the active player.
2.  **Rolling the Dice**: The active player clicks the "Roll dice" button.
    *   If the player rolls a number **2 through 6**, the number is added to their **Current Score**, and they can choose to roll again or hold.
    *   If the player rolls a **1**, their **Current Score is lost (reset to 0)**, and the turn immediately passes to the other player.
3.  **Holding the Score**: The active player can click the "Hold" button at any time.
    *   The **Current Score** is added to their **Global Score**.
    *   The turn passes to the other player.
4.  **Winning the Game**: The first player to reach a **Global Score of 100 or more** wins the game.
5.  **New Game**: The "New game" button resets all scores and starts a fresh game with Player 1 as the active player.

##  Technologies Used

This project is a classic example of a front-end web application, utilizing the following core technologies:

| Technology | Purpose |
| :--- | :--- |
| **HTML5** | Provides the structure and content of the game interface. |
| **CSS3** | Handles the styling, layout, and visual presentation. |
| **JavaScript (ES6+)** | Implements the core game logic, dice rolling, score tracking, and player switching. |

## Project Structure

The repository contains the following files:

```
Pig-Game/
└── Pig Game/
    ├── index.html          # Main game interface
    ├── style.css           # Styling for the game
    ├── script.js           # Core game logic and functionality
    ├── pig-game-flowchart.png # Visual representation of the game flow
    ├── dice-1.png
    ├── dice-2.png
    ├── dice-3.png
    ├── dice-4.png
    ├── dice-5.png
    └── dice-6.png          # Dice images for visual feedback
```

##  Getting Started

To run this game locally, simply follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Yiranubari/Pig-Game.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd Pig-Game/"Pig Game"
    ```
3.  **Open `index.html`:**
    Open the `index.html` file in your preferred web browser (e.g., Chrome, Firefox, Safari).

The game will load, and you can start playing immediately.


