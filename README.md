# FlipKArtgame

A lightweight browser game collection built with pure HTML, CSS, and JavaScript. This repository includes a classic Memory Game and a Snake game, both designed to run without any external dependencies.

## Games Included

### 1. Memory Game
A responsive, accessible card-matching game where players flip cards to find matching pairs. It includes:

- 4x4 and 6x6 grid modes
- move counter and timer
- star rating system
- local best-score tracking
- keyboard navigation support
- responsive layout

Open `memory-game.html` in a browser to play.

### 2. Snake Game
A classic arcade Snake game built in a single HTML file. It includes:

- keyboard controls with arrow keys or WASD
- score and best score tracking
- pause and restart controls
- collision detection and game-over flow
- responsive board design

Open `snake-game.html` in a browser to play.

## How to Run

You can either open the HTML files directly in a browser or serve the project locally.

### Option 1: Open directly
- Open `memory-game.html` for Memory Game
- Open `snake-game.html` for Snake Game

### Option 2: Local web server
From the project folder, run:

```bash
python -m http.server 8000
```

Then visit:

- http://localhost:8000/memory-game.html
- http://localhost:8000/snake-game.html

## Project Structure

- `memory-game.html` — Memory game implementation
- `snake-game.html` — Snake game implementation
- `PRD_dark_theme.md` — dark theme requirements for the memory game
- `PRD_snake_game.md` — Snake game requirements
- `context.md` — project context overview

## Notes

- This project uses only front-end web technologies.
- No external libraries or package installs are required.
- Best scores are stored locally in the browser using `localStorage`.

## License

This project is for learning and personal demo purposes.
