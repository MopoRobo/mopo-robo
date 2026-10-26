# mopo-robo
Code for the Mobridge-Pollock robotics team
Current year: 2026-2027

**2026-2027 Code Documentation**

PURPOSE: 
Allow the robot to move and interact with its environment, scoring as many points as possible as efficiently and quickly as possible while maintaining natural-feeling controls.

LAYOUT: 
Axis 3: Left motor, channel 1
Axis 2: Right motor, channel 2

TECHNIQUES: 
Used the code from last year as a starting point, drastically reducing the time it took to test and fix.
Uploaded code to GitHub instead of Google Drive for better organization

TOOLS:
VEXcode in a web browser
ChromeBook

VERSION NUMBER NAMING SYSTEM:
x.x.x
The first digit is for final competition versions: 1 is for state, 2 is for region, etc. Version 0 is for prototyping purposes only.
The second digit is for major changes: adding/removing systems/devices, restructuring, major optimizations, etc. 
The third digit is for minor changes: small bug fixes, minor optimizations, etc.

CHANGELOG:

v0.1.0:
Created the first code version
Created basic movement controls with placeholder values for voltage

v0.1.1:
Flipped an inequality in motor 2, which made it so the motor could only move in reverse
Inverted values in motor 1 to make it go the correct direction

v0.2.0
Converted code from Blocks to Python
Added comments to make the code easier to read
