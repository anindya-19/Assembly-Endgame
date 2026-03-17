# Assembly: Endgame 🎮

A fun, themed word-guessing game built with React — inspired by Hangman but with a programming twist. Guess the hidden word before the programming languages are wiped out one by one... or you'll be forced to code in **Assembly**! 😱

## 🎯 How to Play

1. A random word is chosen at the start of each game.
2. Click letters from the on-screen keyboard to guess the word.
3. You have **8 attempts** (one per programming language).
4. Each wrong guess "eliminates" a programming language (HTML, CSS, JavaScript… all the way to Assembly).
5. **Guess the word correctly** to save the programming world!
6. Fail, and you've condemned everyone to write Assembly forever. 😭

## ✨ Features

- 🔤 Random word selection from a built-in word list
- 🌐 Visual language chips that "die" with each wrong guess
- 🎉 Confetti celebration on winning
- ♿ Accessible keyboard and screen reader support (`aria-live` regions)
- 🔁 New Game button to play again instantly
- 💬 Randomized farewell messages for each eliminated language

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| React 18 | UI framework |
| Vite | Build tool & dev server |
| clsx | Conditional CSS class utility |
| react-confetti | Win celebration effect |

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or higher recommended)
- npm

### Installation

```bash
# Clone the repository
git clone <your-repo-url>
cd "Assembly Endgame"

# Install dependencies
npm install
```

### Running Locally

```bash
npm run dev
```

Then open your browser and navigate to `http://localhost:5173`.

### Build for Production

```bash
npm run build
```

Preview the production build:

```bash
npm run preview
```

## 📁 Project Structure

```
Assembly Endgame/
├── index.html        # HTML entry point
├── index.jsx         # React app entry point
├── App.jsx           # Main game component
├── languages.js      # Programming language data (names & colors)
├── words.js          # Word list for the game
├── utils.js          # Helper functions (random word, farewell text)
├── index.css         # Global styles
└── vite.config.js    # Vite configuration
```

## 🎨 Programming Languages in the Game

The game features **9 languages** as lives, eliminated in this order:

`HTML` → `CSS` → `JavaScript` → `React` → `TypeScript` → `Node.js` → `Python` → `Ruby` → `Assembly`

Lose all 8 non-Assembly guesses and it's game over — Assembly wins. 🤖

## 📜 License

This project was built as part of the [Scrimba Full-Stack Path](https://scrimba.com/fullstack-path-c0fullstack) curriculum.
