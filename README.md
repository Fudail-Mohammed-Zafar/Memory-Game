# Memory Card Game

A simple memory-matching card game built with HTML, CSS, and JavaScript. The player must match pairs of cards by flipping them over. After finishing the game, the cards are shuffled for a re-match.

## Table of Contents
- [Features](#features)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [How to Play](#how-to-play)

## Features
- Flip cards to reveal hidden images.
- Match pairs of cards.
- Animated flipping and shaking effects for mismatched cards.
- Random card shuffle at the beginning of each game.
- Responsive and interactive UI.

## Project Structure
```
├── Images/                  # Folder containing card images
│   ├── img-1.png
│   ├── img-2.png
│   ├── img-3.png
│   ├── img-4.png
│   ├── img-5.png
│   ├── img-6.png
│   ├── img-7.png
│   └── img-8.png
├── index.html               # Main HTML file
├── styles.css               # CSS file for styling
└── script.js                # JavaScript file for game logic
```

## Technologies Used
- HTML5
- CSS3
- JavaScript

## How to Play
1. Click on any card to flip it over.
2. Try to find the matching pair by flipping another card.
3. If both cards match, they remain flipped; if they don't, they will flip back.
4. The game ends when all cards have been matched.
5. Cards are shuffled every time a game starts or when all matches are found.
