# Project Pitches

## Brainstorm

1. Mehtab - Create a trivia game 
    - draws on each group member's passions
    - tracks user score between attempts and sessions
    - user can pick a topic or all topics
    - separate page for each topic
    - MVP: program quizzes on different topics, provides
        feedback on responses, tracks scores across
        attempts in localStorage
2. Chris - Battlebots (Battleship w/ twist)
    - inspired by CSS grid-garden
    - similar to battleship, but ships are bots and not all linear
    - generate grid, bots, and RNG for computer actions
    - user provides input for attacks.
    - MVP: a game where user battles the computer
    - computer and player bot locations are randomly generated
    - stretch: implement single- or 2-player modes; user picks where they place their bots at game start
3. Ciane - Burger Stacking game
    - ingredients fall from the sky
    - goal is to build the burger as high as possible
    - user moves burger/bun left/right to position it under falling ingredients
    - missed ingredients cause the player to lose lives
    - stretch: change difficulty, changing falling speed or number of starting lives
    - user scoreboard tracks across sessions
4. Julian - Tetris
    - make Tetris
    - gamespace is a grid
    - falling pieces that can be rotated to fit into previous pieces.
    - use CSS transitions to smooth falling animation
    - user scoreboard tracks across sessions
5. Do multiple (stretch???)
6. Wordle
7. Recipe book
8. Business page
9. Interactive to-do list
10. Reminder for favorite bands touring nearby
11. Create a whiteboard
12. Service to recommend books/media based on tastes
13. Anti-climate change app

## Project Pitch 1: Recreate Tetris

Recreating Tetris will challenge our skills in Javascript with implementation of game logic and displaying the game in the canvas. It will force us to use the CSS we've learned to smooth game animations and create the styling for the page.

### Minimum Viable Product

- A working game with eventListeners that mirrors the logic of the original Tetris game and displays the major components of the game (game area, stacked pieces, falling pieces).
  - Player can rotate pieces and move left/right as they fall.
  - Rows clear when complete.
  - Next piece is randomly determined
  - Stores scores in localStorage.
  - falling pieces stack on existing ones

### Additional components

- Allow player to submit their name with the score.
- Additional game mode.
- Additional page to display stylized leaderboard.
- Additional page for a separate game (trivia/battlebots/burgerstack)

## Project Pitch 2: Recreate Lilo/Stitch Burger Stack

Similar to Tetris, this project will require us to use eventListeners and the canvas to display the game, receive user input, and represent objects and interactions in space. We will need to use CSS to aid in animation, and general site styling. 

### Minimum Viable Product

- A working game that correctly implements the logic, but is not pretty.
  - ingredients fall from the sky
  - goal is to build the burger as high as possible
  - user moves burger/bun left/right to position it under falling ingredients
  - next ingredient is randomly determined
  - missed ingredients cause the player to lose lives
  - user scoreboard tracks across sessions (localStorage)
  - Single level, constant falling speed

### Additional Components

- Create level system that gets progressively harder
- Create infinite mode, where speed gradually increases
- Change difficulty, changing falling speed or number of starting lives
- add bad ingredients to avoid
