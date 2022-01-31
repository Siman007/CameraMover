This is a basic C# Keyboard & Mouse control script for UNITY (tested on 2020.3.25f)

To use simply add it to your camera asset.
You can then set the amount of movement performed using the following variables -

	keyboardMoveSpeed = 25.0f;
	keyboardTurnSpeed = 5.0f;

	mouseMoveSpeed = 50.0f;
	mouseScrollSpeed = 20.0f;
	mouseTurnSpeed = 4.0f;

	minTurnAngle = -90.0f;
	maxTurnAngle = 90.0f;

For keyboard support, it implements the following
1) WASD keys with the up and down arrow keys for movement in the X,Y,Z-axis 
2) Left and right arrows rotate in the Y (or left to right)

For the mouse support, it implements the following 
1) When no mouse button is pressed it will DO NOTHING.
2) Left mouse button pressed and the mouse moved for will rotate the camera.
3) Right button pressed and the mouse moved will move the camera in X and Y-axis.
4) Both buttons pressed causes movement in the Z-axis (or zooming in and out), the amount of movement is based on the Y movement of the mouse
5) Scroll wheel pressed causes also causes zooming in and out on the Z-axis



