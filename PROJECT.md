# Project

## Hero

  Our hero will be the playable character. He can build walls and in future will be able to upgrade the walls with the gold.

  The hero has a limited life, along with other properties, such as speed. When his life reaches 0, the game ends, and the final score is displayed.

## Monsters

  Monsters will be attacking our hero and the walls. They are stupid and basically can only go closer to the hero. If on their path they find a wall, they will demolish it after a set number of hits.

## Gold

  You can gain gold by killing monsters.

  You can spend gold by building stuff and upgrading your hero (e.g. increasing life and speed).

## Score

  Score increases every time you do something. Will do a list of things that increase the score, but obviously the main thing you can do for improving your score will be killing monsters. Even time will be a factor for improving score.

## Waves

  Will be waves of monsters. Wave 1, Wave 2, Wave 3... and the level of difficulty will increase, along with the number of monsters.

---

### Main goals, purposes of the project and things to remember in order to stay focused

**The main goal is to implement the game logic.**

#### Don't touch the canvas

  Don't mess around with the stage/canvas's dimensions. Currently they are 512 x 480 px (canvas.width and canvas.height). We don't care about this for the time being. Reason is that there are many libs/frameworks out there that are already managing these details. Will think about it at a later stage.

#### KISS

  At some point I'll consider switching to something more robust (e.g. CoffeeScript or some kind of JS library), by the way for the time being I will stick around with vanilla JS for simplicity. As the codebase will increase in size, I'll apply some patterns in order to maintain the simplicity and avoid complexities.
