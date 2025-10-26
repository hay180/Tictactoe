# Tic-Tac-Toe Game

A beautiful, modern implementation of the classic Tic-Tac-Toe game built with React.

## Features

- **Modern UI Design**: Beautiful gradient background with smooth animations and transitions
- **Responsive Layout**: Works perfectly on desktop and mobile devices
- **Move History**: Track all moves and jump back to any point in the game
- **Draw Detection**: Automatically detects when the game ends in a draw
- **Winning Highlights**: Winning squares are highlighted with a pulsing animation
- **Current Move Indicator**: The current move is highlighted in the history list
- **Hover Effects**: Interactive feedback when hovering over squares
- **Disabled Squares**: Already-played squares are disabled to prevent accidental clicks

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Navigate to the project directory:
```bash
cd 445b13a8-b3ce-46a1-8e42-5f02f3af2639
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

## How to Play

1. The game starts with player X
2. Click on any empty square to place your mark
3. Players alternate turns between X and O
4. The first player to get 3 marks in a row (horizontally, vertically, or diagonally) wins
5. If all squares are filled and no player has won, the game is a draw
6. Use the move history on the right to jump back to any previous state of the game

## Technologies Used

- React 19.2.0
- React Scripts 5.0.0
- CSS Grid for modern layout
- CSS Animations for smooth transitions

## Code Improvements

This version includes several enhancements over the basic implementation:

1. **CSS Grid Layout**: Replaced float-based layout with modern CSS Grid
2. **Loop-based Rendering**: Board squares are rendered using `map()` instead of hardcoding
3. **Enhanced Winner Detection**: Returns both winner and winning line for highlighting
4. **Draw Detection**: Added logic to detect when all squares are filled
5. **Accessibility**: Disabled attribute on played squares for better UX
6. **Visual Feedback**: Hover effects, animations, and current move highlighting
7. **Responsive Design**: Mobile-friendly layout with media queries
8. **Modern Styling**: Professional color scheme with gradients and shadows

## Available Scripts

- `npm start` - Runs the app in development mode
- `npm build` - Builds the app for production
- `npm test` - Runs the test suite
- `npm eject` - Ejects from Create React App (one-way operation)

## License

This is a learning project based on the React documentation tutorial.
