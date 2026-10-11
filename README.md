# Tic-Tac-Toe with React

A small tic-tac-toe game built while learning React with the official React documentation. Two players take turns placing **X** and **O** on a 3 × 3 board.

## Features

- Shows which player's turn is next.
- Detects and displays the winner when three matching marks line up.
- Keeps a history of moves so you can jump back to any earlier board position and continue playing from there.
- Uses React components and state to update the interface as the game changes.

## Built with

- React
- JavaScript
- CSS
- Create React App (`react-scripts`)

## Getting started

### Requirements

- [Node.js](https://nodejs.org/) and npm
- Git (optional, for cloning the repository)

### Install and run

1. Clone this repository:

   ```bash
   git clone https://github.com/sheshikiran1308/TIC-TAC-T0E-with-react.git
   ```

2. Move into the project folder:

   ```bash
   cd TIC-TAC-T0E-with-react
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm start
   ```

The app will open at [http://localhost:3000](http://localhost:3000). If it does not open automatically, visit that address in your browser.

## How to play

1. Click an empty square to place your mark.
2. Players alternate between X and O.
3. The first player to get three marks in a row, column, or diagonal wins.
4. Use the move-history buttons to revisit a previous position.

## Project structure

```text
public/
  index.html       HTML page containing the React root element
src/
  App.js           Game components, state, and winner detection
  index.js         React entry point
  styles.css       App styles
package.json       Project scripts and dependencies
```

## Learning notes

This project is a practice project for learning React concepts from the [official React tutorial](https://react.dev/learn/tutorial-tic-tac-toe), including components, props, state, rendering lists, and handling events.

## Available scripts

- `npm start` — run the development server.
- `npm run build` — create a production build in the `build` folder.
- `npm test` — run the test runner in watch mode.

## License

This project is for learning and practice. No license has been specified.
