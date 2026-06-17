# Snake game
A simple recreation of the traditional snake game using HTML5 canvas and JavaScript

The idea is straight forward, collect eggs and grow the snake, try to survive as long as you can without colliding with the walls or yourself. There are some mysterious eggs that you can eat, but keep in mind that they can bring you good or bad things.

# About this project
This project is made using vanilla JS, the canvas API and local storage to practice basic game development skills without relying on any libraries.

# Features
- Classic snake movement with animation between each two cells
- Next moves saving in a query
- Egg collection system
- Snake growing mechanism
- Powerups system
- Scoring system with the high score saved in the local storage
- Keyboard controlls for windows
- Swipe contol for mobile and touch screen devices
- Playable entirely on the browser

# Controls

### PC
Use the arrow keys to control the snake
- ↑ Move up
- ↓ Move down
- ← Move left
- → Move right

### Mobile
Swipe in the desired direction for the snake's movement

# Rules
- Move the snake to collect eggs
- Each egg increases the length of the snake by 1 cell
- Avoid colliding with your body or the walls
- If collision happens, the game is over
- Eat the mysterious egg to get a random powerup

#PowerUps
- Speed up : increases your speed to 10 squares per second for 7 seconds
- Slow down : decreases your speed to 5 squares per second for 10 seconds
- More fruits : Each fruits you eat spawns two other fruits for 10 seconds
- Grow Up : Each square, the length of the snake increases by 1 for 2 seconds
- Shrink Down : Each square, the length of the snake decreases by 1 for 2 seconds
- Invincible : You stop colliding with your self for 15 seconds, make sure to not be colliding when time ends
- 2x Score : Basically gives you double score for each egg

# Running this project
- Clone the repository
- Open 'index.html' file in your browser

Or just visit 'https://mohammedmostafawebdeveloper.github.io/Snake-game/'
