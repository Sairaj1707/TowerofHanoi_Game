# Tower Of Hanoi Game

## Overview

This web-based project simulates the **Tower of Hanoi** puzzle. Users can play the game manually using drag-and-drop or auto-solve it with a recursive algorithm that calculates and animates the optimal sequence of moves.

## Features

-  **Interactive Gameplay** - Drag and drop disks between poles with real-time rule enforcement.
-  **Restart & Disk Adjustment** - Choose from 3 to 8 disks and restart the game anytime.
-  **Move Counter & Logging** - Tracks number of moves and logs the solution steps.
-  **Auto-Solver** - Visually demonstrates the recursive optimal solution.

## Use Cases

-  **Educational Tool** - Teach recursion and problem-solving in computer science classes.
-  **Algorithm Demonstration** - Visualize how recursive backtracking works.
-  **Puzzle Game** - Provide a fun and challenging brain game.

## Algorithm

The project uses a **recursive backtracking algorithm**, also understood as a **Depth-First Search (DFS)** approach, to solve the Tower of Hanoi problem.

### Recursive Algorithm (Minimal Moves)
```javascript
function hanoi(from, to, buf, n) {
    if (n > 1) {
        hanoi(from, buf, to, n - 1);
        my.moves.push([from, to]);
        hanoi(buf, to, from, n - 1);
    } else {
        my.moves.push([from, to]);
    }
}

```
## Screenshot's :

- Game Pages -
  
  ![image](https://github.com/user-attachments/assets/863f1aaf-1df6-4ac8-8d64-e68a63653fb6)

  ![image](https://github.com/user-attachments/assets/4c8ffc5d-1539-42ef-9c2b-793740c45e9e)

  ![image](https://github.com/user-attachments/assets/06a21b45-9194-46db-be9e-cae3c6d26f1d)
