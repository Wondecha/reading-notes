
## Design with CSS

The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element.

### Block and Inline elements

Block level elements look like they start on a new line. Examples include the <h1>- <h6>, <p> and <div> elements

Inline elements flow within the text and do not start on a new line. Examples include <b>, <i>, <img>, <em> and <span>.

CSS allows you to create rules that control the way that each individual box (and the contents of that box) is presented

CSS works by associating rules with HTML elements. These rules govern
how the content of specified elements should be displayed. A CSS rule
contains two parts: 

-a selector and 
-a declaration.

CSS declarations sit inside curly brackets and each is made up of two
parts: a property and a value, separated by a colon. You can specify
several properties in one declaration, each separated by a semi-colon

# Color in CSS

Color can really bring your pages to life.

The color property allows you to specify the color of text insidean element. You can specify any color in CSS in one of three ways:

### rgb values

These express colors in terms of how much red, green and blue are used to make it up. For example: rgb(100,100,90)

### hex codes

These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash # sign. For example: #ee3e80

### color names

There are 147 predefined color names that are recognized by browsers. For example: DarkCyan

## Background Color

CSS treats each HTML element as if it appears in a box, and the background-color property sets the color of the background for that box.

You can specify your choice of background color in the same three ways you can specify foreground colors: RGB values,
hex codes, and color names. If you do not specify a background color, then the background is transparent.

Every color on a computer screen is created by mixing amounts of red, green, and blue. To find the color you want, you can use a color picker

When picking foreground and background colors, it is important to ensure that there is enough contrast for the text to be legible.

CSS3 introduces an entirely new and intuitive way to specify colors using hue, saturation, and lightness values.

## HUE

Hue is the colloquial idea of color. In HSL colors, hue is often represented as a color circle where the angle represents the color, although it may also be shown as a slider with values from 0 to 360.

## Saturation

Saturation is the amount of gray in a color. Saturation is represented as a percentage. 100% is full saturation and 0% is a shade of gray.

## Lightness

Lightness is the amount of
white (lightness) or black
(darkness) in a color. Lightness
is represented as a percentage.
0% lightness is black, 100%
lightness is white, and 50%
lightness is normal. Lightness
is sometimes referred to as
luminosity.
CSS3 introduces an entirely new and intuitive
way to specify colors using hue, saturation,
and lightness values.
CSS 3: HSL Colors
Please