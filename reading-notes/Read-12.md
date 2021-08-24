## ***Chart.js API***

### EASILY CREATE STUNNING ANIMATED CHARTS WITH CHART.JS
- Charts are used as a way to display data and have a better visual appeal than tables or lists
- Chart.js is a JS plugin that uses the HTML canvas element to create a graph on your webpage
- Chart.js can create different types of charts to include bar charts, lines charts, and pie charts
- A chart is created by performing a few simple steps:
1. Download Chart.js and put the file in your JS project folder
2. Link the JS file to your HTML page
3. Create a canvas element in your HTML file
4. Get the element in your JS file and create a chart variable
5. Finally, create a data variable to include your data and dataset styling

## ***Canvas API***

### Basic Usage
- The canvas element is similar to an image element but lakes an alt or src attribute
- The canvas element can utilize fallback content for pages that do not support it
- A closing canvas tag is required unlike in an image tag
- JS is needed to render content within the tag

### Drawing Shapes with Canvas
- Canvas uses a grid system to draw shapes. To draw a rectangle the syntax is as follows:
>fillRect(x, y, width, height)

- Different shapes include rectangles, triangles, Quadratic Bezier curves, Cubic Bezier curves, arcs, and combinations
- Paths are then created using a path function. These form how the shape will appear

### Drawing Shapes with Canvas
- Many stylings can be provided on a Canvas element
- Color styling includes fill and stroke colors
- Transparency can also be applied
- Different line styling includes width, endlines, line joins, and dashing
- Gradients, shadows, and patterns can also be applied as styling
- Styling of charts within a canvas element is applied in the JS of a directory and not using CSS. Example syntax is as follows:
> linearGradient(x1, y1, x2, y2)
*This creates a linear gradient object*
> lineWidth = 10;
*This changes the line width of a chart*

### Drawing text
- Canvas has two methods to render text:
  1. fillText: This will fill text at a given point
  2. strokeText: This will stroke text at a given point
- Text in the canvas element can be styled similar to HTML text but through JS and not CSS
