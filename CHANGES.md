# version 1

Initial release features:

* Uses Phaser v1.1.4.
* solo player and two player modes.
* sounds and particle effect.

# version 2

* support touch and click movement.
* better ball and paddle collision. feels like an ice cube instead of a rubber ball.
* add many code comments.
* refactored player data in separate objects allowing for homogeneous movement code.

# version 3

* only bounce the ball off paddles and walls if it is approaching them. fixes a bug where the ball gets stuck between two bouncing states, like schroedinger's cat.

# version 4

* fix paddle start positions to avoid a race condition where the game world size does not reflect the expected value. and adjust the walls size and positioning for a more seamless play area.
* reduce goal margins to avoid very fast balls from triggering goals on successful blocks.
