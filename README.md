
# Pac-Man in Python (Pygame)

A recreation of Pac-Man built from scratch using Python and Pygame — complete with maze rendering, smooth grid-based movement, and four ghosts (Blinky, Pinky, Inky, Clyde) with distinct chase behaviors.

# Concepts I Learned

Pygame Basics: Game loop, frame rate, event handling, sprite loading, transformations, and rendering.

Grid-Based Movement: 2D maze representation, tile-based collision detection, queued turns, and screen wrap-around.

Object-Oriented Programming: Implemented a reusable Ghost class with individual states and behaviors.

Collision Detection: Used pygame.Rect for interactions between Pac-Man, ghosts, and collectibles.

Game State Management: Managed score, lives, power-ups, ghost states, win/loss conditions, and game resets.


# Challenges & Debugging
Fixed incorrect grid indexing that prevented vertical movement.

Corrected Ghost class indentation causing AttributeError.

Resolved inconsistent variable names (eaten_ghost vs. eaten_ghosts).

Added missing player collision rectangle.

Fixed incorrect deepcopy import.

Resolved ghost screen wrap-around logic by properly updating positions.



# Reference: 

This project follows along with this tutorial: Build Pac-Man in Python with Pygame!! https://youtu.be/9H27CimgPsQ?si=qkgO2Dr_Mk1r2L8A
