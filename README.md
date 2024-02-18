# Java Pong Game

A classic Pong game implemented in Java using Swing.

## How to Play
- Two players control their respective paddles using the keyboard.
- Player 1 uses the W and S keys to move the paddle up and down.
- Player 2 uses the Up and Down arrow keys for the same purpose.
- The goal is to hit the ball with your paddle and send it past your opponent's paddle.
- A point is scored when one player fails to return the ball with their paddle.
- The game updates the score and resets the paddles and ball position after each point.

## Features
- Classic Pong gameplay with two-player mode.
- Ball speed increases gradually to raise difficulty.
- Score tracking for both players.
- Simple and responsive paddle controls.
- The game window is set to a fixed size for optimal playability.

## References
This project was inspired by the [Java Pong Game Tutorial](https://www.youtube.com/watch?v=oLirZqJFKPE) by **[Bro Code](https://www.youtube.com/@BroCodez)**.

## Code Snippet
Here is a snippet of the `GamePanel` class which is central to the game's functionality:
```java
package com.game.pong;

// ... (imports)

public class GamePanel extends JPanel implements Runnable {
    // ... (fields and constructor)
    
    @Override
    public void paint(Graphics g) {
        // ... (paint method implementation)
    }
    
    public void draw(Graphics g) {
        // ... (draw method implementation)
    }
    
    // ... (other methods)
    
    public class AL extends KeyAdapter {
        // ... (key adapter methods)
    }
}
```

## Installation
Ensure you have Java Development Kit (JDK) installed on your system.
- Clone the repository:
- Ensure you have Java Development Kit (JDK) installed on your system.
Clone the repository:
```bash
git clone https://github.com/yourusername/javaponggame.git
```
- Navigate to the repository directory:
```bash
cd javaponggame
```
- Compile the Java files:
```bash
javac *.java
```
- Run the game:
```bash
java GamePanel
```
