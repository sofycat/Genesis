<p align="center"><img src="https://raw.githubusercontent.com/sofycodes/consoleMe/main/icon.png" style="display:block; margin:auto; width:300px"></p>
<h1 align="center">Genesis 0.5.0</h1>

<p align="center">A simple package adding custom origns for GameMaker LTS 2022+</p>

&nbsp;

&nbsp;
- ### [Download the .yymps](https://github.com/sofycat/Genesis/releases/)
- ### Read the [documentation](https://github.com/sofycat/Genesis)

## Quick quide
### Step Event
```c
var firing_spot_x = new_orign_point_x(x,y,10,-5,image_angle)
var firing_spot_y = new_orign_point_y(x,y,10,-5,image_angle)

instance_create_layer(firing_spot_x,firing_spot_y,"instances", oBullet)
```
This creates a "firing spot" 10 pixels to the left and 5 pixels up similar to how you would use "emptys" in unity
