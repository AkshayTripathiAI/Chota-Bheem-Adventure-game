# Chota Bheem Adventures

A simple endless runner in the browser: Bheem jumps over a charging bull in a jungle, and the bull gets faster with every successful dodge.

This is a non-commercial, fan-made practice game. Characters and names belong to their respective owners; this is a non-commercial fan project. Images and audio are used for learning purposes.

**Live demo:** https://akshaytripathiai.github.io/Chota-Bheem-Adventure-game/

## How to play

- Click **Lets Run** to start.
- **Up arrow**: jump. **Left / Right arrows**: step backward / forward.
- Each time the bull passes you without a collision you score a point and the bull speeds up.
- If the bull hits you the game ends; reload the page to play again.

## Features

- Built with DOM elements and CSS animations (no canvas)
- Animated GIF sprites and background
- Background music and a game-over sound
- Increasing difficulty as your score goes up

## Tech stack

- HTML, CSS (keyframe animations)
- Vanilla JavaScript

## Run locally

```bash
git clone https://github.com/AkshayTripathiAI/Chota-Bheem-Adventure-game.git
cd Chota-Bheem-Adventure-game
npx serve .
```

Or open `index.html` directly in a browser.

## Project structure

```
index.html   # start page and game area
script.js    # controls, collision detection, scoring
style.css    # layout and animations
*.gif/*.png  # sprites and backgrounds
*.mp3        # music and sound effects
```

## Related projects

- [basic-bheem-ladoo-game](https://github.com/AkshayTripathiAI/basic-bheem-ladoo-game) and [Bheem-Ladoo-2](https://github.com/AkshayTripathiAI/Bheem-Ladoo-2) - canvas games with the same characters
- [Adventure-Game](https://github.com/AkshayTripathiAI/Adventure-Game) - bundles this game (as Game 3) with the others in one page
