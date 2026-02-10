# Word Drop

A typing challenge game where words fall from the sky — type them to destroy them before they reach the bottom.

Built for [**Vibe Coding: Building Software in Conversation with AI (TECH 42)**](https://continuingstudies.stanford.edu/courses/professional-and-personal-development/vibe-coding-building-software-in-conversation-with-ai/20252_TECH-42) at Stanford Continuing Studies, Winter 2025. Instructor: Elliott Adams.

## Play

Open `index.html` in any browser. No install, no dependencies, no build step.

## How It Works

- Words fall from the top of the screen
- Type a word exactly to destroy it — earn points and build combos
- Miss 3 words and it's game over
- Difficulty increases every 10 words: faster drops, shorter spawn intervals, longer words

## Features

- **Combo scoring** — consecutive correct words multiply your points
- **3 word tiers** — green (short/easy), yellow (medium), red (long/hard)
- **Partial match highlighting** — matching words glow as you type
- **Particle effects** — explosions on word destruction
- **Progressive difficulty** — levels unlock harder words and increase speed
- **Game over stats** — score, words destroyed, max combo, time survived

## Built With

Single conversation with Claude (Opus 4.6) using [Claude Code](https://claude.ai/claude-code). One self-contained HTML file, zero external dependencies. ~580 lines of vanilla HTML/CSS/JavaScript.
