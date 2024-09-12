# Game Overview
### CC
**All Default Images or Images in games are Under a fair use policy, and Created by the Developers themselves**
**For any DMCA or CC Requests, Create an issue on this repository**

## Crosshair Overlay
This Crosshair Overlay is a simple tool that allows the display and creation of crosshairs on a monitor. It supports the use of custom ".sty" files, enabling users to customize the appearance of the crosshairs. The syntax for using the Crosshair Overlays ".sty" files is as follows:

* using MONITOR INDEX - Specifies the monitor to be used.
* using Width of MONITOR INDEX - Replaces "Width" in the whole file with the actual width of the specified monitor.
* using Height of MONITOR INDEX - Replaces "Height" in the whole file with the actual height of the specified monitor.
### Features
* Support - Adds support for syntax highlighting in Visual Studio for ".sty" files
* Identify - Displays the index of each connected monitor for a short time in the top right-hand corner of each monitor
### Drawing Shapes
The Crosshair Overlay allows users to draw various shapes on the screen using the following commands:

* **Line** x, y, length, color, thickness, rotation - Draws a line on the screen with the specified parameters.
    - x: The x-coordinate of the starting point of the line.
    - y: The y-coordinate of the starting point of the line.
    - length: The length of the line.
    - color: The color of the line.
    - thickness: The thickness of the line.
    - rotation: The rotation angle of the line.

* **Arc** x, y, radius, length, color, thickness, rotation, fill - Draws an arc on the screen with the specified parameters.
    - x: The x-coordinate of the starting point of the arc.
    - y: The y-coordinate of the starting point of the arc.
    - radius: The radius of the arc.
    - length: The length of the arc.
    - color: The color of the arc.
    - thickness: The thickness of the arc.
    - rotation: The rotation angle of the arc.
    - fill: Specifies whether the arc should be filled.

* **Arc** x, y, width, height, length, color, thickness, rotation, fill - Draws an elliptical arc on the screen with the specified parameters.
    - x: The x-coordinate of the starting point of the arc.
    - y: The y-coordinate of the starting point of the arc.
    - width: The width of the ellipse.
    - height: The height of the ellipse.
    - length: The length of the arc.
    - color: The color of the arc.
    - thickness: The thickness of the arc.
    - rotation: The rotation angle of the arc.
    - fill: Specifies whether the arc should be filled.

* **Circle** x, y, radius, color, thickness, fill - Draws a circle on the screen with the specified parameters.
    - x: The x-coordinate of the center of the circle.
    - y: The y-coordinate of the center of the circle.
    - radius: The radius of the circle.
    - color: The color of the circle.
    - thickness: The thickness of the circle.
    - fill: Specifies whether the circle should be filled.

* **Circle** x, y, width, height, color, thickness, fill - Draws an ellipse on the screen with the specified parameters.
    - x: The x-coordinate of the center of the ellipse.
    - y: The y-coordinate of the center of the ellipse.
    - width: The width of the ellipse.
    - height: The height of the ellipse.
    - color: The color of the ellipse.
    - thickness: The thickness of the ellipse.
    - fill: Specifies whether the ellipse should be filled.

* **Rectangle** x, y, width, height, color, thickness, rotation, fill - Draws a rectangle on the screen with the specified parameters.
    - x: The x-coordinate of the top-left corner of the rectangle.
    - y: The y-coordinate of the top-left corner of the rectangle.
    - width: The width of the rectangle.
    - height: The height of the rectangle.
    - color: The color of the rectangle.
    - thickness: The thickness of the rectangle's border.
    - rotation: The rotation angle of the rectangle.
    - fill: Specifies whether the rectangle should be filled.

**Important:**
- length, radius, width, height and thickness all have to be > 0
- color defines an RGB HEX color, defined by #RGB
- fill only allows true or false values

These parameters allow users to customize the position, size, color, thickness, and rotation of the shapes drawn on the screen using the Crosshair Overlay.

## Guess the Number
A simple number guessing game

## Leapster
A jump and run game
