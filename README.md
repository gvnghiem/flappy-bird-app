# Flappy Bird Game

A simple implementation of the classic Flappy Bird game using Python and Pygame, featuring a single sprite sheet for all game assets.

## Overview

This project is a recreation of Flappy Bird, where the player navigates a bird through a series of pipes by flapping its wings with the spacebar. The game includes three states: idle (start screen), playing, and game over. All graphics are sourced from a single 800x800 pixel sprite sheet which can be downloaded from here [spritesheet.png](https://www.pngfind.com/mpng/iRmmbbJ_flappy-bird-atlas-png-atlas-png-flappy-bird/)

### Features
- **Sprite Sheet Integration**: Background, bird animations, and pipes are loaded from a single sprite sheet.
- **Bird Animation**: Three-frame animation for the bird (flapping wings).
- **Scoring**: Earn points by passing through pipe gaps.
- **Collision Detection**: Game ends if the bird hits a pipe or goes out of bounds.
- **Responsive Controls**: Spacebar to flap, 'Q' to quit from idle/game over states.

## Prerequisites

- **Python 3.x**: Ensure Python is installed (download from [python.org](https://www.python.org/)).
- **Pygame**: Install via pip:
  ```bash
  pip install pygame
