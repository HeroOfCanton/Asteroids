# Asteroids
Final Project for CS4540 Spring 2016

Developed By:

Jordan Hendley, Lance Petersen, Hayden Shelton, Ryan Welling

Abstract

For this project we chose to put our own twist on the classic arcade game Asteroids. We improved the game by adding several new features which improved gameplay and appearance. The main features we added are: improved asteroid sprites and motion, sound effects, a high score table, various powerups, AI aliens, and dynamically updated levels. 

Introduction

For this assignment, we have implemented a web based version of Asteroids. Our idea was to create an updated version of this classic game. To manage the time available to us, we chose to break up the work into two sprints that were each one week long. During each sprint everyone completed the tasks that they were assigned.

Our project is a canvas based version of the game with more realistic physics and several gameplay improvements. In order to accomplish this, we leveraged a JavaScript library called Phaser.js. Phaser links Pixi.js and Physics.js into a 2D game development environment that is easy to use and modular. Utilizing this library allowed us to add physics attributes to our sprites (such as acceleration, angle, etc.) and then allow Phaser.js to do the rest. 

In addition to adding physics to the game, our version has been improved compared to the original game by adding more complex and visually appealing images to our sprites. These enhance the game and help to give it a more updated feel. However, we chose to use sprites that still give a somewhat “retro” feel to the game so as to not depart too dramatically from the spirit of the original game.

Another area where we have chosen to supplement the original game is through the addition of several powerups. These are small items that occasionally spawn upon the destruction of an asteroid for a short period of time before disappearing. If the user’s ship succeeds in obtaining one of these powerups before it disappears, they are granted a special ability. The following three powerups have been added: 1) a shield, 2) a gamma blast, and 3) a spread shot. Obtaining the shield powerup will grant the user a shield for a limited period of time. While the shield is active, the user’s ship will not be destroyed upon a collision with an asteroid. Upon obtaining the gamma blast powerup, a gamma blast is fired that clears all asteroids on the screen and progresses the player to the next level (no points are awarded for asteroids destroyed this way). Upon obtaining the spread shot powerup, the user’s ship will fire 3 lasers at a time rather than 1 for a short period of time.

An alien spaceship has been added to our game in order to increase the difficulty and to keep things more interesting. This alien has a small level of artificial intelligence (AI) and spawns periodically to make the game more difficult. Another feature that was added to keep the game interesting is dynamically updated levels. Upon clearing all asteroids from the screen, the user is notified that they have advanced to a new level and more asteroids are spawned. At the beginning of a level, asteroids are created such that they will not spawn too close to the user’s ship. As a finishing touch on the project, we also included a high score table and sound effects tied to various events. 

Tutorial

Controls: 
Left and Right Arrows - rotate ship left and right
Up Arrow - move forward
Spacebar - fire laser

The purpose of the game is to destroy asteroids and aliens while surviving. Asteroids and aliens are destroyed when a laser hits them. If your ship collides with an asteroid or is shot by a laser from an alien ship. When an asteroid is destroyed, there is a chance that a powerup will be generated for a short period of time. If your ship collects (runs into) one of these powerups, a special ability is temporarily granted. Powerups include a shield, a gamma blast that destroys all asteroids, and a spread shot that causes your ship to fire 3 lasers simultaneously. Once the game is over, you can enter your initials and the high scores will be displayed.

