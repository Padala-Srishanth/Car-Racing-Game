# Car Racing Game
This is an interactive Car Racing Game built using Python and Pygame library. 
The game involves controlling a car on a three-lane road, avoiding incoming traffic, and scoring points as you progress. 
The game speed increases gradually, making it more challenging as you proceed.

# Features
Lane Switching: The player can switch lanes using arrow keys (← →) to avoid collisions.
Dynamic Traffic: Vehicles appear randomly in any lane, adding an element of unpredictability.
Collision Detection: If the player's car collides with another vehicle, the game is over.
Score System: Players earn points for successfully passing other vehicles.
Speed Increment: The game speed increases after passing every 5 vehicles.
Restart Option: After a crash, the player can choose to restart the game.

# How to Run the Game
Prerequisites
Python 3.x installed
Pygame library installed

# File Structure
Car Racing Game
│
├── images
│   ├── car.png           # Player's car image
│   ├── crash.png         # Crash image when the game is over
│   ├── pickup_truck.png  # Random traffic vehicle 1
│   ├── semi_trailer.png  # Random traffic vehicle 2
│   ├── taxi.png          # Random traffic vehicle 3
│   ├── van.png           # Random traffic vehicle 4
│
├── car_game.py           # Main game file
├── README.md             # This file

# Scoring
+1 Point for each vehicle passed successfully.
Speed increases every time you pass 5 vehicles.
If you collide with any vehicle, the game ends.

# Game Over
If your car collides with any vehicle, the Game Over screen appears.
You can choose to Restart the game by pressing Y or Quit by pressing N.

# Future Improvements
Adding background music and sound effects.
Introducing power-ups like shields or speed boosts.
Adding different levels of difficulty.
Introducing a high-score leaderboard

