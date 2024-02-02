Whack-a-Mole Web Game
Overview
This Whack-a-Mole web game is the final capstone project for a web development program. The game is based on the classic arcade game where players use a mallet to hit moles that appear at random, back into their holes. Your task is to complete the game using your JavaScript, HTML, and CSS skills, and add a unique touch to the design.

Installation
To get started with the game, follow these steps:

Fork and clone this repository.
Navigate to the project's folder.
Run npm install to install dependencies.
To run the unit tests, use npm test. Note that passing all tests is recommended but not required to complete the assignment.
Files and Structure
index.html: The HTML document that holds the game structure. Modify this file to pass the tests.
src/styles.css: The CSS file for styling the game. You can make optional changes to enhance the appearance.
src/index.js: The JavaScript file containing the game functionality. Modify this file to pass the tests.
test/solution.test.js: Unit tests for the game.
User Stories
US-01 - Basic game structure
Add a title to the game, surrounded by h1 tags. Example: <h1 id="title"> Whack-a-Mole </h1>
Add nine holes and moles to the grid in index.html.
Define a start button in index.html.
Use querySelector() to access elements in index.js.
US-02 - Basic game functionality: Randomness
Implement randomInteger(min, max) function.
Implement setDelay(difficulty) function.
Implement chooseHole(holes) function.
US-03 - Game flow
Implement toggleVisibility(hole) function.
Implement showAndHide(hole, delay) function.
Implement showUp() function.
Implement gameOver() function.
Uncomment and implement startGame() function.
US-04: Whack!
Implement updateScore() function.
Implement clearScore() function.
Implement whack(event) function.
Implement setEventListeners() function.
US-05: Timer
Implement startTimer() function.
Implement updateTimer() function.
US-06: Originality
Enhance the game's originality:

Change the look of the game in styles.css.
Add audio FX and music.
Include additional features like user controls, negative point sprite, or animations.
US-07: Deploying to GitHub
Deploy the game to GitHub following the instructions in the Git and GitHub module.
Acknowledgments
This project is part of the web development certificate capstone for the web development program.
