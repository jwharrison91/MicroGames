# MicroGames

1. The game can be played using either the mouse and keyboard or a game controller.
	1. For the mouse and keyboard, the mouse controls the camera position and the keyboard controls the direction to walk.
		1. Moving the mouse left and right will rotate the camera around the player. Moving the mouse down will move the camera closer to the character and moving it up will move it further away.
		2. "WASD" can be used for player movement. W - forward, S - backward, A - left, D - right.
		3. The "space" bar can be used to jump. If in the middle of a jump, the "space" bar can be pressed again and a cloud will be formed underneath the player. This jump/cloud creation action can be used to move across the terrain.
			(the clouds may appear different colors, but at this time they act the same)
	2. The escape key can be used to pause the game. Whatever is highlighted red will be the option selected. To move the choices up or down use "W" or "S".
	3. For use with a controller, the left joystick controls movement. The right joystick controls the camera. The jump and cloud behavior mentioned above is triggered with the south button on the right side of the gamepad, and the menu is triggered with the north button on the right side of the gamepad.
	4. There are two types of enemies that exist in the game:
		1. Skeletons that throw rocks:
			1. the rocks will be thrown in the direction that the player is standing when the rock is thrown. 
			2. if the rock hits the player, the player will lose health, which can be seen by the green bar in the top left corner of the screen.
		2. Jumping Bombs:
			1. Once inside a certain radius, the bombs will use AI to jump towards the predicted position of the player. 
			2. if the bomb detonates within a certain radius of the player, the player will take damage.
		3. If the player takes too much damage and the health bar is depleted, they will die. They will also die if they hit the water. This pirate cannot swim (Tommy Vercetti from Vice City couldn't swim either so we think it is ok). 
	5. There are multiple levels each with different objectives. The objective will be displayed at the bottom of the screen
	6. From the second level onward the player has the ability to cast flames from his hands and attack enemies using the left mouse button.
	7. The bombs implement a basic AI. Additionally, level 4 contains an AI racer. The fireballs implement a basic combat to make the game more engaging.
2. Issues:
	a. Sometimes a fireball will shoot in a random direction if the raycast doesn't find an object to collide with. It happens really rarely.
