# bongocat-fighter
https://eikamikiku.github.io/bongocat-fighter/

## Description:
Idea from https://github.com/kuroni/bongocat-osu/

## How to use:

Add browser source to OBS or whatever recording software.

## Configuration:
Add the URL parameters to the link.
The default would be:
<br>https://eikamikiku.github.io/bongocat-fighter/?gamepad=0&buttons=12,13,14,15,2,3,5,0,1,7,4&deadzone=0.4

**gamepad** parameter will pickup that gamepad number, so if you have multiple, and want another one to be used, change this number.

**buttons** parameter allows for custom button mapping.
You have to provide all buttons, if you are going to configure it.
<br>Button numbers go in order, 5-10 are buttons from bongo cat's perspective.
<br>The buttons go from left to right, first top then bottom row.

The order of buttons in the parameter:
1) Up
2) Down
3) Left
4) Right
5) 1
6) 2
7) 3
8) 4
9) 5
10) 6
11) Smoke button

You can find out what button you are pressing if you open console (F12 in browser).

**deadzone** parameter is how sensitive threshold for axes are to be counted as activated. Default is 0.4.

## ToDo:
* Hitbox support.
