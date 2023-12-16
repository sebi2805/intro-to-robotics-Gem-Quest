# Gem Quest

Welcome to **Gem Quest** - an engaging Arduino-based game where strategy, speed, and skill come together. Navigate through a maze of rooms, collect treasures, and challenge yourself to beat the high score!

Learn more about Gem Quest and its development at [thegemquest.xyz](http://thegemquest.xyz).

![Gem Quest Setup](/setup.webp)

## Game Overview

**Gem Quest** is set in a 16x16 virtual grid, displayed through an 8x8 LED matrix. The grid is divided into four 8x8 rooms, but only one room is visible at a time. Your goal is to collect treasures within these rooms, but be quick! Treasures not collected within a specific time will vanish.

### Features

- **Dynamic Rooms**: Explore four different rooms in a larger 16x16 world.
- **Treasure Hunt**: Collect treasures to score points, with quicker collections yielding higher scores.
- **High Score Tracking**: Compete for the top three high scores, saved in EEPROM.
- **Customizable Settings**: Adjust LCD and matrix brightness, sound settings, and more through an intuitive menu system.

## How to Play

1. **Navigate**: Use the joystick to move around the rooms.
2. **Collect**: Move over treasures to collect them. Speed is key!
3. **Avoid Walls**: Be careful not to run into walls while navigating.
4. **Score Points**: Collect treasures quickly to score higher.
5. **Track Progress**: Watch your score and game info on the LCD display.

## Controls

- **Joystick**: Navigate through the menu and game.
- **Button**: Select menu options and confirm actions.

## Settings Menu

- Adjust LCD and matrix brightness.
- Toggle sound settings on or off.
- View and reset high scores.

## Installation

1. Connect the LED matrix, LCD, joystick, and other components as per the schematic.
2. Upload the Arduino code to your board.
3. Power up and start playing!

## Components Used

| Component      | Function                                             |
| -------------- | ---------------------------------------------------- |
| Matrix LED     | Displays the game's 8x8 grid and visual elements.    |
| MAX7219 Driver | Controls the LED matrix, handling the display logic. |
| LCD Display    | Shows scores, game information, and settings.        |
| Potentiometer  | Adjusts brightness levels of the LCD and LED matrix. |
| Joystick       | Used for navigating through the game and menus.      |
| Button         | Selects menu options and confirms actions.           |
| Buzzer         | Provides audio feedback for game events.             |
| Wires          | Connects the components and completes the circuit.   |
| Resistors      | Ensures appropriate current flow to the components.  |
| Capacitors     | Stabilizes voltage and stores energy.                |

## Video Demonstration

[Watch Gem Quest in action here!](https://youtu.be/nOXUbVnMvQQ)

## Join the Quest

Get ready to dive into the world of Gem Quest, where every move counts. Can you top the leaderboard and become the ultimate treasure hunter?
