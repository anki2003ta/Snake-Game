# Snake Game using Java Swing  

## Overview  
This project is a simple Snake game implemented using *Java Swing*. The game involves controlling a snake that grows as it eats food (enemy). The player must avoid colliding with the snake's body or the game boundaries. The game ends when the snake collides with itself, and the player can restart by pressing the spacebar.

---

## Features  

- *Snake Movement*: Use arrow keys to control the snake’s movement (left, right, up, down).
- *Dynamic Gameplay*: The snake grows in size each time it eats the food.
- *Game Over*: The game ends when the snake collides with itself.
- *Restart*: Press the spacebar to restart the game after it ends.
- *Graphics*: Visual representation of the snake and food with images for a more engaging experience.
- *Score Display*: The score and length of the snake are displayed at the top of the screen.

---

## Technical Features  

1. *Java Swing*:  
   Utilized for building the GUI elements like the main game window and rendering graphical components.

2. *Event-Driven Programming*:  
   The game reacts to user input and events like keyboard presses to control the snake.

3. *KeyListener*:  
   Captures key presses (left, right, up, down, and space for restarting) to control the snake.

4. *ActionListener*:  
   Used to control game mechanics by responding to timer-based events to update the game state.

5. *Timer*:  
   Manages the movement of the snake and periodic updates of the game state, creating the smooth flow of gameplay.

6. *Randomization*:  
   Generates random positions for the food to appear, making the game more dynamic and unpredictable.

7. *Graphics*:  
   Custom graphics are used to draw the game components like the snake, food, and background.

8. *Collision Detection*:  
   Detects if the snake collides with its body or the food, triggering actions like growing the snake or ending the game.

9. *Image Icons*:  
   Displays images for the snake’s body, mouth, and food, enhancing the visual appeal of the game.

10. *Game Over and Restart*:  
   The game stops when the snake collides with itself and provides an option to restart the game by pressing the spacebar.

---

## Getting Started  

### Prerequisites  
- *Java Development Kit (JDK)* 8 or higher  
- A Java IDE (e.g., IntelliJ IDEA, Eclipse, or NetBeans)  

### How to Run  

1. Clone this repository:  
   ```bash  
   git clone https://github.com/anki2003ta/Snake-Game
