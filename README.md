# CPE-487: Digital System Design: Stevens Fall 2020
## Modifications Made to Lab 3: Bat and Ball
- Changed the variables responsibe for the size of the ball (8 pixels to 24 pixels)
- Changed the shape of the projectile (square to circle)
- Changed projectile color (red to cyan)
- Added horizontal motion to the projectile
## Final Project: BrickBreaker
This final project is essentially a further modified version of Lab 3: Bat and Ball. The webpage for this project can be found: [HERE](https://sites.google.com/view/andrewdesanti/brickbreaker?authuser=0)
All modifications are found within bat_n_ball.vhd. No other files required editing from their original forms in Lab 3.
### Specific Changes:
- Brick size and position definitions are found in lines 23-24, 29-52, and 59-89.
- Brick color definitions are found in lines 93-97.
- Drawing the bricks on the VGA display is found on lines 133-442.
- Collision detection for the bricks is located on lines 450-618.
