<p align="left"><img src="https://raw.githubusercontent.com/sofycodes/consoleMe/main/icon.png" style="display:block; margin:auto; width:300px"></p>
<h1 align="left">Genesis 0.5.0</h1>

<p align="left">A simple package adding custom origns for GameMaker LTS 2022+</p>

## Installation
1. [Download the .yymps](https://github.com/sofycat/Genesis/releases/)
2. Import the package in `Tools` -> `Import Local Package`. 
3. Ready to go!

## Quick quide
### Step Event
```c
var firing_spot_x = new_orign_point_x(x,y,10,-5,image_angle)
var firing_spot_y = new_orign_point_y(x,y,10,-5,image_angle)

instance_create_layer(firing_spot_x,firing_spot_y,"instances", oBullet)
```
This creates a "firing spot" 10 pixels to the left and 5 pixels up similar to how you would use "emptys" in unity
