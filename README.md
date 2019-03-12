# CSC 335 Lab: Reversi Changes

To validate your design in the Reversi project, you are tasked with making two changes:

1. However you represented your board before, it must now be an array of java.lang.Boolean, with Boolean.TRUE being White (Computer or 'W') and Boolean.FALSE being Black (Human or 'B') and null being a blank space.

2. You now should be playing on 10 by 10 board with the initial positions in the center of the board as they were in the 8x8 game.

Note that the model choice here is deliberately "bad" to make it unlikely you actually chose this representation of the game's state. 

Clone your project, make the changes, and check it in to your section's GitHub Classroom repository.

This is a timed exercise, it is due by the end of section.

## Notes

Successful validation of the MVC architecture means that you should not have to change the view in any way. The model (and, to a much lesser extent, the controller should be able to hide these changes from the view.
