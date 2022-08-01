# flappy-pong
Just a game. (lol)

  There's not really much to this.
    There are 3 versions of the game.
    1.The original
    2.Version 1.0.1
    3.Version 1.1.0



CHANGELOG

1.0.0
After I copied the original code

1.0.1
-Adding 2 HP and 2 Max HP everytime you pass/*enter* a wall
-When you play, Instead of 100 HP and 100 Max HP, You have 255 HP and 255 Max HP(This relates to the next change in this game)
-Ball color is connected to the HP

Code changes:

void score() {
  maxHealth += 2
  health += 2
  score++
}

float maxHealth = 255
float health = 255

fill(255, 255, health)

1.1.0
-Points!
-FPS counter and FPS cap
-Rounded Health values(using int(drawmaxHealth, health), not float(maxHealth, health))

Code changes:

*Check the code...(flappy-pong/flappypong1_1/flappypong)*
