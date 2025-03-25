# gamepadNavigation
A demo site with a js script which can transform any webpage into a gamepad navigable site

This is a work in progress, so it is not fully commented up yet.

The script first finds all button elements.  When the gamepad joysticks are moved, the script calculates the angle which the joystick is being pushed, to then calculate the closest button to the line drawn at the angle of the joystick from the currently selected button.

It also allows assigning angles to the gamepad buttons, such as the arrow buttons, so that the button for each direction can be used to navigate the page as well.