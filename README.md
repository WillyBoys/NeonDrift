# Neon Drift

Neon Drift is a one file browser game inspired by classic arcade space dodgers. You pilot a small ship, weave through incoming asteroids, build combos with near misses, and use a dash to survive longer and push hazards out of the way.

## AI Generated Code Disclosure

This repository exists as a research experiment in **Vibe Coding**.

**The game code in this repo was generated 100 percent by AI.**  
The goal was to explore how far an AI assisted workflow can go when building a complete, playable project from prompts, iteration, and fast feedback.

What that means:

- The HTML, CSS, and JavaScript were produced through AI generation and follow up AI edits.
- The code may include non standard patterns, duplicated logic, or rough edges that a typical human written project would refactor.
- Any bugs, balancing quirks, or weird behaviors should be considered part of the experiment and learning process.

If you are reviewing this project, please treat it as a prototype and a documentation artifact for AI assisted development rather than a polished production codebase.

## Play the Game

Open `index.html` in a browser, or play the hosted version if this repo is connected to GitHub Pages.

## How to Play

### Goal
Survive as long as possible while dodging asteroids. Your score increases over time, and you can earn bonus points through risky movement and dash interactions.

### Controls

#### Desktop
- Move: **W A S D** or **Arrow Keys**
- Dash: **Space**
- Start or restart: **Enter** or click **Play**

#### Mobile
- Move: **Drag** your finger to steer the ship
- Dash: **Double tap**
- Start: **Tap**

## Gameplay Features

### Asteroids
Asteroids spawn from the edges and travel across the screen. Over time, the game ramps up by spawning more asteroids and increasing their speed.

### Dash
Dash provides a quick burst of speed and can be used to escape tight situations. In this build, dashing can also interact with asteroids by pushing them away, which can create openings and chain reactions.

### Near Miss and Combo
Passing very close to an asteroid without colliding can count as a near miss. Near misses increase your combo multiplier for a short window. If you stop chaining near misses, the combo resets.

### Storms
Occasionally the game enters a storm event. Storms increase intensity for a short time, typically by making asteroid spawns denser and the screen more chaotic.

### Cosmetics
Skins unlock based on best score milestones. You can select unlocked cosmetics on the game over screen.

### Leaderboard
This project includes an optional global leaderboard submission flow. It may require verification and a network connection.

## Notes

- This is intentionally built as a single file game for simplicity and experimentation.
- If you want to fork and modify it, feel free. If you do, consider adding a note about what was changed and whether the AI generated design was retained or replaced.

## License

No explicit license is provided by default. If you plan to reuse or distribute this project, add a license file that matches your intended usage.