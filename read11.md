# CHART.JS
Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.
# Setting Up :
At first you’ll need to download Chart.js. Then create a new html page and import the script.
## What can you do with charts?
1. Drawing a line chart.
2. Drawing a pie chart.
3. Drawing a bar chart.
The great things about Chart.js are that it’s simple to use and really very flexible. Plus, once you’ve mastered the basics here, you’ll discover that there are tons of options to do.

# Drawing shapes:
The Grid: Before we can start drawing, we need to talk about the canvas grid or coordinate space. Normally 1 unit in the grid corresponds to 1 pixel on the canvas. The origin of this grid is positioned in the top left corner at coordinate (0,0). All elements are placed relative to this origin.

# Drawing shapes with canvas
 Using < canvas> allows you to draw many things like:
 The grid: The origin of this grid is positioned in the top left corner at coordinate (0,0). All elements are placed relative to this origin. So the position of the top left corner of the blue square becomes x pixels from the left and y pixels from the top, at coordinate (x,y)

1. Rectangles: There are three functions that draw rectangles on the canvas:
#### *fillRect(x, y, width, height) Draws a filled rectangle.
#### *strokeRect(x, y, width, height) Draws a rectangular outline.
#### *clearRect(x, y, width, height) Clears the specified rectangular area, making it fully transparent.
2. Paths:A path is a list of points, connected by segments of lines that can be of different shapes, curved or not, of different width and of different color.
*** First, you create the path.
*** Then you use drawing commands to draw into the path.
*** Once the path has been created, you can stroke or fill the path to render it.
3. Triangles.
4. Moving Pen:One very useful function, which doesn't actually draw anything but becomes part of the path list described above, is the moveTo() function. You can probably best think of this as lifting a pen or pencil from one spot on a piece of paper and placing it on the next.
5. Lines:For drawing straight lines, use the lineTo() method. lineTo(x, y) Draws a line from the current drawing position to the position specified by x and y. This method takes two arguments, x and y, which are the coordinates of the line's end point.
6. Arcs:arc(x, y, radius, startAngle, endAngle, anticlockwise)
Draws an arc which is centered at (x, y) position with radius r starting at startAngle and ending at endAngle going in the given direction indicated by anticlockwise (defaulting to clockwise).

You can also make a combination of those above and more. Applying styles and colors:
Now we will explore the canvas options we have to make canvas drawings a little more attractive!
What can we style in canvas drawings?

## 1.Colors.
## 2.Transparency.
## 3.Lines styles.
## 4.Gradients.
## 5.Patterns.
## 6.Shadows.

# Drawing text
Drawing text The canvas rendering context provides two methods to render text:
fillText(text, x, y [, maxWidth]) Fills a given text at the given (x,y) position. Optionally with a maximum width to draw. strokeText(text, x, y [, maxWidth]) Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.

# Advanced text measurements
In the case you need to obtain more details about the text, the following method allows you to measure it. 
measureText() Returns a TextMetrics object containing the width, in pixels, that the specified text will be when drawn in the current text style.
**************************************
