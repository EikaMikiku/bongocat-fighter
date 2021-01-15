# bongocat-fighter
https://eikamikiku.github.io/bongocat-fighter/

## Description:
Idea from https://github.com/kuroni/bongocat-osu/

## How to use:

Add browser source to OBS or whatever recording software.

## Configuration:
Add the URL parameters to the link.
The full default URL would be:
<br>https://eikamikiku.github.io/bongocat-fighter/?gamepad=0&buttons=12,13,14,15,2,3,5,0,1,7,4&deadzone=0.4&ap2s=15

Parameter  | Default | Note
------------- | ------------- | ------------- |
gamepad  | 0 | Gamepad index.<br>If you have multiple connected, and want a different gamepad to be used, change this number.
buttons  | 12,13,14,15,2,3,5,0,1,7,4 | Allows for custom button mapping.<br>You have to provide all 11 buttons if you are going to change this.<br>More info [here](#buttons-parameter).
deadzone | 0.4 | How sensitive threshold is for axes to be counted as activated.
ap2s | 15 | How many actions per about 2 seconds you have to do until you get a tryhard bongo cat face.

## Buttons parameter:
You have to provide all buttons, if you are going to configure it.
<br>Button numbers go in order, buttons are from bongo cat's perspective, including directions.
<br>The buttons(5-10) go from left to right, first top then bottom row.

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

## ToDo:
* Hitbox support.
