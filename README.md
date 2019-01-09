# GAUCHOBALL (AKA RAGE CAGE)

## Background & Overview 

Gauchoball is a fast-paced drinking game for a large group (7+ ideally) that involves bouncing all ball into a cup. Here's how it works.

### Materials:

Table: Long and rectangular is ideal.
2 ping pong balls
30+ solo cups: actual number is your choice; the more cups, the longer the game goes; at least 4 cups per person at the table recommended.

### Setup:
All but two cups are filled to beer-pong level. Filled cups may be placed in a hexagon shape in the center of the table or a line going the length of the center of the table.
Everyone lines up, standing around the table, similar to flip cup.
### Game Play:

BASIC MECHANICS
The two people that start the game are given one empty cup and one ping pong ball each. 
Each player is to bounce the ball into their cup while the cup is on the table. Once you have made a ball into your cup, you pass the cup to the person on your LEFT. It is now their turn to shoot.

STACKING CUPS
When two players (both trying to bounce the ball into their own cup) are adjacent, this is where things get fun. For brevity, these players will be referred to as LEFT Player and RIGHT Player. 
If RIGHT Player makes the cup before LEFT Player, RIGHT Player must stack their empty cup on top of the empty cup that belongs to LEFT Player (the cup LEFT Player is actively shooting at). If LEFT Player achieves this (does not count if the ball that LEFT Player is using is sandwiched between the two cups), then:
LEFT Player passes the stack of cups to the player to his LEFT. The player to his left begins shooting immediately.
RIGHT Player celebrates, he humiliated LEFT Player
LEFT Player must choose a cup from the center (filled with beer), chug it, and his turn starts again.
DIFFICULTY INCREASES WITH TIME
As the cups pile up, someone will have to shoot on the increasingly large stack. This makes it increasingly difficult as the game goes on.
WINNING
The game is over when all the cups in the middle of the table have been drank. Everyone is a winner.
Additional Rules:
If someone makes a bounce on their first attempt, they can pass the cup to ANYONE in the table, as opposed to just the person to their LEFT. Strategically, it makes sense to pass the cup to the person to the RIGHT of whoever else is actively shooting--that's not required though.
If someone accidentally bounces the ball into one of the center cups, DRINK IT! Then stack it on their cup they are shooting at and continue shooting.

Functionality & MVP 

BASIC MVPs

- [ ] Create key / mouse functions for power and direction
- [ ] Implement cup rotation and gameplay logic
- [ ] Start, pause & play the game
- [ ] AI Players with randomized power and direction
- [ ] Rules modal describing the game rules
- [ ] Deploy production game and write ReadMe

Bonus MVPs

- [ ] Play music during the game
- [ ] Create backend for custom name leaderboard cups scored & assisted

Wireframes

Shit

Architecture & Technologies

Vanilla JavaScript - overall structure and game logic
HTML5 Canvas - DOM manipulation and rendering
Web Audio API - for sound generation, processing and control
Webpack to bundle and serve up the various scripts

Implementation Timeline 
Day 1
Setup all necessary Node modules, including getting webpack up and running. Create webpack.config.js as well as package.json. Write a basic entry file and the bare bones of all 4 scripts outlined above. 
- [ ] Get webpack serving files and frame out index.html
- [ ] Finish bounce power and direction physics
Day 2
[x] Port over the relevant pieces of my Asteroids(with collision physics) project and implement Asteroid creation
Day 3
Dedicate this day to learning the Web Audio API. First, build out the AudioEvent object to connect to the Board object. Then, use board.js to create and render Asteroids and AudioEvents. Goals for the day:
[x] Complete the asteroids.js module (constructor, update functions, colors)
[x] Get sounds to play on collisions
[x] Build first sound library
[x] Get collision graphics working
[ ] Make the Asteroids able to be created with mouse. Set vectors on mouse release.


Day 4
Create the logic backend. Build out modular functions for handling the different evolutions. Goals for the day:
[ ] Build Markov Matrix object and link it with collisions
[ ] Have a functional screen on the Canvas frontend that correctly handles creation and running of the simulation.
[ ] Make sure that starting, stopping, and resetting works.
Day 5
Install the controls for the user to interact with the game. Style the frontend, making it polished and professional. Goals for the day:
[ ] Create controls for game speed, stop, start, restart, reset
[ ] Build out list of instruments
[ ] Have a styled Canvas, nice looking controls and title
Over the weekend:
[ ] Test the project for bugs
[ ] Deploy the project on GitHub Pages


Bonus Features 

- [ ] Learn enough Web Audio to render an object to the Canvas element and create a sound
- [ ] Complete WebAudioAPI Tutorial and loaded basic sound from static assets
- [ ] Export an AudioEvent object with correct type and handling logic

