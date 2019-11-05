# HTML Colors



## CSS Background Color


In this tutorial we'll cover the basics of adding background colors using CSS to elements with fixed and variable widths. 
As a bonus we'll also demonstrate how to create perfect responsive color squares with just a few lines of code! 
Body background color
In CSS the background is considered to be the width and height of an element,
plus any padding and borders (but not margins).
Using the CSS background-color property we can color the <body> background of our HTML page red. 
![ccs background](https://i.imgur.com/qgsEakY.png)

Pretty simple, right! Of course, y
ou could always use an ID or class to give the <body> element a background color,
but this is the easiest method. Next we'll look at a couple techniques
to color the background of in-page elements like a<div>.

## RGB Value

In HTML, a color can be specified as an RGB value, using this formula:

rgb(red, green, blue)

Each parameter (red, green, and blue) defines the intensity of the color between 0 and 255.

For example, rgb(255, 0, 0) is displayed as red, because red is set to its highest value (255) and the others are set to 0.

To display black, set all color parameters to 0, like this: rgb(0, 0, 0).

To display white, set all color parameters to 255, like this: rgb(255, 255, 255).

Experiment by mixing the RGB values below:

## HEX Value

In HTML, a color can be specified using a hexadecimal value in the form:

#rrggbb

Where rr (red), gg (green) and bb (blue) are hexadecimal values between 00 and ff (same as decimal 0-255).

For example, #ff0000 is displayed as red, because red is set to its highest value (ff) and the others are set to the lowest value (00).


## HSL Value
In HTML, a color can be specified using hue, saturation, and lightness (HSL) in the form:

hsl(hue, saturation, lightness)

Hue is a degree on the color wheel from 0 to 360. 0 is red, 120 is green, and 240 is blue.

Saturation is a percentage value, 0% means a shade of gray, and 100% is the full color.

Lightness is also a percentage, 0% is black, 50% is neither light or dark, 100% is white
