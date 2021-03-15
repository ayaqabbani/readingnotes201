# creating animated charts
Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.

# Creating a Chart
It's easy to get started with Chart.js. All that's required is the script included in your page along with a single < canvas> node to render the chart.

# the canvas element
At first sight a < canvas> looks like the < img> element, with the only clear difference being that it doesn't have the src and alt attributes. 
Indeed, the < canvas> element has only two attributes, width and height. 
These are both optional and can also be set using DOM properties. 
When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high.
The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted.

# Drawing shapes with canvas
before we start drawing we need to understand the grid which is the back scene of the canvas it contains lines with several sizes.
we have rectangles, triangles, lines, arcs and curves, providing familiarity with some of the basic shapes.

# applying styles and colors 
adding different colors, line styles, gradients, patterns and shadows to your drawings to make it a little more attractive.

# color
color is a string representing a CSS < color>, a gradient object, or a pattern object.

# Transparency
In addition to drawing opaque shapes to the canvas, we can also draw semi-transparent (or translucent) shapes.
This is done by either setting the globalAlpha property or by assigning a semi-transparent color to the stroke and/or fill style.

# Line styles
There are several properties which allow us to style lines.
1. lineWidth = value
Sets the width of lines drawn in the future.

2. lineCap = type
Sets the appearance of the ends of lines.

3. lineJoin = type
Sets the appearance of the "corners" where lines meet.

4. miterLimit = value
Establishes a limit on the miter when two lines join at a sharp angle, to let you control how thick the junction becomes.

5. getLineDash()
Returns the current line dash pattern array containing an even number of non-negative numbers.

6. setLineDash(segments)
Sets the current line dash pattern.

7. lineDashOffset = value.
Specifies where to start a dash array on a line.

# shadows
Using shadows involves just four properties:

1. shadowOffsetX = float
Indicates the horizontal distance the shadow should extend from the object. This value isn't affected by the transformation matrix. The default is 0.

2. shadowOffsetY = float
Indicates the vertical distance the shadow should extend from the object. This value isn't affected by the transformation matrix. The default is 0.

3. shadowBlur = float
Indicates the size of the blurring effect; this value doesn't correspond to a number of pixels and is not affected by the current transformation matrix. The default value is 0.

4. shadowColor = color
A standard CSS color value indicating the color of the shadow effect; by default, it is fully-transparent black.

# Drawing text
how to draw text inside canvas ?
The canvas rendering context provides two methods to render text:
1. fillText(text, x, y [, maxWidth])
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.

2. strokeText(text, x, y [, maxWidth])
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.

# Styling text
There are some more properties which let you adjust the way the text gets displayed on the canvas:
1. font = value
The current text style being used when drawing text. This string uses the same syntax as the CSS font property. The default font is 10px sans-serif.

2. textAlign = value
Text alignment setting. Possible values: start, end, left, right or center. The default value is start.

3. textBaseline = value
Baseline alignment setting. Possible values: top, hanging, middle, alphabetic, ideographic, bottom. The default value is alphabetic.

4. direction = value
Directionality. Possible values: ltr, rtl, inherit. The default value is inherit.