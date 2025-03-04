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

  
### Changes Made:
1. **Features**: Added "Sound Effects" to the list, describing the audio cues.
2. **Setup**: Updated step 2 to include the MP3 sound files with their purposes.
3. **File Structure**: Updated to list `die.mp3`, `hit.mp3`, `flap.mp3`, and `point.mp3` instead of mp3 files.
4. **Troubleshooting**: Added a note about sound errors specific to MP3s.
5. **Credits**: Added a mention of [101soundboards.com](101soundboards.com) as the source of the sound effects.

