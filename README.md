# HTML---SnakeGame
Game Setup: The snake starts with a length of 1 at position (10, 10), and food is placed randomly on the screen.
Snake Movement: The snake moves according to the user input (W, A, S, D for up, left, down, and right). Each time the snake moves, the body parts follow the head.
Game Over Condition: The game ends if the snake hits the walls or collides with itself.
Food Consumption: When the snake eats food (denoted by *), its length increases by 1 and the score increments. New food is placed randomly on the board after each consumption.
Display: The game is displayed on a 20x20 grid with boundaries drawn on the top and bottom.
You can modify the grid size and game speed according to your needs.

How to Create an Executable File
To create an executable file from the above code:

Use Electron:

Install Node.js
Install Electron: npm install electron --save-dev.
Create a main.js file to launch the index.html.
Package it using tools like electron-packager or electron-builder.

Run Locally:

Save the HTML code as index.html.
Open it in any modern web browser.
Progressive Web App (PWA):

Use your browser's "Add to Desktop" or "Install App" option for standalone execution.
