# Blackjack Game

This is a simple Blackjack game implemented using JavaScript, HTML, and CSS. The game allows a player to play against the computer.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Game Rules](#game-rules)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)
- [License](#license)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/blackjack-game.git
    cd blackjack-game
    ```

2. Install the dependencies:
    ```sh
    npm install
    ```

3. Start the development server:
    ```sh
    npm run dev
    ```

## Usage

Open your browser and navigate to `http://localhost:3000` to start playing the game.

## Game Rules

- The goal of the game is to beat the computer by having a hand value closest to 21 without exceeding it.
- Number cards (2-10) are worth their face value.
- Face cards (J, Q, K) are worth 10 points.
- Aces can be worth 1 or 11 points, depending on which value benefits the hand more.

## Project Structure

```
blackjack-game/
├── index.html
├── main.js
├── package.json
├── src/
│   └── blackjack/
│       ├── index.js
│       └── usecases/
│           ├── askCard.js
│           ├── cardValue.js
│           ├── computerTurn.js
│           ├── createCard.js
│           ├── create-deck.js
│           └── index.js
├── style.css
└── .gitignore
```

## Dependencies

- [SweetAlert2](https://sweetalert2.github.io/) - For displaying alerts.
- [Underscore.js](https://underscorejs.org/) - For utility functions.
- [Vite](https://vitejs.dev/) - For development and build tooling.

## License

This project is licensed under the MIT License.