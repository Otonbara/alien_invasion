This Python script implements the game "Alien Invasion" using the Pygame library. The game involves a spaceship controlled by the player that must shoot down alien invaders before they reach the bottom of the screen. The key components of the game include:

Initialization: The AlienInvasion class initializes the game, sets up the screen, and creates game resources such as the ship, bullets, aliens, and the play button.
Game Loop: The run_game method contains the main loop, which checks for events, updates the game state, and refreshes the screen.
Event Handling: Methods like _check_events, _check_keydown_events, and _check_keyup_events handle user input from the keyboard and mouse.
Game State Updates: Methods such as _update_bullets, _update_aliens, and _ship_hit manage game dynamics like bullet movements, alien movements, and collisions.
Screen Updates: The _update_screen method renders the game objects on the screen and updates the display.
Game Controls: The game can be controlled using keyboard events for moving the ship and shooting bullets.
